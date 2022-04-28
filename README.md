# clientes_django

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/LombaAnderson/clientes_django/blob/main/LICENSE)

# Sobre o projeto
O projeto Librairie_Django é uma API Django Rest framework onde se pode cadastrar nome, autor, ano que saiu o livro, seu estado, número de páginas e editora. Dessa forma é possível cadastrar livros, apagá-los, deixá-los registrados com as opções GET, POST, HEAD e OPTIONS. A título de exemplo no caso de OPTIONS é possível utilizá-lo para que um cliente descobra quais as opções de requisição permitidas para um determinado recurso em um servidor. Inicialmente é preciso configurar o settings.py e em seguida é necessário criar as models onde ficarão todas as informações descritas acima. Foram feitos testes manuais e unitários para verificar se está tudo ok e utilizado python decouple com intuito de preservar a chave. 

## Imagem de exemplo de cadastro de livros
<div align="center">
<img src="https://user-images.githubusercontent.com/60937513/145520946-99122343-e0f7-425c-b78f-2df14ce928be.png" width="700" />
</div>

# principais Tecnologias utilizadas
- Python
- API Django Rest

 Principais Frameworks
-Django==3.1.3
-djangorestframework==3.13.1
-django-filter==21.1


# Instruções para compilar, testar e rodar o projeto

```bash
# Clonar repositório
git clone https://github.com/LombaAnderson/clientes_django

# Criação e acesso da pasta do projeto
-mkdir clientes
-cd clientes

# Criação do ambiente de desenvolvimento do Python
-python -m venv venv

# Ativar o ambiente de desenvolvimento(venv)
-source venv/Scripts/.activate

# Instalação do Django (Atenção: instalar somente após a ativação da venv)
-pip install django

# Instalação do pacote do Django Rest Framework
-pip install django djangorestframework
 
# Comando de criação do projeto
-django-admin startproject projeto_clientes .

# Criação do servidor
-python manage.py runserver

# Acesso ao servidor Django
http://127.0.0.1:8000/

# Apps 
-django-admin startapp clientes

# Preparação das migrations
- python manage.py makemigrations

# Envio das migrations configuradas para o banco de dados
- python manage.py migrate

```

# Autor

Anderson Lomba de Oliveira

Linkedin

https://www.linkedin.com/in/anderson-lomba-140279142/

Portfólio

https://www.lombanderson.epizy.com

# Agradecimentos

Agradeço ao meu Deus que sempre me ajuda e a minha esposa que amo muito! 



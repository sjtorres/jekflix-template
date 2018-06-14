---
layout: post
title: Criando uma app em Django
tags:
- aplicação
- django
- instalação
- passo a passo.
- python
---#Criando uma app em Django

Vamos criar uma aplicação em Django? Nesse tutorial você vai aprender passo a passo, como criar uma aplicação web de cadastro de pessoas que pode ser utilizado tanto para uma clínica odontológica que será o nosso caso ou também para qualquer sistema que exige um cadastro de clientes.

Esse Projeto está sendo desenvolvido como trabalho final da Faculdade 
[FATECIE](http://fatecie.edu.br/faculdadefatecie) do curso de Sistemas Para Internet, pelos acadêmicos: 
[Wesley](https://github.com/wesleyadonay), 
[Tiago](https://github.com/TiagoHavro) e 
[Sandro](http://sandrotorres.com.br/), da turma de 2017.

O que vou passar para vocês é um projeto simples de cadastro de clientes, que pode ser utilizados em várias aplicações, no nosso caso, vou criar um cadastro de pacientes de uma clínica odontológica.

##Ambiente Virtual

Bom á princípio teremos que criar um ambiente virtual para que possamos instalar o django e começar a desenvolver. Para saber mais sobre ambiente virtual no Django, olhe esse Post, que explica tintin por tintin, 
[sobre o virtualenv](https://sandrojtorres.wordpress.com/2017/10/17/django-guia-de-instalacao-passo-a-passo/) e a instalação do Django no windows.

Visite também 
[meu site](http://sandrotorres.com.br/) e se cadastre na Newsletter para receber por e-mail novidades.

##Estrutura do Projeto


*Ambiente: env_odonto

	
*Projeto: odonto

	
*Aplicação: cadastro

	
*Classe: pacientes

	
*Atributos:

*nome

	
*CPF

	
*nascimento

	
*e-mail

	
*telefone

	
*criado em

##Criando o ambiente virtual

Nessa etapa vamos criar um ambiente virtual para que possamos instalar plugins e bibliotecas que não interfiram em outros projetos.


![Django Projeto](https://sandrojtorres.files.wordpress.com/2017/11/virtualenv.jpg)

*$ pip install virtualenv

	
*$ virtualenv env_odonto

	
*$ cd env_odonto

	
*$ cd Scripts

	
*$ activate.bat

	
*$ cd..

##Pronto para receber o Django?

Agora vamos instalar o Django, ferramenta extraordinária que facilita muito a vida dos desenvolvedores.


![importDjango](https://sandrojtorres.files.wordpress.com/2017/11/installdjango.jpg)

*$ pip install django==1.11.3

	
*$ python

	
*>>> import django

	
*>>> django.get_version( )

##Criando o Projeto e o App

Nessa parte vamos criar a pasta do projeto (odonto) e a do app (cadastro), propriamente dito. De acordo com a imagem, tem computadores que não vão aceitar o comando - 
**django-admin.py**
 - com a extensão .py. Sendo assim é só digitar o comando 
**django-admin**
 sem a extensão .py que vai funcionar.


![django projeto](https://sandrojtorres.files.wordpress.com/2017/11/criandoprojectapp.jpg)

*$ django-admin startproject odonto

	
*$ cd odonto

	
*$ django-admin startapp cadastro
 

##Rodando o servidor


![executando Server](https://sandrojtorres.files.wordpress.com/2017/11/runserver.jpg)

*$ python manage.py runserver

![conectado](https://sandrojtorres.files.wordpress.com/2017/11/conectado.jpg)

##Finalizando...

Bom pessoal, no próximo post vamos finalizar a parte do projeto que cria os templates já com os htmls e forms.py é no terceiro post finalizo com o CSS.

Um abraço para todos e se quiserem comentar para sanar alguma dúvida, fiquem a vontade. Também estou aberto a sugestões para melhoria do projeto.

Logo logo, estarei publicando esse projeto no 
[meu github](https://github.com/sjtorres), podendo assim qualquer um usar ou melhorar o projeto.

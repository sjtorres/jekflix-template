---
layout: post
title: Django - guia de instalação passo a passo.
tags:
- django
- guia
- instalação
- passo a passo.
- python
---##O que é Django?

Bom, nesse artigo vamos aprender de maneira simples e descomplicada a fazer a instalação do Django. Mas o que é Django mesmo?

O Django é um framework gratuito utilizado para a criação de aplicações web, escrito em Python. É um framework web, ou seja, é um conjunto de componentes que ajuda a desenvolver sites de forma mais rápida e mais fácil.

##Virtualenv

O virtualenv é uma ferramenta que permite que criemos ambientes virtuais isolados para projetos Python.

Permite que cada ambiente tenha autonomia para instalar plugins e bibliotecas de forma que a configuração de um ambiente não impacte nos restantes.

##Instalando o Virtualenv

Instalando e criando o seu primeiro ambiente virtual com o virtualenv:

*Comando instalação:  
**$ pip install virtualenv**

	
*Comando criação do ambiente virtual: 
**$ virtualenv  newProject**

	
*Entrar na parta newProject: 
**$ cd newProject**

	
*Entrar na pasta Script:  
**$ cd Script**

	
*Ativando o ambiente virtual:
**  $ activate.bat**
Pronto seu ambiente virtual está 
**pronto**
 
**para receber o Django**
.

##Instalando o Django

Agora dentro da pasta 
**newProject**
 vamos executar os seguintes comandos:

*Comando instalação: 
**$ pip install Django==1.11.3**

	
*Importando o Django para o Python: 
**$ python**


*Dentro do Python digite:  
**>>>import django**

	
*Ainda no Python digite:  
**>>>django.get_version( )**
Se der tudo certo, vai aparecer a versão instalada do Django:
**  >>> 1.11 .3**


##Criando uma aplicação

Por fim criaremos uma aplicação dentro da pasta 
**newProject**
 que criamos:

*Criando e dando nome a aplicação:
**$ django-admin.py startproject newAplicacao**

	
*Entre na pasta 
**newAplicacao**
 e digite:
**$ python manage.py runserver**
O resultado:

##![fig01](https://sandrojtorres.files.wordpress.com/2017/10/fig01.jpg)


## Concluindo

Quem gostou ou tem alguma dica ou encontrou um jeito diferente de de executar esse comando, pode deixar nos comentário que responderei o mais rápido possível.

Há, quase ia me esquecendo,  todo esse material foi resumido do conteúdo do professor Tiago Piperno da Faculdade de Tecnologia e Ciências do Norte do Paraná - FATECIE.

Pessoal uma abraço para todos, e podem esperar para próxima semana vamos começar a criar Post e uma Carteira de cliente utilizando o framework Django.

 

---
layout: post
title:  "Integrando Django com Keycloak"
date:   2018-05-11 07:00:00 +0300
categories: django
image:  /images/posts/keycloak.png
---


Eai pessoal!

No post de hoje irei apresentar de forma susinta como é possível realizar a integração do Django com o **Identity and Access Management [Keycloak](https://www.keycloak.org)**, substituíndo parcialmente a autenticação default do Django.

Para isso, utilizaremos o projeto [Getting Started with Django 2](https://github.com/marcospereirampj/django2-getting-started) como base e tomaremos como premissas os seguintes requisitos:

1. Deveremos utilizar o protocolo [OpenID](http://openid.net/). 
2. O sistema deverá autenticar-se utilizando a API do Keycloak (não deveremos utilizar a tela default do Keycloak).
3. Deverão ser removidos os módulos de autenticação default do Django.
4. O Token gerado pelo Keycloak deverá ser assinado utilizando RS256.

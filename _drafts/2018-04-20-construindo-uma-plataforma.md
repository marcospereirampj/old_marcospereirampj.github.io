---
layout: post
title:  "Agriness 365: a construção de uma plataforma"
date:   2018-04-20 19:00:00 +0300
categories: development
image:  /images/posts/agriness365.jpg
---

Hi guys! I'm back! 

(Well, It's my first post in English, so sorry any errors :D)

On post today, I'll talk about an process that ---------- on the last 11 months and result was presentation on INFO360, organizzed by Agriness. It's about the process construction of a platfom.


=============================


Na postagem de hoje irei falar um pouco sobre um processo que venho participando nos últimos 11 meses e cujo resultado foi apresentado no [INFO 360](http://info360.agriness.com/) organizado pela Agriness. Trata-se do processo de construção de uma Plataforma.

Nesse artigo não discuteremos muito sobre as tecnologias utilizadas, focaremos nos conceitos, metodologias e padrões que nos guiaram durante todo o processo e nas tomadas de decisões.

Então, vamos lá!

## Antigo Cenário: o monolítico

Mesmo com o fortalecimento de conceitos como microserviços, integração, mensagerias, API's, etc, grande parte das solux ções ainda nascem como grandes monolíticos. Provalvemente, isso se deve ao fato de que monolíticos são mais flexíveis quanto as mudanças de requisitos - já que está tudo praticamente no mesmo sistema/projeto. Além disso, não existe a necessidade de camadas e interfaces de integrações com outras partes do sistema - o que simplifica o desenvolvimento.

Antes da decisão de mudança arquitetural, esse era o cenário do meu atual desafio. Praticamente todos os módulos do sistema estavam acomplados em um único grande projeto com várias customizações que o tornava ainda mais complexo e dependente da tecnologia usada.

Com a necessidade da evolução do sistema era imprecidível realizar ajustes no processo e arquitetura. Além disso, tudo deveria ocorrer sem interferir no cronograma da contrução da solução..

## Por que mudar?

A decisão de mudança arquitetural surgiu após a necessidade de evolução da solução que estava sendo desenvolvida. A equipe percebeu que expandir o que estava sendo construido poderia sair muito caro no futuro. Então, resolvemos estudar e desenhar qual seria a melhor opção para a solução que estava sendo proposta.

Foram várias semanas de estudos e testes de tecnologias que poderiam nos auxiliar no projeto (indico a leitura do livro [Platform Revolution: How Networked Markets Are Transforming the Economyand How to Make Them Work for You](https://www.amazon.com.br/Platform-Revolution-Networked-Transforming-Economyand-ebook/dp/B00ZAT8VS4?qid=1526350078&sr=1-1&ref=sr_1_1)). Foram realizados vários benchmarkings e reuniões de pró/contra para chegarmos a uma decisão.

Bom, após todo esse estudo ficou nítido que o que estavámos construíndo não era um simples sistema web, mas uma plataforma. E para obtermos sucesso era preciso tratar o projeto como tal, focando no baixo acomplatamento, escalabilidade, performance e interação com usuário - basicamente esses eram nossos pontos focais.

## Por onde começar?

Entendido o problema que estamos enfrentando precisávamos agora montar um estratégia para atacá-lo.

## Agriness 365
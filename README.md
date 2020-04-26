Demo: [https://tech-eventos.netlify.app/](https://tech-eventos.netlify.app/)

[![Netlify Status](https://api.netlify.com/api/v1/badges/2cc22fd5-8eb4-48c8-8459-f9c3ebdaf545/deploy-status)](https://app.netlify.com/sites/tech-eventos/deploys)

# EventosTI

Agregador das maiores conferências de desenvolvimento do Brasil.

O [https://tech-eventos.netlify.app/](https://tech-eventos.netlify.app/) é uma iniciativa criada para a comunidade com o propósito de trazer em um único ambiente todas as conferências de desenvolvimento, tecnologia e afins que estarão rolando Brasil a fora!

## Vindo da comunidade para a comunidade 

O projeto foi criado para ser totalmente colaborativo, feito da comunidade para a comunidade. Caso alguém queira adicionar alguma conferência ou evento basta fazer aquela PR seguindo o modelo abaixo e pronto!

Além de deixar o seu GitHub verdinho, vai facilitar a vida de todos nós **devs** que nunca sabemos qual e quando será a próxima conferência a ocorrer!



## Modelo de PR para conferências

Nome do arquivo: `yyyy-mm-dd-titulo-da-sua-conferencia-yyyy.md`

Template:

```markdown
---
layout: post                                                # Layout do post, deixar por padrão post.
title: 'Título da sua conferência 2020'                     # Título da conferência.
date:   2016-04-30 10:51:47 +0530                           # Data de início da conferência no formato yyyy-mm-dd sem aspas.
categories: python                                          # Lista de tags associadas a sua conferência. Ex: Linguagem (js) e estado (sp). Caso seja mais de uma linguagem use apenas geral.
img: pugce.png                                              # imagem de divulgação da palestra dimensão 400x250

---

Aqui você pode cadastrar todas as informações úteis que encontrar sobre a conf! <!-- Descrição da sua conferência. -->

 ```
 
 O arquivo deve ser adicionado à pasta `_posts`


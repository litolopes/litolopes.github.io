---
layout: post
title: "Como contribuir com comunidades Open Source - Contribuindo com o OpenShift"
date: 2018-08-15 15:00:00 -03:00
author: Wellington Carlos Lopes - litolopes
comments: true
---

A importância do engajamento, participação e contribuição nas comunidades Open Source é um tema bastante discutido atualmente e muito bem recebido pelos profissionais das mais diversas áreas. Tenho recebido contato de estudantes de cursos, como: Tecnologia em Eventos, Agronomia, Gestão Energética, Letras, etc.

O modelo de contribuição através de comunidades têm ultrapassado as barreiras e está chegando em outras áreas do conhecimento muito além do mercado de TI. 

Independentemente da área de atuação, quando uma pessoa decide conhecer mais o modelo Open Source e se engajar em comunidades globais de desenvolvimento, a primeira pergunta que surge é: "Como eu faço para me tornar um contribuidor da Comunidade ?"

Como escrevi no artigo sobre como contribuir com a Comunidade Fedora [post][como-contribuir-fedora], tanto profissionais experiêntes quanto jovens estudantes, enfrentam alguns desafios para iniciar as contribuições em comunidades Open Source. Nesse artigo foi apresentado o passo-a-passo no processo de registro na Comunidade Fedora, e o inicio do processo de contribuição. 

Além da comunidade Fedora, atualmente existem mais de 1.800.000 comunidades e projetos abertos no GitHub. Cada comunidade apresenta uma série de oportunidades para novos contribuidors. No mercado de TI, um tema que está em evidência é a infraestrutura baseada em containers, que permite maior flexibilidade e agilidade na gestão de aplicações. O conceito de PaaS - Plataforma as a Service, baseada em containers, é implementado através da tecnologia (e da comunidade) OpenShift. 

A comunidade OpenShift pode ser encontrada em [GitHub][openshift-origin-github]  é dividida em vários sub-grupos de trabalho que se especializam em alguns temas, entre eles: 

* OpenShift OPS
* Machine Learning on OpenShift
* OpenShift .EDU
* OpenShift Image Builders
* OpenShift Big Data
* OpenShift .NET
* OpenShift .GOV
* OpenShift on OpenStack
* OpenShift in Automotive
* Mobile on OpenShift 
* Operatir Framework


Para se tornar un contribuidor na comunidade OpenShift é necessário alguns passos. 

# 1 - CADASTRO

No link [post][openshift-project] é possível cadastrar-se utilizando uma conta de email.


{% include image-local.html
        img="images/openshift/cadastro-openshift.png"
        title="Cadastro de email na comunidade OpenShift ."
        caption="cadastro-openshift" %}

Um exemplo de um grupo de desenvolvimento do OpenShift é o "Machine Learning on Openshift". Esse grupo tem como objetivo discutir e desenvolver as práticas para adoção de Machine Learning em aplicações para instalação e execução no OpenShift 

Na página de cada grupo o contribuidor encontrará informações sobre os temas de interesses do grupo, lista de contribuidores, agenda de eventos, agenda de reuniões, além do Blog com artigos com conteúdos específicos de tema principal do grupo. 

Para se registrar em um desses grupo basta informar seu email , conforme a imagem abaixo: 

{% include image-local.html
        img="images/openshift/openshift-machinelearning.png"
        title="Grupo de Machine Learning da comunidade OpenShift ."
        caption="machinelearning-openshift" %}

Além disso, todo o projeto OpenShift está armazenado no GitHub no link: github.com/openshift/origin

Dentro do projeto no GitHUb, a comunidade apresenta um guia com as informações para os contribuidores. Esse documento pode ser acessado em: https://github.com/openshift/origin/blob/master/CONTRIBUTING.adoc


# 2 - CONTRIBUIÇÃO 

Cada grupo de desenvolvimento dentro da comunidade possui suas proprias atividades, demandas de desenvolvimento e um planejamento em relação ao Roadmap da tecnologias. 

Depois de ter realizado o cadastro na comunidade, é possível buscar informações sobre todas as demandas de desenvolvimento para as releases do OpenShift. 

A visão geral do roadmap está disponível no link: https://ci.openshift.redhat.com/roadmap_overview.html

{% include image-local.html
        img="images/openshift/road-map-openshift.png"
        title="Roadmap da comunidade OpenShift ."
        caption="road-map-openshift" %}

O roadmap apresenta a lista de atividades agrupadas por cada sub-grupo (como os listados acima), qual Release planeja-se incluir a funcionalidade e qual é o grupo (Board) que lidera do desenvolvimento.

Clicando em uma das atividades, você será redirecionado ao Trello com a descrição da atividade, todo o log de interações dos contribuidores. 

{% include image-local.html
        img="images/openshift/trello-OpenShift.png"
        title="Trello da comunidade OpenShift ."
        caption="trello-OpenShift" %}

Notem que abaixo da descrição da atividade existe um link para o BugZila. No caso dessa atividade o link é:  https://bugzilla.redhat.com/show_bug.cgi?id=1427022
  
O BugZila é a ferramenta onde se registra todas as necessidades de desenvolvimento, sejam elas de correção ou de novas funcionalidades. Para a atividade apresentada como exemplo, temos as seguintes informações: 

{% include image-local.html
        img="images/openshift/bugzila-openshift.png"
        title="BugZila da comunidade OpenShift ."
        caption="bugzila-openshift" %}

Através do BugZila é possível consultar as informações referentes a atividade, como por exemplo: 

- Status: **Nova**
- Qual componente:  **RFE** 
- Prioridade: **Média**
- Data e quem reportou o problema: **2017-02-27 01:19 EST by Jaspreet Kaur**	
- Quem é o responsável pela atividade: **Ben Parees**
- Quem é o responsável pelo QA: **Xiaoli Tian**


# 3 - COMUNICAÇÃO

As ferramentas de comunicação adotapa pelos contribuidores da comunidade OpenShift são: 

IRC: **#openshift-dev** no **FreeNode**.

E-mail: Cadastre-se para fazer parte da lista de desenvolvedores [site][email-cadastro].


Aproveite para contribuir, se desenvolver profissionalmente e, principalmente, "conhecer" outros contribuidores ! 


[email-cadastro]: http://lists.openshift.redhat.com/openshiftmm/listinfo/dev
[openshift-roadmap]: https://ci.openshift.redhat.com/roadmap_overview.html
[openshift-roadmap-trello]: https://trello.com/b/nlLwlKoz/atomicopenshift-roadmap
[openshift-project]: https://commons.openshift.org/
[openshift-guidelines-contribution]: https://github.com/openshift/origin-server/blob/master/CONTRIBUTING.md
https://github.com/openshift/origin/blob/master/CONTRIBUTING.adoc
[openshift-origin-github]:https://github.com/openshift/origin 
[como-contribuir-fedora]: https://litolopes.github.io/2018/02/contribuindo-com-o-projeto-fedora

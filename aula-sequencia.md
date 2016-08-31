---
layout: page
categories: aula
title: "Diagrama de sequência (prática, vale ponto)"
date: 2016-08-29 20:20:00 -0300
---

Exemplo de diagrama de sequência na vida real: [diagrama de sequência do protocolo CAS]({{site.baseurl}}/files/cas-sequence.png).

## Exercício (enviar para rodrigo@dcc.ufba.br até 04/09, por equipe do projeto)

Vamos desenhar diagramas de sequência do jogo da forca. Primeiramente, baixe o [código-fonte do forca]({{site.baseurl}}/files/forca.zip).

A seguir, use o [Astah](astah.net) para criar um modelo a partir do código Java. Caso esteja usando a versão Community, use [este arquivo]({{site.baseurl}}/files/forca-classes.asta) com as classes já importadas.

Depois disso, desenhe um diagrama de sequência para o fluxo principal do jogo, implementado na classe `Main`, mostrando sua interação com objetos das classes `Campeonato`, `Jogador`, `Partida` e `Letra`.

Por fim, desenhe um diagrama de sequência para o caso de uso "jogar letra", mostrando a sequência de interações que acontecem quando o jogador escolhe uma letra. Certifique-se de modelar os casos alternativos (jogador acertou e jogador errou).

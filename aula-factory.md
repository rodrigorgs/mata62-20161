---
layout: page
categories: aula
title: "Atividade: Factory Method e Abstract Factory"
date: 2016-10-03 20:20:00 -0300
---

## Atividade: Factory Method e Abstract Factory (vale nota)

**Material**: [padroes-criacao.zip]({{site.baseurl}}/files/padroes-criacao.zip) (projeto Eclipse na linguagem Java)

Baixe o material, descompacte e abra no Eclipse. Trata-se de um sistema para gerar documentação em dois formatos: HTML e [Markdown](http://commonmark.org/help/). A geração da documentação é feita na classe `CriadorDocumentacao`, que cria um documento em três partes: `Cabecalho`, `Corpo` e `Rodape`.

**Discussão em aula**. Suponha que queremos adicionar um novo formato, LaTeX. Quais classes é preciso alterar? Se `CriadorDocumentacao` fosse parte de uma biblioteca (que você não pode alterar), como você adicionaria um novo formato?

**Atividade**. Crie uma cópia do projeto original, com nome `padroes-factory-method`, e aplique o padrão Factory Method para tornar `CriadorDocumentacao` independente do formato da documentação.

**Discussão em aula**. E agora, como você faria para adicionar um novo formato sem alterar a classe `CriadorDocumentacao`?

**Atividade**. Crie uma cópia do projeto original, com nome `padroes-abstract-factory`, e aplique o padrão Abstract Factory para tornar `CriadorDocumentacao` independente do formato da documentação.

**Discussão em aula**. Quais os prós e os contas de cada solução (Factory Method vs Abstract Factory)?

**Entrega**. Crie um arquivo `.zip` contendo as duas pastas dos projetos derivados (`padroes-factory-method` e `padroes-abstract-factory`) e envie para <rodrigo@dcc.ufba.br> até ~~domingo, 9 de outubro de 2016~~ **26/10/2016**.



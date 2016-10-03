---
layout: page
categories: aula
title: "Padrões de projeto"
date: 2016-09-21 20:20:00 -0300
---

## Referências

- Curso - Padrões de Projeto (Prof. Vítor Souza, UFES): [introdução](http://www.inf.ufes.br/~vitorsouza/wp-content/uploads/java-br-curso-padroesdeprojeto-slides01.pdf), [criação](http://www.inf.ufes.br/~vitorsouza/wp-content/uploads/java-br-curso-padroesdeprojeto-slides02.pdf), [estrutura](http://www.inf.ufes.br/~vitorsouza/wp-content/uploads/java-br-curso-padroesdeprojeto-slides03.pdf), [comportamento](http://www.inf.ufes.br/~vitorsouza/wp-content/uploads/java-br-curso-padroesdeprojeto-slides04.pdf)
- [Projeto de software orientado a objeto (Prof. Jacques Sauvé, UFCG)](http://www.dsc.ufcg.edu.br/~jacques/cursos/map/html/map2.htm): [observer](http://www.dsc.ufcg.edu.br/~jacques/cursos/map/html/arqu/observer.htm), [strategy](http://www.dsc.ufcg.edu.br/~jacques/cursos/map/html/pat/strategy.htm), [template method](http://www.dsc.ufcg.edu.br/~jacques/cursos/map/html/pat/template.htm), [factory method](http://www.dsc.ufcg.edu.br/~jacques/cursos/map/html/pat/factory.htm), [abstract factory](http://www.dsc.ufcg.edu.br/~jacques/cursos/map/html/pat/abstractfactory.htm), [composite](http://www.dsc.ufcg.edu.br/~jacques/cursos/map/html/pat/composite.htm), [decorator](http://www.dsc.ufcg.edu.br/~jacques/cursos/map/html/pat/decorator.htm) (há outros na seção 4)

## Padrões estudados na disciplina

- Observer
- Strategy
- Template Method
- Factory Method
- AbstractFactory
- Adapter
- Composite
- Decorator

## Atividade: Factory Method e Abstract Factory (vale nota)

**Equipe**: a mesma equipe dos outros trabalhos.

**Material**: [padroes-criacao.zip]({{site.baseurl}}/files/padroes-criacao.zip) (projeto Eclipse na linguagem Java)

Baixe o material, descompacte e abra no Eclipse. Trata-se de um sistema para gerar documentação em dois formatos: HTML e [Markdown](http://commonmark.org/help/). A geração da documentação é feita na classe `CriadorDocumentacao`, que cria um documento em três partes: `Cabecalho`, `Corpo` e `Rodape`.

**Discussão em aula**. Suponha que queremos adicionar um novo formato, LaTeX. Quais classes é preciso alterar? Se `CriadorDocumentacao` fosse parte de uma biblioteca (que você não pode alterar), como você adicionaria um novo formato?

**Atividade**. Crie uma cópia do projeto original, com nome `padroes-factory-method`, e aplique o padrão Factory Method para tornar `CriadorDocumentacao` independente do formato da documentação.

**Discussão em aula**. E agora, como você faria para adicionar um novo formato sem alterar a classe `CriadorDocumentacao`?

**Atividade**. Crie uma cópia do projeto original, com nome `padroes-abstract-factory`, e aplique o padrão Abstract Factory para tornar `CriadorDocumentacao` independente do formato da documentação.

**Discussão em aula**. Quais os prós e os contas de cada solução (Factory Method vs Abstract Factory)?

**Entrega**. Crie um arquivo `.zip` contendo as duas pastas dos projetos derivados (`padroes-factory-method` e `padroes-abstract-factory`) e envie para <rodrigo@dcc.ufba.br> até **domingo, 9 de outubro de 2016**.


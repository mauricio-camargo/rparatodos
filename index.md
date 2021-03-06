--- 
title: "R para todos"
author: "Maurício Garcia de Camargo (Professor da FURG)"
date: "2016-10-08"
site: bookdown::bookdown_site
output: bookdown::gitbook
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
github-repo: mauricio-camargo/rparatodos
description: "Este livro reune todo meu aprendizado no R."
---

# Prefácio {-}

O R assusta! 

Conheci o R em 2001 mas demorei uns três anos para tomar coragem e começar a aprender sozinho.  

Se o R assustou a mim, que adoro estatística, imagino o que fez a você!

Mas você verá que o susto passa rápido. Talvez  a única desvantagem do R seja justamente essa: a sua curva de aprendizado é relativamente inclinada! Mas conforme você vai aprendendo, vai também entendendo as vantagens do R, que são inúmeras, e quando o susto passar, vai sentir uma imensa alegria em poder fazer as suas coisas no R.

Você terá orgulho em saber o R!

Entre as tantas vantagens do R, destaco apenas duas:

> A pergunta certa sobre uma análise em R não é se é possível fazê-la, e sim como fazê-la. **Paulo Justiniano Ribeiro**

> O R permite fazer coisas absurdamente complexas de maneira absurdamente simples. **Tony Underwood**

Ou seja, ele faz tudo, e de maneira fácil. E, além de tudo, é *grátis*!

Muita gente já afirmou que o R não é para qualquer um, mas eu acredito firmemente que o R seja **Para todos**.

Pela minha experiência mais de 10 anos ensinando R para turmas de graduação e pós-graduação, qualquer um pode aprender o R. Em todas as turmas, 15 a 25% nunca irão aprender porque não querem; 50% farão um pequeno esforço e aprenderão as coisas básicas; 15 a 25% vão aprender além do básico, buscando recursos de aprendizado por conta própria, que existem aos montes na internet; 2 a 5% irão viciar no R, alguns de maneira não saudável.

> Usar o R é um pouco semelhante ao tabagismo. No começo é difícil, pode ter dores de cabeça e até mesmo sufocar nas primeiras vezes. Mas, a longo prazo, torna-se agradável e até mesmo viciante. No entanto, no fundo, para aqueles dispostos a serem honestos, há algo que não é totalmente saudável nele. *François Pinard*

Aprender o R e aprender estatística não são a mesma coisa, mas muita gente acha que aprendendo o R automaticamente aprenderão estatística!

Este livro não se propõe a ensinar estatítica. Para isso existem muitos outros bons livros por aí. Aqui você aprenderá a usar o R como ferramenta e fazer algumas coisas interessantes com ele. O objetivo deste livro é funcionar como um manual de consultas, ou de receitas, onde você poderá recorrer em caso de necessidade. 

Este livro está sendo escrito usando... o R! O pacote do R `bookdown` fornece ferramentas de edição de livros usando a linguagem `rmarkdown`, que é de fácil aprendizado.

Estas notas são fruto de mais de dez anos de experiência no ensino da estatística na graduação e na pós-graduação do Centro de Estudos do Mar da UFPR e no Instituto Oceanográfico da FURG, além de ensinar como convidado em outras instituições.

O R é uma ferramenta de ensino sem precedentes, com o potencial de facilitar incrivelmente a compreensão de análises estatísticas complexas pelos alunos. Muitos estatísticos, no mundo inteiro, muito antes disso, já tinham se dado conta do potencial do R (ou do seu inspirador, o software comercial S-Plus). 

Nenhuma experiência em estatística é requerida do leitor,  pois as noções básicas são fornecidas juntamente com o aprendizado das primeiras linhas na linguagem R.

A idéia do livro foi de servir como um manual de consulta e leitura casual, onde o interessado encontra no início de cada capítulo uma breve descrição das análises e de seus propósitos, sempre seguido de um exemplo prático de aplicação. Cada capítulo é complementado com pelo menos um exemplo de aplicação, sempre utilizando conjuntos de dados de fácil compreensão, tanto criados no próprio código exemplificado como pertencentes a conjuntos clássicos, embutidos no R.

**Agradecimentos**

Cada aluno meu merece um agradecimento único e especial. Foram vocês que me obrigaram a aprender estatística e me ensinaram a ensinar. Tenho certeza de que o aprendizado de R será muito útil para a maioria de vocês. Agradeço especialmente aos alunos do “clube” de estatística do CEM: Kassio Rios, Leonardo Sandrini, Eliandro Gilbert, Fernanda Souza, Maikon Di Domenico, Pablo Guilherme e Rodrigo Aluizio.

Nenhuma opinião pode, pela lógica, ser unânime, concluiu certa vez Nelson Rodrigues. Em estatística isso não é mau e por isso agradeço também a todos os professores que, pela interação através de aulas, publicações ou mesmo de conversas sobre estatística, me mostraram muitos caminhos sobre o delineamento amostral: Paulo Lana, Henry Spach, Paulo Pagliosa, André Garraffoni e Eunice Machado. 

Um especial agradecimento ao time de desenvolvedores do R, que disponibilizou um ambiente extremamente útil ao público em geral e, como não me canso de dizer, contribuiu em muito para o avanço da ciência em países subdesenvolvidos ou em desenvolvimento, pela transferência de uma tecnologia outrora restrita a uns poucos países felizardos. 

Por último, mas não em último, um carinhoso agradecimento aos meus três filhos e à Eunice, que suportam em casa um chato que só fala em estatística.

O livro está hospedado em https://github.com/mauricio-camargo/rparatodos e pode ser acessado livremente. Caso queira contribuir com o conteúdo do livro, use os recursos do `github`.


<br>
<br>

<center>

Maurício Garcia de Camargo

Rio Grande, 07 de outubro de 2016
</center>

# tppe_TP3
TP3

### UnB - Universidade de Brasilia 
### FGA - Faculdade do Gama
### TPPE - Técnicas de Programação para Plataformas Emergentes

## Componentes do grupo:
|Aluno  |  Matricula |
| --------- | ------------------------------------------------------ |
|Antonio Igor Carvalho | 180030264     | 
|Mateus Moreira Lima | 180024868      | 
| Victor Rayan Adriano Ferreira| 190044390 |
|Wesley Pedrosa dos Santos  | 180029240 |
----
# Entrega

* [Simplicidade](./caracteristicas/SIMPLICIDADE.md);
* [Elegância](./caracteristicas/Elegancia.md);
* [Extensibilidade](./caracteristicas/Extensibilidade.md);
* [Ausência de duplicidades](./caracteristicas/Ausencia_de_Duplicidades.md); 
* [Boa documentação](./caracteristicas/boa_documentacao.md). 

---
Qualidade do projeto de código -- um breve resumo: 

Projeto de software não é simplesmente uma especificação feita antes da
atividade de codificação e que posteriormente deve ser seguida à risca. A
construção do código é também vista como uma atividade de projeto. Não há uma
atividade de projeto, não há um time de projetistas: são os programadores quem
constantemente refinam e estendem o projeto ao refinar e estender o código. Caso
especial: TDD é uma técnica que realiza verificações de projetos antes mesmo do
código ter sido escrito. 

Elementos que são projetados por nós, em diferentes níveis: 
- Arquitetura de sistema: projetamos o sistema como um todo, identificamos os
  principais subsistemas e como é realizada a comunicação entre eles. Esse
projeto tem alto impacto em atributos de qualidade como desempenho e baixo
impacto em linhas de código. 

- Módulos e Componentes: cada subsistema é decomposto em módulos menores e mais
  compreensíveis e, a depender da linguagem/framework utilizado, são compostos
de pacotes (Java), namespace, bibliotecas reutilizáveis, hierarquias de classes,
etc... Para tais módulos geralmente são publicadas interfaces que posteriormente
são difíceis de serem alteradas (Refactoring de interfaces publicadas é sempre
mais complicado de se realizar comparado a interfaces públicas).

- Classes e tipos de dados: cada módulo, por sua vez, é decomposto em classes e
  tipos de dados. Nesse estágio o projeto tende a ser mais informal e mais fácil
de ser alterado (principalmente por meio de refatorações, em que o comportamento
externamente observável do código é preservado - ou pelo menos deveria ser).
Nesse nível realiza-se micro-projetos em tempo de programação. 

- Funções: menor nível de projeto, mas ainda assim é realizada atividade de
  projeto. Funções devem ser cuidadosamente projetadas pois terão impacto no
sistema. Uma vez criadas, deve-se definir como tais funções funcionam
internamente.


O desafio é criar um bom projeto que seja mais fácil de ser modificado, de ser
entendido, de ser consertado, mais resiliente a mudanças (acomoda futuras
extensões e modificações) e menos suscetíveis a erros. 

Não há projeto errado e projeto certo, há mau e bom projeto. Bons projetos
possuem as seguintes características: 
* [Simplicidade](./caracteristicas/SIMPLICIDADE.md);
* [Elegância](./caracteristicas/Elegancia.md);
* Modularidade (baixo acoplamento e alta coesão);
* Boas interfaces; 
* [Extensibilidade](./caracteristicas/Extensibilidade.md);
* [Ausência de duplicidades](./caracteristicas/Ausencia_de_Duplicidades.md); 
* Portabilidade;
* "Idiomático" (idioma da linguagem) e,
* [Boa documentação](./caracteristicas/boa_documentacao.md). 

Fonte: _Code Craft : The Practice of Writing Excellent Code_, No Starch Press,
Incorporated, 2006. _ProQuest Ebook Central_,
https://ebookcentral.proquest.com/lib/univbrasilia-ebooks/detail.action?docID=273481.

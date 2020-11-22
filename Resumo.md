# Resumo de Padrões de Desenvolvimento 

Design Patterns ou padrões de projetos são soluções generalistas para problemas recorrentes durante o desenvolvimento de um software. Não se trata de um framework ou um código pronto, mas de uma definição de alto nível de como um problema comum pode ser solucionado.

Origem
Em 1978 os arquitetos Christopher Alexander, Sara Ishikawa e Murray Silverstein escreveram um livro chamado “A Pattern Language: Towns, Buildings, Construction” que foi publicado em português com o nome “Uma Linguagem de Padrões”. Neste livro os autores catalogaram 253 tipos de problemas (ou desafios de projeto) e analisaram o que está por trás de cada situação, descrevendo-as na sua essência e propondo uma solução padrão.

Em 1987 durante a segunda edição da OOPSLA (Object-Oriented Programming, Systems, Languages, and Applications) o engenheiro de software Kent Back, que posteriormente foi um dos criadores das metodologias Extreme Programming e Test Driven Development (TDD), junto com Ward Cunningham apresentaram uma palestra intitulada “Using Pattern Languages for Object-Oriented Programs” (Utilizando a linguagem dos padrões para programação orientada a objetos, em tradução livre). Nesta palestra eles propuseram cinco padrões de projetos no campo da ciência da computação.

Mas esses conceitos ficaram realmente conhecidos em 1994, quando os engenheiros de software Erich Gamma, Richard Helm, Ralph Johnson e John Vlissides escreveram o livro “Design Patterns: Elements of Reusable Object-Oriented Software” com o objetivo de catalogar problemas comuns aos projetos de desenvolvimento de software e as formas de resolver esses problemas. Os autores catalogaram 23 padrões que utilizaram ao longo de suas carreiras. Este livro teve mais 500.000 exemplares vendidos e foi publicado em 13 idiomas. No Brasil foi publicado com o nome “Padrões de Projeto – Soluções Reutilizáveis de Software Orientado a Objetos”. Os autores do livro ficaram conhecidos como Gang of Four (Gangue dos quatro) ou “GoF”. Depois disso muitos outros livros surgiram, alguns criticando alguns desses padrões, e outros divulgando novos padrões.

Desde então, Design Patterns tem sido um tema bastante estudado por programadores e arquitetos de software pelo mundo todo.

# Design Patterns mais conhecidos
Os padrões do GoF são os mais conhecidos, porém existe uma série de outros padrões catalogados. Neste artigo procurei citar os padrões de projeto mais conhecidos e que são considerados como boas práticas pelo mercado.

Por vezes alguns padrões deixam de ser utilizados devido a evolução das linguagens de programação e a utilização de novos padrões que melhor atendem alguns cenários. Um exemplo disso é o padrão Service Locator, que acabou caindo em desuso devido aos padrões Dependency Injection e Inversion of Control, que juntos conseguem desacoplar as dependências de uma forma mais organizada que o Service Locator.


# Design Patterns GoF
Os autores do livro “Design Patterns: Elements of Reusable Object-Oriented Software” agruparam os Design Patterns em três tipos diferentes: Creational (Criação), Structural (Estrutura), Behavioral (Comportamental).

## Creational Design Patterns

Abstract Factory
Builder
Factory Method
Prototype
Singleton

## Structural Design Patterns

Adapter
Bridge
Composite
Decorator
Façade
Flyweight
Proxy

## Behavioral Patterns

Chain of Responsibility
Command
Interpreter
Iterator
Mediator
Memento
Observer
State
Strategy
Template Method
Visitor

## Padrões arquiteturais
Interceptor
Model View Controler (MVC)
Model View ViewModel (MVVM)
Model View Presenter (MVP)
n-tier
Specification
Publish–subscribe
Inversion of control

## Outros Design Patterns
Rules Design Patterns
Dependency Injection
Intercepting filter
Lazy loading
Mock object
Method chaining
Inversion of control
Unit of Work
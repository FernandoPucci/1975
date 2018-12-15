# SOLID
Also in [Android Pub - SOLID Principles](https://android.jlelse.eu/solid-principles-the-definitive-guide-75e30a284dea)

## S - Single Responsibility Principle
>- Princípio da responsabilidade única = Cada 'coisa' faz só uma coisa. Ex. Uma classe representa somente aquela classe.

 

## O - Open Closed Principle
>- Princípio do 'Aberto/Fechado' 
 Aberto para extensões e fechados para modificações.

 No Curso, é apresentado o conceito do único ponto de entrada, por exemplo, um construtor com parâmetros, o qual é a única maneira de se instanciar determinada classe e passar valor para os atributos, garantindo que dentro do mesmo, possam ser realizadas diversas validações de nossa entidade de dompinio rico.

 Para trabalhar com listas, mantendo o Open Closed Principle, recomenda-se usar `IReadOnlyCollection<T>` ao invés de `List<T>`, o que força o programador a usar o método criado para adição à lista (com validações inclusive), ao invés de simplesmente adicionar um objeto à lista.   

## L - Liskov Substitution Principle
>- Princípio da substituição de Liskov

## I - Interface Segregation Principle
>- Princípio da Segregação

## D - Dependency Inversion Principle
>- Princípio da Inversão de Dependência


# S.O.L.I.D

## S ? Single Responsiblity Principle (Princípio da responsabilidade única)
Uma classe deve ter um, e somente um, motivo para mudar. <br />
Esse princípio declara que uma classe deve ser especializada em um único assunto e possuir apenas uma responsabilidade dentro do software, ou seja, a classe deve ter uma única tarefa ou ação para executar.

## O ? Open-Closed Principle (Princípio Aberto-Fechado)
Objetos ou entidades devem estar abertos para extensão, mas fechados para modificação, ou seja, quando novos comportamentos e recursos precisam ser adicionados no software, devemos estender e não alterar o código fonte original.

## L ? Liskov Substitution Principle (Princípio da substituição de Liskov)
Uma classe derivada deve ser substituível por sua classe base.

## I ? Interface Segregation Principle (Princípio da Segregação da Interface)
Esse princípio basicamente diz que é melhor criar interfaces mais específicas ao invés de termos uma única interface genérica.<br/>
Uma classe não pode ser forçada a depender de métodos que não utilizará - Robert C. Martin

## D ? Dependency Inversion Principle (Princípio da inversão da dependência)
De acordo com Uncle Bob, esse princípio pode ser definido da seguinte forma:

1. Módulos de alto nível não devem depender de módulos de baixo nível. Ambos devem depender da abstração.

2. Abstrações não devem depender de detalhes. Detalhes devem depender de abstrações.

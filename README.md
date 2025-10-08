# FuncoesJS

Atividade do tutorial sobre: declaration function, Arrow Function e Expression Function.

JavaScript possui três tipos de funções diferentes, sendo elas: **Declaration Function**, **Expression Function** e **Arrow Function**. Vou  trazer as definições delas e suas utilidades. 

**DECLARATION FUNCTION**: Uma declaration function em JavaScript é uma maneira de definir uma função. Para definir uma função, você precisa fornecer seu nome, quaisquer parâmetros (se aplicável) e o código que define o que a função faz. As declarações de função têm uma sintaxe específica e são movidas para o topo de seu escopo durante a fase de criação. 
function somar(a,b){
return a+b
}
somar(3,4); saída:7


**EXPRESSION FUNCTION**:Uma expression function é uma maneira de definir uma função como parte de uma expressão, tornando-a versátil para atribuição a variáveis, passagem como argumentos ou invocação imediata. Expression functions podem ser nomeadas ou anônimas. Eles não são içados , ou seja, são acessíveis somente após sua definição. Frequentemente usado em retornos de chamada , fechamentos e criação de funções dinâmicas. Habilitam o encapsulamento de funcionalidades dentro de um escopo limitado.
var x = function (y) {
  return y * y;
}
x(4); saída: 16

**ARROW FUNCTION**: Elas são basicamente uma nova forma de criar funções com JavaScript, com uma estrutura mais curta, mas bem poderosa ao mesmo tempo.
Sintaxe básica: Uma função convencional pode ser criada com este código: function() {#comandos}. Já a sintaxe básica de uma arrow function é a seguinte: () => {#comandos}.
É possível observar que não foi necessário escrever a palavra “function”. Além disso, usamos o sinal “=>” para criá-la, o que lembra uma flecha, fazendo jus ao nome “Arrow Functions”.
Quando vemos essa estrutura, notamos que é uma forma mais elegante e “bonita” de criar funções. abaixo, um código simples utilizando a arrow funcion:
const sayHello = name => `Seja bem-vindo ${name}!!!`. 
sayHello("Gustavo"); saída: Seja bem-vindo Gustavo!!!


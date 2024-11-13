RESOLUÇÃO EXERCÍCIO 02

Aluno: Márcio Fabrício Leitão Oliveira de Sousa

Turma: POO – 2024.2

1. Qual a diferença entre tipagem dinâmica e tipagem estática?

R= Linguagens com tipagem estática não permitem ao desenvolvedor alterar o tipo da variável depois de declarada. Geralmente a verificação de tipo é feita em tempo de compilação. Enquanto a tipagem dinâmica está ligado a habilidade da linguagem de programação permitir que a mesma variável possa receber valores de tipos diferentes ao longo da execução do código.


2. Qual o principal problema do uso de tipagem dinâmica?

R= O principal problema são os possíveis erros em tempo de execução, causados por mudanças inesperadas de tipo ao longo do código. Como o tipo de uma variável pode mudar de maneira imprevisível durante a execução, isso pode levar a situações onde uma variável é usada de forma incorreta, resultando em erros difíceis de detectar e debugar.


3. Pesquise um exemplo na internet em que a tipagem dinâmica pode ser problemático.

R= Ao apresentar mudanças no tipo de variável, como pode acontecer com a linguagem python, por exemplo, em uma função para somar dois números:
``` python
def somar(a, b):
     return a + b
```

Considerando a e b do tipo int, onde a = 10 e b =5, ele retornaria como resultado o valor 15. Entretanto, atribuindo a a e b valores do tipo string, onde a = “10” e b = “5”, o resultado seria 105.


4. Pesquise e exemplifique com um exemplo porque dizemos que a linguagem C, mesmo tendo tipagem estática, possui tipagem fraca.

R= é considerada de tipagem fraca porque permite operações entre tipos de dados diferentes e conversões explícitas e implícitas entre eles sem restrições rigorosas. Um exemplo que demonstra a tipagem fraca é a possibilidade de somar um número inteiro com um caractere ou converter um ponteiro para um tipo de dado incompatível, erro que é permitido pelo compilador.

5. Poderíamos dizer que a tipagem do TypeScript é fraca por uma variável do tipo number aceitar tanto inteiros como ponto flutuante?

R= Não, o fato do Typescript aceitar inteiros e flutuantes no tipo number tem a ver com uma característica de design da linguagem e não compromete a segurança e nem a força da tipagem. Outrossim, a  tipagem fraca refere-se à flexibilidade da linguagem em realizar ou permitir a conversão entre tipos diferentes e não ao fato de um tipo específico de receber mais de uma variação de representação.

6. Reescreva o exemplo abaixo, mantendo a quebra de linhas usando template strings e os valores Ely, 120.56 e TypeScript venham de variáveis declaradas separadamente e “interpoladas” na string: 

Ely 

My payment time is 120.56 

and 

my preffered language is TypeScript

``` typescript
let nome = "Ely";
let pagamento = 120.56;
let linguagem = "Typescript";

const mensagem =`
${nome}
My payment time is ${pagamento} 
and 
my preffered language is ${linguagem}
`;

console.log(mensagem);
```

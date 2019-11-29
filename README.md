# 1286_URI-Motoboy

**Número da Lista**: 5<br>
**Conteúdo da Disciplina**: Programação Dinâmica<br>
**Linguagem**: C++<br>

## Alunos
|Matrícula | Aluno |
| -- | -- |
| 17/0062465  |  Paulo Vitor Coelho da Rocha |
| 15/0023375  |  Vitor Cardoso Xoteslem |

## Sobre 
Nosso projeto se resume a resolver e explicar o funcionamento da questão 1286 da plataforma URI

## Texto da questão
José é um motoboy e trabalha fazendo entregas para uma pizzaria. Seu salário é baseado no número de pizzas entregues. Só que esta pizzaria está com muito movimento e ele pediu auxílio a seu amigo Roberto para que o ajudasse nas entregas. Como Roberto é camarada e está sem trabalho no momento, ele concordou em pegar aqueles pedidos cujas entregas serão mais demoradas.

Assim, sempre que chegam à pizzaria, antes de partirem para novas entregas José determina a quantidade de pizzas que Roberto deverá entregar e seleciona para ele os pedidos mais demorados. Por exemplo, se há 22 pizzas para serem entregues e José determinar que Roberto entregue no máximo 10 destas pizzas (pode ser menos), estas devem estar obrigatoriamente entre os pedidos que levarão mais tempo para serem entregues. Isso é ilustrado no primeiro caso de teste, onde Roberto deverá fazer a entrega do segundo, terceiro e sexto pedido, somando 8 pizzas e 62 minutos (23 + 21 + 18). Se Roberto fosse realmente entregar 10 pizzas, ele teria que atender o segundo, terceiro e quarto pedido e isto levaria 59 minutos (23 + 21 + 16), o que não é o objetivo de José, pois levaria menos tempo do que a primeira opção, ou seja, a relação pizzas/tempo não importa muito para José (isso pode ser observado no segundo caso de teste do exemplo abaixo).

Para poder fazer a divisão do trabalho, José pediu a um amigo acadêmico em Ciência da Computação que desenvolvesse um programa que determinasse quanto tempo seu amigo Roberto irá levar para entregar estes pedidos mais demorados.

Entrada
A entrada contém vários casos de teste. Cada caso de teste contém na primeira linha um valor inteiro N (1 ≤ N ≤ 20) que indica o número de pedidos. A linha seguinte contém um valor inteiro P (1 ≤ P ≤ 30) indicando o número máximo de pizzas que podem ser entregues por Roberto. Cada uma das próximas N linhas contém um pedido com o tempo total para ser entregue e a quantidade de pizzas do pedido, respectivamente. A final da entrada é determinado por N = 0, e não deverá ser processado.

Saída
Para cada caso de teste de entrada deve ser impresso um valor inteiro que determina o tempo que Roberto irá levar para entregar as suas pizzas seguido de um espaço em branco e do texto “min.”.<br>
<p>Exemplo de entrada&emsp;&emsp;&emsp;Exemplo de saída<br>
6&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;62 min.<br>
10<br>
15 5<br>
23 4<br>
21 2<br>
16 4<br>
19 5<br>
18 2<br></p>

## Screenshots
![AC](./IMG/AC.png)

## Instalação 
Para rodar a questão 1286 Accepted

```
    g++ Motoboy.cpp
    ./a.out
```

## Tabela com preenchimento recursivo do caso de teste

![knapsack](knapsack.jpg)

#Diário de Campo — ALEST I

Tema: Algoritmo de ordenação - Bubble Sort
Aplicação: Ordenação de cartas de um baralho
Integrantes: Tayara e Vicente

 31/08 — Início e definição do trabalho

Conversamos sobre a proposta da atividade e sobre qual seria a melhor maneira de representar o funcionamento de um algoritmo de ordenação sem muitos conhecimentos prévios. 
Decidimos utilizar o Bubble Sort e relacioná-lo a um jogo de cartas, consideramos que esse exemplo tornaria mais simples visualizar as comparações e trocas realizadas pelo algoritmo.
A ideia definida foi criar cartas contendo valor e naipe e utilizar o Bubble Sort para organizar uma mão de cartas de acordo com seus valores.

01/09 a 04/09 — Planejamento e primeiros ajustes

Durante alguns dias do feriado, alinhamos e conrrigimos a estrutura do trabalho e sobre como a ideia do baralho poderia ser implementada em Java.
Definimos que cada carta deveria possuir pelo menos duas informações:

 valor;
 naipe;

Também discutimos que a ordenação seria realizada considerando o valor numérico das cartas, enquanto o naipe permaneceria como uma característica da própria carta.
Começamos a organizar a estrutura necessária para implementar e testar o algoritmo.

07/09 — acompanhamento

Devido ao feriado, naõ0 desenvolvemos o trabalho nesse dia em especifico.

 08/09 — Ajustes

Revisamos o projeto, Vicente alinhou algumas dúvidas comigo.
Revisamos principalmente o funcionamento do Bubble Sort:

1. O algoritmo compara duas cartas vizinhas;
2. Caso a primeira possua valor maior que a segunda, suas posições são trocadas;
3. O processo continua ao longo do vetor;
4. Ao final de cada passagem, os maiores valores vão sendo posicionados no final;
5. O processo é repetido até que toda a mão esteja ordenada.

Também revisamos os conceitos de melhor caso e pior caso.
No melhor caso, as cartas já estão ordenadas. Como a implementação verifica se ocorreu alguma troca, o algoritmo pode encerrar antes.
No pior caso, as cartas estão em ordem inversa e é necessário realizar um número maior de comparações e trocas.

 09/09 - Conclusão

O desenvolvimento do trabalho permitiu visualizar de maneira prática o funcionamento do Bubble Sort;
A escolha do jogo de cartas foi a escolha mais "simples", mas tornou o processo de ordenação e do nosso entendimento sobre o algoritmo mais intuitivo,
Como estamos ambos receosos e com certa dificuldade na disciplina e somos apenas dupla, algo mais simples nos levou a tentar trabalhar em uma ideia sem necessitar inteiramente de IA. 

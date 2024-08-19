### #7DaysOfCode-Alura-ONE


## #7DaysOfCode - Dia 1: Comparando tipos de variáveis em Javascript

**O problema:** Em Javascript, a comparação de valores entre variáveis de tipos diferentes pode levar a resultados inesperados devido à conversão de tipos implícita.

**O desafio:** Reescrever o código fornecido para que as comparações sejam precisas e exibam mensagens corretas, considerando o tipo de cada variável.

**Exemplo:** 

```javascript
console.log( false == '0' ); // Retorna true
```

**Objetivo:** Utilizar o operador de igualdade estrita (`===`) para evitar conversões de tipos implícitas e obter comparações mais precisas.

**Resumo do texto:**

O primeiro dia do #7DaysOfCode aborda a importância de entender como o Javascript compara variáveis de diferentes tipos. O desafio consiste em reescrever um código que contém comparações imprecisas, utilizando o operador de igualdade estrita para garantir resultados precisos. 

### O primeiro codigo resolvido no Link Abaixo:

Primeiro desafio concluído: [Click Aqui](https://github.com/LucasASouzak/7DaysOfCode-Alura-ONE/blob/c1b3596490b0fd4f435332ab21768aaa36511b7f/7DiasDesafioUM.html). #7DaysOfCode-Alura-ONE

## #7DaysOfCode - Dia 2: Sistema de Boas-vindas Personalizado

O desafio de hoje consiste em criar um programa que simule um site de cadastro. O programa deve pedir ao usuário três informações: nome, idade e linguagem de programação que está aprendendo. Em seguida, o programa deve exibir uma mensagem de boas-vindas personalizada usando as informações fornecidas pelo usuário. 

**Exemplo de Código (JavaScript):**

```Javascript
const nome = prompt("Qual o seu nome?");
const idade = prompt("Quantos anos você tem?");
const linguagem = prompt("Qual linguagem de programação você está estudando?");

alert(`Olá ${nome}, você tem ${idade} anos e já está aprendendo ${linguagem}!`);
```

**Exercício Opcional:** O programa também pode perguntar ao usuário se ele gosta da linguagem de programação que está aprendendo e exibir uma mensagem de incentivo ou pena, dependendo da resposta. 

**Lembre-se:** Você pode adaptar o código para usar outras linguagens de programação, como Python ou C++, e também pode usar diferentes métodos de entrada e saída de dados, como console.log, alert, prompt, ou até mesmo interfaces gráficas com HTML e CSS. 

### O segundo codigo resolvido no Link Abaixo:
Segundo desafio concluído: [Click Aqui](https://github.com/LucasASouzak/7DaysOfCode-Alura-ONE/blob/main/7DiasDesafioDOIS.html). #7DaysOfCode-Alura-ONE


## #7DaysOfCode - Dia 3: Sistema de Boas-vindas Personalizado

O desafio proposto consiste em criar um jogo interativo em JavaScript, simulando um caminho de aprendizado em programação. O jogador deve tomar diversas decisões que influenciarão o desenrolar da história, como escolher entre Front-end e Back-end, e quais tecnologias aprender.

Conceitos-chave:

Estruturas de controle: if, else, for, while.
Entrada e saída de dados: prompt e alert.
Lógica de programação: Criar fluxos de decisão e repetições.

```JavaScript
if (cidade === "Roma"){
    // mostre a foto do “Coliseu”
}
else if (cidade === “Paris”){
    // mostre a foto do “Torre Eiffel”
}
else {
    // dê a resposta “Você não digitou nenhuma cidade válida”   

}
```

### O Terceiro codigo resolvido no Link Abaixo:
Segundo desafio concluído: [Click Aqui](https://github.com/LucasASouzak/7DaysOfCode-Alura-ONE/blob/main/7DiasDesaioTRES.html). #7DaysOfCode-Alura-ONE

## #7DaysOfCode - Dia 4: Jogo simples de adivinhação.

Objetivo: Criar um jogo simples onde o jogador tenta adivinhar um número escolhido aleatoriamente pelo computador.

Regras:

O computador escolhe um número entre 0 e 10.
O jogador tem 3 tentativas para acertar o número.
A cada tentativa, o jogador informa seu palpite.
Se o jogador acertar, o jogo termina e ele é parabenizado.
Se o jogador errar, ele tem mais duas tentativas.
Se o jogador não acertar em nenhuma das 3 tentativas, o número correto é revelado.
Dicas:

Utilize uma estrutura de repetição (como while ou for) para controlar as 3 tentativas.
Para gerar um número aleatório, use 
```JavaScript
Math.random() e a fórmula: Math.floor(Math.random() * (máximo - mínimo + 1) + mínimo).
```

### O Quarto codigo resolvido no Link Abaixo:

Segundo desafio concluído: [Click Aqui](https://github.com/LucasASouzak/7DaysOfCode-Alura-ONE/blob/main/7DiasDesafioQUATRO.html). #7DaysOfCode-Alura-ONE

## #7DaysOfCode - Dia 5: Jogo simples de adivinhação.

Objetivo: Criar um programa em JavaScript que simule uma lista de compras, organizando itens por categorias.

Funcionalidades:

Perguntar ao usuário:
Se deseja adicionar um item à lista.
O nome do item.
A categoria do item (frutas, laticínios, congelados, doces, etc.).
Armazenar os itens: Utilizar um array para armazenar os itens e suas respectivas categorias.
Agrupar os itens: Organizar os itens em categorias e exibir o resultado formatado.
Exemplo de saída:

```Javascript
Lista de compras:
    Frutas: banana, tomate, maçã, uva, abacate
    Laticínios: leite vegetal, leite de vaca, leite em pó
    Congelados:
    Doces: chiclete e bala de ursinho
```

Dicas:

Utilizar arrays: O objeto Array é ideal para armazenar listas de elementos.
Método push(): Adiciona um novo elemento ao final de um array.
Formatar a saída: Utilizar console.log para exibir o resultado de forma clara e organizada.
Exemplo de código para criar um array vazio e adicionar um elemento:

```JavaScript
let meuArray = []; // Cria um array vazio
meuArray.push("elemento1"); // Adiciona "elemento1" ao array
```

### O Quinto codigo resolvido no Link Abaixo:

Quinto desafio concluído: [Click Aqui](https://github.com/LucasASouzak/7DaysOfCode-Alura-ONE/blob/main/7DiasDesafioCinco.html). 

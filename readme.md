<div>
<img src="https://github.com/emersonfsti/DIO-Desafios-cod-bas-log/blob/main/img/logoLogicaDIO.png?raw=true" alt="Logo Logica de Programação DIO" style="float:left; margin-right:10px;" width="150" height="125"/>
<h1>Formação Lógica de Programação</h1>
</div>
<hr>
<br>

## Emerson Felix de Souza

> No projeto "Classificador de Nível de Herói", criado por mim, Emerson Felix, em 12/07/2024, desenvolvi um script em JavaScript que classifica heróis com base na quantidade de experiência (XP) acumulada. Utilizei um laço de repetição for para incrementar a XP do herói em 500 a cada iteração, até completar 21 iterações. Com uma estrutura de decisão switch case, determinei e exibi a classificação do herói em categorias como Ferro, Bronze, Prata, Ouro, Platina, Ascendente, Imortal e Radiante, conforme a XP acumulada em cada etapa.

# Desafio de Código:

## 1 Jornada do Herói

### Descrição

> Você é um jovem herói que embarca em uma jornada épica para derrotar o temido dragão que aterroriza o reino. No entanto, você precisa atravessar uma floresta perigosa para chegar à caverna do dragão. Cada passo é crucial, e sua jornada será determinada pela lógica afiada que você possuir.

_Tarefa: Escreva um algoritmo que simule a jornada do herói pela floresta. O herói começa em uma posição inicial e deve dar uma série de passos para atravessar a floresta até a caverna do dragão._

### Entrada

A posição inicial do herói na floresta (um número inteiro).
O número total de passos que o herói deve dar (um número inteiro).

### Saída

Imprima a posição final do herói após dar a quantidade de passos especificada.

### Exemplos

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada | Saida                      |
| ------- | -------------------------- |
| 2 e 3   | Posicao final do heroi: 5  |
| 15 e 3  | Posicao final do heroi: 18 |
| 6 e 10  | Posicao final do heroi: 16 |

<hr>

## 2 Pontos de Experiência

### Descrição

> Você é um herói em um mundo mágico repleto de monstros e desafios. Sua missão agora é enfrentar inimigos e ganhar pontos de experiência (XP) para se tornar mais forte. A cada vitória, você ganha XP e se aproxima de se tornar um lendário campeão.

_Tarefa: Escreva um programa simples que simule o ganho de XP após derrotar um monstro. O programa deve calcular e exibir a quantidade de XP ganhos com base no nível do monstro e na dificuldade da batalha._

_Calculo do XP: Para calcular a quantidade de XP ganhos, o programa precisa considerar o nível do monstro e a dificuldade da batalha. A fórmula num1 * num2 * 100 é usada para calcular essa quantidade com base nos valores fornecidos._

#### Explicação:

_num1: Este é o nível do monstro. Quanto maior o nível do monstro, mais XP você ganhará ao derrotá-lo. Portanto, multiplicar o nível do monstro por um valor maior ajudará a refletir o aumento da recompensa de XP para monstros mais poderosos._

_num2: Este é o valor da dificuldade da batalha, variando de 1 a 100. Quanto maior a dificuldade da batalha, mais XP você deve ganhar para enfrentar um desafio maior. Multiplicar pela dificuldade ajuda a ajustar a recompensa de XP com base na intensidade da batalha._

_100: Este é o multiplicador constante que determina a escala geral de recompensa de XP. Multiplicar pelo nível do monstro e pela dificuldade aumenta a recompensa em 100 vezes o valor do nível e da dificuldade._

### Entrada

O nível do monstro (um número inteiro).
A dificuldade da batalha, representada por um valor de 1 a 100 (um número inteiro).

### Saída

Imprima a quantidade de XP ganhos após a batalha.

### Exemplos

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada | Saida                  |
| ------- | ---------------------- |
| 45 e 40 | Voce ganhou 180000 XP! |
| 41 e 38 | Voce ganhou 155800 XP! |
| 15 e 20 | Voce ganhou 30000 XP!  |

## 3 Capturando Pokémons Iniciais

### Descrição

> No mundo dos jogos Pokémon, os treinadores começam sua jornada escolhendo um dos três Pokémons iniciais: Bulbasaur, Charmander e Mewtwo. Cada treinador escolhe um dos quatro pokemons. Seu desafio é criar uma solução que permita ao jogador escolher um dos Pokémons iniciais e exibir uma mensagem de boas-vindas e o Pokémon escolhido.

### Entrada

Você receberá um número inteiro que representa a escolha do treinador: 1 para Bulbasaur, 2 para Charmander, 4 Pikachu e 5 para Mewtwo.

### Saída

A saída deve ser uma mensagem de boas-vindas que inclua o nome do Pokémon escolhido.

### Exemplos

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada                  | Saída                                                |
| ------------------------ | ---------------------------------------------------- |
| Escolha o seu Pokemon: 1 | Voce escolheu o Bulbasaur como seu Pokemon inicial.  |
| Escolha o seu Pokemon: 2 | Voce escolheu o Charmander como seu Pokemon inicial. |
| Escolha o seu Pokemon: 4 | Voce escolheu o Pikachu como seu Pokemon inicial.    |
| Escolha o seu Pokemon: 5 | Voce escolheu o Mewtwocomo seu Pokemon inicial.      |


<hr>


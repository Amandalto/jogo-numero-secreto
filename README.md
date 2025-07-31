# Jogo do Número Secreto

Um simples jogo de adivinhação onde o jogador precisa descobrir um número secreto entre 1 e 100.

## Funcionalidades

- Geração aleatória de um número secreto
- Dicas indicando se o número secreto é maior ou menor que o palpite
- Contagem de tentativas
- Reinício do jogo após vitória
- Sintetização de voz para feedback (utilizando ResponsiveVoice)
- Prevenção de números repetidos até que todos sejam sorteados

## Tecnologias Utilizadas

- JavaScript
- HTML 
- CSS 
- Biblioteca ResponsiveVoice para síntese de voz

## Como Jogar

1. Faça um palpite digitando um número entre 1 e 100
2. Receba dicas se o número secreto é maior ou menor
3. Continue tentando até acertar
4. Clique em "Novo jogo" para reiniciar

## Estrutura do Código

- `listaDeNumerosSorteados`: Armazena números já sorteados
- `numeroLimite`: Define o intervalo máximo (100)
- `numeroSecreto`: Número a ser adivinhado
- `tentativas`: Contador de tentativas

### Funções Principais

- `exibirTextoNaTela()`: Exibe textos na tela e usa síntese de voz
- `verificarChute()`: Valida o palpite do jogador
- `gerarNumeroAleatorio()`: Gera números únicos
- `limparCampo()`: Limpa o campo de input
- `reiniciarJogo()`: Prepara um novo jogo

## Requisitos

- Navegador moderno com suporte a JavaScript
- Conexão com a internet para usar a API ResponsiveVoice

## Observações

O jogo evita repetição de números até que todos os números possíveis (1-100) tenham sido sorteados, garantindo uma experiência mais justa.

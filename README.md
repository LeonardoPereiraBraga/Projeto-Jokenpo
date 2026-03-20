# 🎮 Jokenpô MD3

**Aluno:** Leonardo Pereira Braga

## 📱 Descrição do Projeto

O aplicativo **Jokenpô MD3** é um jogo mobile desenvolvido em Android que simula o clássico jogo de pedra, papel e tesoura entre o usuário e o computador.

O jogador pode escolher entre três opções:

* Pedra
* Papel
* Tesoura

A cada rodada, o aplicativo gera uma escolha aleatória para o computador e exibe o resultado na tela, atualizando automaticamente o placar.

## ⚙️ Funcionamento

* O usuário seleciona uma das opções disponíveis tocando nas imagens.
* O computador escolhe uma opção aleatória.
* O sistema compara as escolhas e determina o vencedor da rodada.
* O placar é atualizado em tempo real.
* O jogo segue o formato **MD3 (Melhor de 3)**:

  * O primeiro a alcançar **2 vitórias** vence a partida.
* Ao final, uma mensagem indica o vencedor.
* O botão **"Reiniciar MD3"** permite reiniciar o jogo a qualquer momento.

## 🧠 Lógica do Jogo

A lógica foi implementada utilizando:

* Estruturas condicionais (`if/else`)
* Geração de números aleatórios (`Random`)
* Controle de estado da partida (jogo finalizado ou não)

## 🔄 Reinício

Ao clicar no botão de reinício:

* O placar é zerado
* A imagem volta ao estado inicial
* O jogo é liberado para uma nova partida

## 📌 Tecnologias Utilizadas

* Java
* Android Studio
* XML (Layout)

---

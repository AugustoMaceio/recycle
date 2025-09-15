# Classificador de Lixo Reciclável (Desafio 01 - Teachable MAchine)
##Deep Learning UFPE-Cin

Este projeto é um exercício prático da disciplina **Deep Learning (2025.2)** da Pós-graduação em Ciência da Computação do CIn-UFPE. O objetivo é classificar tipos de lixo reciclável (metal, papel, plástico, vidro, lixo comum) utilizando um modelo treinado no [Teachable Machine](https://teachablemachine.withgoogle.com/) e executado no navegador com TensorFlow.js.

## Como funciona

- O usuário acessa a aplicação web, ativa a webcam e posiciona o objeto a ser classificado.
- O modelo identifica o tipo de lixo e exibe o rótulo e a imagem da lixeira correspondente.
- O sistema foi projetado para funcionar em dispositivos móveis e desktops.

## Estrutura

- `index.html`: Interface principal da aplicação.
- `img/`: Pasta com imagens das lixeiras para cada tipo de lixo.
- `model/`: Pasta com o modelo treinado exportado do Teachable Machine.

## Como rodar localmente

1. Clone este repositório.
2. Instale a extensão **Live Server** no VS Code.
3. Abra o projeto no VS Code e inicie o Live Server.
4. Acesse pelo navegador em `http://localhost:5500/index.html` ou, para acessar via celular na mesma rede, use o IP local do seu computador (ex: `http://192.168.1.100:5500/index.html`).

## Créditos
 - Augusto César M. de Oliveira
- Exercício da disciplina Deep Learning (2025.2) - Pós-graduação em Ciência da Computação

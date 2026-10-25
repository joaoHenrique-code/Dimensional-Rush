# Dimensional Rush — Protótipo 0.1

Jogo de plataforma e velocidade 2D, feito com JavaScript e Phaser 3.90.0.

## O que já existe

- Personagem **provisório** vermelho e preto (a arte original entra depois)
- Movimento lateral, pulo e dash
- Comandos na tela para jogar no celular, em modo paisagem
- Pequena fase com plataformas, três abismos, energias colecionáveis e portal de saída
- Reinício pelo botão da tela quando a fase terminar
- Teclado: A/D ou setas = andar; espaço/W/seta para cima = pular; Shift/X/Z = dash

## Como abrir no celular

O método mais fácil e estável é publicar o arquivo `index.html` com GitHub Pages. É preciso ter internet para carregar a biblioteca Phaser pela primeira vez e em cada recarga (o arquivo usa CDN).

1. No GitHub, crie um **repositório público** chamado `dimensional-rush`.
2. Toque em **Add file → Upload files** e envie o `index.html` (no navegador do celular, ative **Versão para computador** se o botão não aparecer).
3. Clique em **Commit changes**.
4. Abra **Settings → Pages**.
5. Em **Build and deployment**, escolha **Deploy from a branch**.
6. Escolha branch **main**, pasta **/(root)** e toque em **Save**.
7. Quando o GitHub terminar a publicação, visite `https://SEU-USUARIO.github.io/dimensional-rush/` e gire o celular para a horizontal.

Também é possível abrir `index.html` localmente em um navegador que permita arquivos locais, mas esse comportamento varia entre aplicativos Android. GitHub Pages tende a ser mais confiável.

## Próximos passos

1. Testar movimentação, salto e dash no celular.
2. Ajustar a velocidade e o tamanho da fase conforme seu feedback.
3. Substituir o personagem provisório pelos sprites do protagonista original.
4. Criar animações de idle, corrida e salto.
5. Adicionar o primeiro inimigo e ataque de energia.

## Créditos

Protótipo criado como projeto original de aprendizado e portfólio, inspirado genericamente em jogos de plataforma e ação. Não contém personagens, cenários ou músicas copiados de outras franquias.

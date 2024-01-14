# Introdução

<img src="https://hypetech.games/assets/images/branding/dark.png" alt="Hypetech" width="350"/>

Neste desafio prático meu objetivo foi melhorar a experiencia do usuario implementando novas funcionalidades sem mudar a essencia do jogo atual.

jogo usado para este desafio: **Motograu**

## Sobre o Motograu

Com uma temática divertida e voltada ao público brasileiro, o **Motograu** é um jogo de categoria Crash, onde objetivo do jogador é **apostar no Motoqueiro e retirar sua aposta antes que o Cachorro Caramelo o derrube**.

Caso a aposta seja encerrada pelo jogador antes do Motoqueiro ser derrubado, o valor apostado é pago multiplicado pelo multiplicador do momento do cashout.

As rodadas são automáticas e os resultados são transmitidos ao vivo aos jogadores, fornecendo a todos os jogadores as mesmas probabilidades imparciais ao mesmo tempo, 24 horas por dia, 7 dias por semana.

![UI MotoGrau](https://i.ibb.co/42BnW3g/MotoGrau.png)


# Como rodar o projeto localmente:

### 1. Clone o repositório:
```bash
git clone [https://github.com/hypetechgames/frontend-challenge](https://github.com/Gabrielgs0/frontend-challenge.git)
```

### 2. Instale as dependências e inicie o projeto

Acesse a pasta do projeto:
```bash
cd frontend-challenge
```

Instale as dependências do projeto:
```bash
yarn install
```

Inicie o projeto:
```bash
yarn dev
```

### 3. Obtendo um token de acesso ao jogo

Para acessar o jogo é necessário obter um token de acesso que cria uma sessão demonstrativa funcional para desenvolvimento.

Para obtê-lo:

**1 - Acesse a API de Demonstração:** 
 https://hypetech-demo-api-service-developer.up.railway.app/docs/

**2 - Obtenha um link de demonstração:**	

	{ "gameUrl": "https://hypetech-games-ui-developer.up.railway.app/44cdf4cec80508c531f71a1929d591c8" }

**3 - Extraia o token obtido:**
~~https://hypetech-games-ui-developer.up.railway.app/~~**44cdf4cec80508c531f71a1929d591c8**

Exemplo: https://i.ibb.co/fp07Mxs/Screen-Recording-2024-01-08-at-17-59-36.gif

**4 - Acesse o jogo:**
Uma vez obtido o token, utilize-o no seu ambiente de desenvolvimento:

**Exemplo - URL do seu ambiente:** http://localhost:8000/
**Exemplo - URL do jogo no seu ambiente:** http://localhost:8000/2b29acad3f7a1e6b0995155668719e66

Caso encontre dificuldade em obter o token seguindo processo acima, você poderá utilizar os tokens públicos abaixo *(ciente que outros desenvolvedores podem estar utilizando a mesma sessão ao mesmo tempo)*:

**Motograu:** 44cdf4cec80508c531f71a1929d591c8

Claro! Aqui está a versão atualizada do README.md com o link para o site onde o jogo pode ser jogado:

---

# Jogo do Número Secreto

Este é um simples jogo de adivinhação de números implementado em JavaScript, HTML e CSS. O objetivo do jogo é adivinhar um número secreto gerado aleatoriamente entre 1 e 10. O jogo fornece dicas se o número adivinhado é maior ou menor que o número secreto até que o jogador acerte.

## Funcionalidades

- **Geração de Número Aleatório:** O jogo gera um número aleatório entre 1 e 10, que o jogador deve adivinhar.
- **Tentativas de Adivinhação:** O jogador pode chutar quantas vezes forem necessárias até acertar o número secreto. A cada tentativa, o jogo informa se o número correto é maior ou menor que o chute dado.
- **Mensagens de Voz:** As mensagens do jogo são exibidas na tela e também narradas utilizando a API `responsiveVoice`.
- **Reinício do Jogo:** Após acertar o número, o jogador pode reiniciar o jogo para tentar novamente.

## Como Jogar  

1. O jogo começa com uma mensagem pedindo para você escolher um número entre 1 e 10.
2. Insira o número no campo de input e clique no botão "Chutar".
3. O jogo informará se o número secreto é maior ou menor que o número chutado.
4. Continue chutando até descobrir o número secreto.
5. Após acertar, você verá a quantidade de tentativas que levou para acertar. O botão "Novo jogo" será habilitado para que você possa jogar novamente.

## Estrutura do Código

- **HTML:** Define a estrutura básica da interface do jogo.
- **CSS:** Estiliza os elementos do jogo, como o layout, cores e fontes.
- **JavaScript:**
  - `gerarNumeroAleatorio()`: Gera o número secreto de forma aleatória e garante que não seja repetido.
  - `verificarChute()`: Verifica se o número chutado pelo jogador é o número secreto e exibe as mensagens correspondentes.
  - `exibirTextoNaTela(tag, texto)`: Exibe as mensagens na tela e as narra em voz alta.
  - `reiniciarJogo()`: Reinicia o jogo gerando um novo número secreto e resetando as tentativas.
  - `limparCampo()`: Limpa o campo de input após cada tentativa.

## Requisitos

- Um navegador com suporte a JavaScript.
- Conexão à internet para carregar a biblioteca `responsiveVoice.js`.

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/ARui93/Curso_Js.git
   ```
2. Abra o arquivo `index.html` em seu navegador.

## Jogue Online

Você também pode jogar o jogo online através do seguinte link: [Jogo do Número Secreto](https://jogo-pink-theta.vercel.app/)

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias.

---

Assim, os usuários podem acessar o jogo diretamente online ou seguir as instruções para executar localmente.
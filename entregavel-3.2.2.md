Agora, vamos ao entregável!

Assuma o seguinte vetor de objetos de gatos:

```js

```

// 2. Mapeie o vetor de gatos para dentro desta div (deve mostrar apenas imagem e raça);
// 3. Ao clicar, faça aparecer em um alert um texto informando origem, ano de reconhecimento e temperamento;

5. Crie um botão para pintar de azul o fundo dos itens de gato cuja origem são os Estados Unidos
6. Crie um campo de texto e um botão filtrar. Ao pressionar o botão, pinte de roxo o fundo dos itens de gato que possuem o texto inserido no campo de texto (pesquisa nos campos raça, origem e temperamento). Sua busca deve ser case-insensitive. Utilize os método toLowerCase e includes. Exemplo:

```js
const textinho =
  "Vamos dar um rolê, eu vou te apresentar o melhor baile do Rio de Janeiro. Tu já sabe qual é, o Complexo da Penha é um verdadeiro pu...";
const textinhoEmMinusculas = textinho.toLowerCase();

const esseTrechoExiste = textinho.includes("Vamos dar um rolê"); // true
const esseTrechoNaoExiste = textinho.includes(
  "Golfinhos com botas de gelatina",
); // false
```

A partir daqui, é pra fazer aparecer no console, sem HTML:

7. Filtre os gatos reconhecidos depois dos anos 2000;
8. Qual a média dos anos de reconhecimento dos gatos?
9. Quantos gatos cuja origem não é dos Estados Unidos não soltam pelo?
10. Pergunte para o usuário via prompt qual gato ele quer ver (lá ele). Baseado na raça informada, redirecione o usuário para o link da imagem.

```js
window.location.href = "/gatos/havana_brown.jpg";
```

A entrega deve ser realizada através de um único link do GitHub. Apenas um integrante do grupo precisa entregar.
Lembre-se: nada de let, for, if, switch e outras paradas. O único momento onde o forEach é admitido é no momento de atribuir os eventos de clique!

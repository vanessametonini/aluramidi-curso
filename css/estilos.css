:root {
  --cinza: #aaa;
  --vermelha: #e93d50;
  --vermelha-escura: #af303f;
  --branca: #fff;
  --luz: rgb(229, 255, 0);
}

body {
  align-items: center;
  background: linear-gradient(45deg, #a7cfdf 0%,#23538a 100%);
  display: flex;
  justify-content: center;
  flex-direction: column;
  font-family: 'Montserrat', sans-serif;
  min-height: 100vh;
}

h1 {
  color: var(--branca);
  margin-bottom: 20px;
  font-size: 2rem;
}

.teclado {
  background: linear-gradient(to bottom, #eeeeee 0%,#cccccc 100%);
  box-shadow: 6px 8px 0 6px #666, 10px 10px 10px #000;
  border-radius: 30px;
  display: grid;
  gap: 10px;
  grid-template-columns: repeat(3, 1fr);
  padding: 10px;
}

.tecla {
  background-color: var(--branca);
  border-radius: 30px;
  box-shadow: 3px 3px 0 var(--cinza);
  color: var(--vermelha);
  cursor: pointer;
  height: 120px;
  font-size: 1.75em;
  font-weight: bold;
  line-height: 120px;
  text-align: center;
  width: 120px;
}

.tecla.ativa,
.tecla:active {
  background-color: var(--vermelha);
  border: 4px solid  var(--vermelha);
  box-shadow: 3px 3px 0 var(--vermelha-escura) inset;
  color: var(--branca);
  outline: none;
}

.tecla.focus,
.tecla:focus {
  outline: none;
  box-shadow: 1px 1px 10px var(--luz);
}

.tecla.active:focus,
.tecla:active:focus {
  box-shadow: 3px 3px 0 var(--vermelha-escura) inset, 1px 1px 10px var(--luz);
}

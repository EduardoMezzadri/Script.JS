# Script.JS
document.addEventListener('DOMContentLoaded', function(){ 
...
diminuiFonteBotao.addEventListener('click', function(){ 
tamanhoAtualFonte = 0.1; 
document.body.style.fontSize = ${tamanhoAtualFonte}rem` 
}) 
const botaoDeAcessibilidade = document.getElementById('botao-
acessibilidade'); 
const opcoesDeAcessibilidade document.getElementById('opcoes-
acessibilidade'); 
botaoDeAcessibilidade.addEventListener('click', function (){ 
botaoDeAcessibilidade.classList.toggle('rotacao-botao'); 
opcoesDeAcessibilidade.classList.toggle('apresenta-lista'); 
}) 
})

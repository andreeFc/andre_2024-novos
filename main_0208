document.querySelectorAll('.botao').forEach(btn => {
    btn.addEventListener('click', function() {

        document.querySelectorAll('.aba-conteudo').forEach(tab => {
            tab.classList.remove('ativo');
            // document.querySelectorAll('.botao').forEach(tab => {
            //           tab.classList.remove('ativo');   
        });
        const index = Array.from(document.querySelectorAll('.botao')).indexOf(this);
        document.querySelectorAll('.aba-conteudo')[index].classList.add('ativo');
        document.querySelectorAll('.botao')[index].classList.add('ativo');

    });
});

const botoes = document.querySelectorAll('.botao');
for(let i=0;i <botoes.length;i++){
    botoes[i].onclick = function() {
        for(let j=0;j<botoes.length;j++) {
            botoes[j].classList.remove('ativo'); }
        botoes[i].classList.add('ativo');}
        }
const contadores = document.querySelectorAll(".contador");
const tempoObjetivo1 = new Date("2024-08-05T00:00:00");
let tempoatual = new Date();

contadores[0].textContent = calculaTempo(tempoObjetivo1);

function calculaTempo(tempoObjetivo) {
    let tempoAtual = new Date();
    let tempoFinal = tempoObjetivo - tempoAtual;
    let segundos = Math.floor(tempoFinal / 1000);
    return segundos;
 }
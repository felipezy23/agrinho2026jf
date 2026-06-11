// ==========================
// AGRINHO - DO CAMPO PARA SUA MESA
// ==========================

console.log("Site Agrinho carregado com sucesso!");

// Seleciona todos os cards
const cards = document.querySelectorAll(".card");

// Mensagens para cada card
const mensagens = [
    "A produção agrícola é o primeiro passo para alimentar milhões de pessoas.",
    "O transporte conecta o campo às cidades, levando alimentos frescos para todos.",
    "O consumo consciente ajuda a valorizar o trabalho dos agricultores."
];

// Adiciona eventos aos cards
cards.forEach((card, indice) => {
    card.addEventListener("click", () => {
        alert(mensagens[indice]);
    });
});

// Mensagem de boas-vindas
window.addEventListener("load", () => {
    setTimeout(() => {
        alert("Bem-vindo ao projeto Agrinho: Do Campo para Sua Mesa!");
    }, 1000);
});

// Efeito ao passar o mouse nos cards
cards.forEach(card => {
    card.addEventListener("mouseenter", () => {
        card.style.transform = "scale(1.05)";
    });

    card.addEventListener("mouseleave", () => {
        card.style.transform = "scale(1)";
    });
});

// Contador de visitas na sessão
let visitas = sessionStorage.getItem("visitas");

if (!visitas) {
    visitas = 1;
} else {
    visitas = Number(visitas) + 1;
}

sessionStorage.setItem("visitas", visitas);

console.log(`Você visitou esta página ${visitas} vez(es) nesta sessão.`);

// Mostra a data atual no console
const hoje = new Date();

console.log(
    `Data de acesso: ${hoje.getDate()}/${hoje.getMonth() + 1}/${hoje.getFullYear()}`
);

# notas-atletas
DEV Projeto de certificação
🏅 Avaliação de Atletas – Ginástica Artística
📌 Descrição do Projeto

Este projeto consiste em uma aplicação desenvolvida em JavaScript para calcular a média válida das notas de atletas em uma competição de ginástica artística.

Cada atleta é avaliado por cinco jurados, e a média final é calculada desconsiderando a maior e a menor nota, conforme as regras oficiais da competição.

O sistema recebe o nome do atleta e suas cinco notas, processa os dados e exibe no console:

Nome do atleta

Notas obtidas (ordenadas)

Média válida calculada

📐 Regras de Avaliação

Cada jurado atribui uma nota de 1 a 10

A maior e a menor nota são descartadas

A média é calculada com base nas três notas centrais

📥 Estrutura de Entrada

A aplicação recebe uma matriz de objetos no seguinte formato:

let atletas = [
 {
   nome: "Cesar Abascal",
   notas: [10, 9.34, 8.42, 10, 7.88]
 },
 {
   nome: "Fernando Puntel",
   notas: [8, 10, 10, 7, 9.33]
 }
];

📤 Saída Esperada
Atleta: Cesar Abascal
Notas Obtidas: 7.88,8.42,9.34,10,10
Média Válida: 9.253333333333334

⚙️ Funcionamento da Lógica

Percorre todos os atletas com um laço for

Ordena as notas usando .sort()

Remove a maior e a menor nota com .slice()

Soma as três notas centrais com .forEach()

Calcula a média com base nas notas válidas

Exibe os resultados no console com console.log()

🧠 Tecnologias Utilizadas

JavaScript (ES6)

Console do navegador ou Node.js

▶️ Como Executar
Opção 1 – Navegador

Abra o Console do navegador (F12)

Cole o código JavaScript

Pressione Enter

Opção 2 – Node.js

Salve o código em um arquivo index.js

Execute no terminal:

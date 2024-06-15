Este repositório contém um estudo simples sobre três métodos úteis em JavaScript: includes, startsWith e endsWith. Esses métodos são usados para verificar se uma string ou um array contém um determinado valor ou começa/termina com uma substring específica.

Descrição dos Métodos
includes()
O método includes verifica se um array contém um determinado valor entre seus elementos ou se uma string contém uma determinada substring. Retorna true se o valor for encontrado, caso contrário, retorna false.

Exemplo com Array

let nomes = ["Matheus", "Lucas", "Jose"];

if(nomes.includes("Matheus")){
  console.log("ESTA NA LISTA");
} else {
  console.log("NAO ESTA NA LISTA");
}


Exemplo com String

let frase = "O sol está brilhando";
console.log(frase.includes("sol")); // true


startsWith()
O método startsWith verifica se uma string começa com os caracteres de uma determinada substring. Retorna true se a string começar com a substring especificada, caso contrário, retorna false.

Exemplo

let nome = "Matheus";
console.log(nome.startsWith("Mat")); // true


endsWith()
O método endsWith verifica se uma string termina com os caracteres de uma determinada substring. Retorna true se a string terminar com a substring especificada, caso contrário, retorna false.

Exemplo

let nome = "Matheus";
console.log(nome.endsWith("eus")); // true


Executando o Código
Para executar os exemplos de código fornecidos, você pode seguir estas etapas:

Certifique-se de ter o Node.js instalado em sua máquina.
Crie um arquivo JavaScript (por exemplo, index.js) e copie o código fornecido neste README para o arquivo.
Execute o arquivo no terminal usando o comando:

node index.js

Conclusão
Este estudo fornece uma visão geral básica dos métodos includes, startsWith e endsWith em JavaScript. Esses métodos são muito úteis para manipulação de strings e arrays, ajudando a realizar verificações rápidas e eficientes.

Sinta-se à vontade para explorar mais sobre esses métodos e experimentar diferentes exemplos para aprimorar seu entendimento.
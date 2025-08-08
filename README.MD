🚀 Projeto Arrays & Listas em JavaScript
Esse projetinho é um rolê básico e poderoso pra dominar o uso de arrays (listas) em JavaScript — essencial pra organizar dados e trabalhar com coleções de valores no seu código.

✨ O que tem aqui?
Criação de arrays vazios e com dados.

Inserção de elementos usando .push(), adicionando itens no final da lista.

Acesso a elementos pelo índice, começando do zero (primeiro elemento = índice 0).

Como pegar o último elemento da lista usando o tamanho da array (.length).

💻 Código em ação
js
Copiar
Editar
let listaGenerica = [];
let linguagensDeProgramacao  = ['JavaScript','C','C++', 'Kotlin', 'Python'];

// Adicionando linguagens no final da lista
linguagensDeProgramacao.push('Java', 'Ruby','GoLang');
console.log(linguagensDeProgramacao);

let listaDeNomes = ['Daniel', 'Milone', 'Garrafa'];
console.log(listaDeNomes[0]); // Imprime 'Daniel'

let listaDeFrutas = ['Banana', 'Maçã', 'Tomate'];
console.log(listaDeFrutas[1]); // Imprime 'Maçã'

let listaDeCarros = ['Celta', 'Palio', 'Monza'];
console.log(listaDeCarros[listaDeCarros.length -1]); // Imprime 'Monza' (último)
📚 Conceitos importantes
Arrays são coleções ordenadas, que guardam vários valores em sequência.

Índices começam em zero: o primeiro elemento é sempre o índice 0.

.push() adiciona um ou mais itens no fim da lista.

.length informa quantos elementos existem no array — perfeito pra pegar o último item com índice length - 1.

🎯 Use esse projeto para
Praticar manipulação de listas.

Entender conceitos básicos de estruturas de dados em JS.

Basear seus próximos códigos em manipulação de arrays para organizar informações.


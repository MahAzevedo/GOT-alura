Manipulando o DOM - Aula 1: Desenvolvendo JavaScript em Game Of Thrones.

Substituir o parágrafo: "O inverno está chegando" na tag <p>, por "Mádjan está chegando", diretamente no JavaScript, através do uso do DOM.
Pode ser por um único jeito, porém, aqui, usei dois:

.innerHTML() e;
.innerText().

.innerHTML(), 
".element.innerHTML - Esta propriedade obtém ou altera qualquer elemento no HTML, inclusive tags."

.innerText().
".element.innerText - Esta propriedade permite inserir textos no HTML."

.
.
.

Extraído de JavaScript: manipulando o DOM, por Pedro Marins, instrutor Alura:

aula: 01
Exercício 07 - Para saber mais: selecionando elementos.

O DOM (Document Object Model) e o JavaScript, juntos, possuem grande poder de modificar dinamicamente a estrutura de um documento HTML. Sendo possível, por exemplo:

.Adicionar/modificar/remover tags, textos, imagens e qualquer elemento no HTML.
.Alterar estilos CSS da página.
.Criar novos eventos HTML.

Vamos conferir formas de realizar os itens listados acima.

->>> Métodos para selecionar elementos no HTML

.document.getElementByID(id) - Recupera um elemento pelo ID.
.document.getElementsByTagName(name) - Recupera um elemento pelo nome.
.document.getElementsByClassName(name) - Recupera um elemento pelo nome da classe.


->>> Propriedades e métodos para alterar elementos no HTML

.element.innerHTML - Esta propriedade obtém ou altera qualquer elemento no HTML, inclusive tags.
.element.innerText - Esta propriedade permite inserir textos no HTML.
.element.value - Esta propriedade altera o valor de um elemento HTML
.element.setAttribute(atributo, valor) - Este método altera o valor de um atributo de um elemento HTML.


->>> Adicionando e excluindo elementos

.document.write() - Escreve no fluxo de saída do HTML.
.document.appendChild() - Adiciona um elemento HTML.
.document.removeChild() - Remove um elemento HTML.
.document.replaceChild() - Substitui um elemento HTML.
.document.createElement() - Cria um elemento HTML.

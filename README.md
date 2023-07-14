# Material gerado ao realizar o desafio Criando um Ebook com ChatGPT & MidJourney da DIO

## Criando um título poderoso

### Prompt

Crie um título de um ebook sobre o tema de CSS. O ebook é do nicho de programação e o subnicho é de CSS. O título deve ser épico e curto e tenha uma temática de Star Wars no título. Cite 5 variações de título em português.

### Melhor resultado

CSS Jedi: Domine a Força do Estilo na Web

## Criando o ebook

### Regras

> Usar tamanho de fontes múltiplas de 8: 8px, 16px, 24px, 32px, 40px, 48px

> Título com fonte sendo 2x acima da fonte normal considerando a regra de oito. Por exemplo, se a fonte normal for 24px, então o título terá 40px.

> Texto minimalista

> Ter um layout agradável

## Gerar o conteúdo do ebook

### Prompt

Faça um texto para ebook, com foco em CSS, listando os principais seletores CSS com exemplos em código

{REGRAS}

> Explique sempre de uma maneira simples

> Deixe o texto enxuto

> Sempre traga exemplos de código em contextos reais

> Sempre deixe um título sugestivo por tópico

### Resultado

Ebook: Guia dos Principais Seletores CSS

Índice:

1. Introdução
2. Seletores de Elementos
3. Seletores de Classe
4. Seletores de ID
5. Seletores de Atributo
6. Seletores de Descendência
7. Seletores de Filho Direto
8. Seletores de Adjacentes
9. Seletores de Pseudo-classes
10. Conclusão

1. Introdução

O CSS (Cascading Style Sheets) é uma linguagem essencial para estilizar páginas da web. Os seletores CSS desempenham um papel crucial ao segmentar elementos específicos em um documento HTML. Neste guia, vamos explorar os principais seletores CSS e fornecer exemplos de código para cada um deles.

2. Seletores de Elementos

Os seletores de elementos permitem segmentar um tipo específico de elemento HTML. Eles são representados pelo nome do elemento.

Exemplo:
```css
p {
  color: blue;
}
```

Neste exemplo, todos os elementos `<p>` terão sua cor de texto definida como azul.

3. Seletores de Classe

Os seletores de classe são usados para segmentar elementos com base em suas classes. Uma classe é atribuída a um ou mais elementos e é definida com um ponto (.) seguido pelo nome da classe.

Exemplo:
```css
.button {
  background-color: red;
}
```

Neste exemplo, todos os elementos com a classe "button" terão a cor de fundo definida como vermelho.

4. Seletores de ID

Os seletores de ID são semelhantes aos seletores de classe, mas segmentam elementos com base em seus IDs exclusivos. Um ID é atribuído a apenas um elemento e é definido com uma hashtag (#) seguida pelo nome do ID.

Exemplo:
```css
#header {
  font-size: 24px;
}
```

Neste exemplo, o elemento com o ID "header" terá o tamanho da fonte definido como 24 pixels.

5. Seletores de Atributo

Os seletores de atributo permitem segmentar elementos com base em atributos específicos. Eles são definidos entre colchetes ([]).

Exemplo:
```css
input[type="text"] {
  border: 1px solid gray;
}
```

Neste exemplo, todos os elementos `<input>` com o atributo `type` definido como "text" terão uma borda de 1 pixel sólida cinza.

6. Seletores de Descendência

Os seletores de descendência são usados para segmentar elementos que são descendentes de outro elemento. Eles são representados pelo espaço entre os seletores.

Exemplo:
```css
ul li {
  list-style: square;
}
```

Neste exemplo, todos os elementos `<li>` que são descendentes de um elemento `<ul>` terão o estilo de lista definido como "square".

7. Seletores de Filho Direto

Os seletores de filho direto são semelhantes aos seletores de descendência, mas segmentam apenas os elementos que são filhos diretos de outro elemento. Eles são representados pelo sinal de maior que (>).

Exemplo:
```css
div > p {
  font-weight: bold;
}
```

Neste exemplo, todos os elementos `<p>` que são filhos diretos de um elemento `<div>` terão o peso da fonte definido como negrito.

8. Seletores de Adjacentes

Os seletores de adjacentes segmentam o elemento adjacente imediatamente após outro elemento. Eles são representados pelo sinal de mais (+).

Exemplo:
```css
h2 + p {
  margin-top: 10px;
}
```

Neste exemplo, o elemento `<p>` que é adjacente imediatamente após um elemento `<h2>` terá uma margem superior de 10 pixels.

9. Seletores de Pseudo-classes

Os seletores de pseudo-classes segmentam elementos em estados específicos. Eles são representados por dois pontos (::) seguidos pelo nome da pseudo-classe.

Exemplo:
```css
a:hover {
  color: red;
}
```

Neste exemplo, quando um link (`<a>`) é ativado pelo evento de "hover" (quando o cursor está sobre ele), a cor do texto será alterada para vermelho.

10. Conclusão

Neste guia, exploramos os principais seletores CSS que você pode usar para estilizar seus elementos HTML. Lembre-se de experimentar e combinar diferentes seletores para obter resultados desejados. Com uma compreensão clara desses seletores, você estará pronto para criar estilos incríveis em suas páginas da web.

Espero que este guia tenha sido útil! Continue aprimorando suas habilidades em CSS e desfrute da criação de designs impressionantes para suas páginas da web.

## Diagramação

Foi utilizado o PowerPoint Online para a diagramação. Para estilizar os códigos CSS, foi utilizado o [Showcode](https://showcode.app)
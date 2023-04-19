<h1>Dia 01 - Conceitos importantes</h1>

<h2> > Adicionando JavaScript a uma página na Web</h2>
<h2>--------------------------------------------------------------------------------------------------------------------------</h2>

<p>JavaScript pode ser adicionado a uma página web de três formas:<br>
- Script em linha<br>
- Scrip Interno<br>
- Script externo<br>
- Múltiplos scripts externos<br></p>

<h3>· O que é Inline Script (script em linha)?</h3>

<p>Script inline é a criação de um script index.html</p>

<h3>· O que é internal Script (script interno)?</h3>

<p>Script interno é a escrita no <em>head</em> ou no <em>body</em>, e neste caso é melhor escrever no body do documento HTML.</p>

<h3>· O que é external Script (script externo)?</h3>

<p>Similar ao script interno, o script externo pode ser colocado no header ou no body, mas por preferência é inserido no body.<br> Primeiro é criado um arquivo com a extensão .js, todos os arquivos com a extensão .js são arquivos javascript.</p>

<h3>· O que é multiple external Script (multiplos scripts externos)?</h3>
<p>É possível conectar vários scripts externos a uma página web.</p>

<br>
<h2> > Introdução aos tipos de dados</h2>
<h2>---------------------------------------------------------------------------------------------------------------------------</h2>

<p>Nas linguagens de programação no geral, há diferentes tipos de dados. Os seguintes tipos são os dados primitivos:<br>
- String: coleção de caracteres dentro de aspas simples, duplas ou acento grave `<br>
- Number: inteiros e pontos flutuantes.<br>
- Boolean: True ou False<br>
- Undefined: Em javascript, se não for atribuido um valor a uma variavel o valor é <em>indefinido</em>. Se a função não retornar nada, é retornado indefinido.<br>
- Null: Valor nulo<br>
- Symbol: Retorna um valor do tipo símbolo, e cada valor é único (como um id)<br>

<br>
<h2> > Verificando os tipos de dados</h2>
<h2>---------------------------------------------------------------------------------------------------------------------------</h2>
- Para verificar o tipo de dado de uma varíavel, é utilizado o operador typeof:<br>
ex:<br>
console.log(typeof 'Asabeneh') // string<br>
console.log(typeof 5) // number<br>
console.log(typeof true) // boolean<br>
console.log(typeof null) // object type<br>
console.log(typeof undefined) // undefined<br>

<br>
<h2> > Comentários</h2>
<h2>---------------------------------------------------------------------------------------------------------------------------</h2>
Comentários no javascript é são á outras linguagens. Há duas formas de comentar:<br>
- Única linha: cada linha é utilizado '//'<br>
- Mútiplas linhas: A linha se inicia com /* e termina com */<br>

<br>
<h2> > Variáveis</h2>
<h2>---------------------------------------------------------------------------------------------------------------------------</h2>
Varíavel é um container de dados. Estes dados são alocados na memória. Quando uma variável é atribuida a um valor (dado), o espaço na memória será preenchido com o dado. Para declararmos uma variável nós utilizamos o var, let ou const.<br>
A diferença entre let e const é:<br>
- let: é uma variável, e seu valor pode ser alterado.<br>
- const: const é um tipo de variável que possui seu valor inalterável.
<br>
<br>
 - Os nomes das variáveis devem seguir as seguintes regras:<br>
- Não iniciar com um número.<br>
- JS não aceita caracteres especiais a não ser sinal de dolar e sublinhado '_'<br>
- Deve ser utilizado camelCase.<br>
- Não deve possuir espaços.

</p>
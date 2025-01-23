# Inserção de CÓDIGOS em Arquivo Markdown
<!-- Para indicarmos que um fragmento de texto é um Código de Linguagem de Programação, podemos utilizar o sinal de Crase (`) apenas envolvendo o conteúdo (se o mesmo for de apenas uma linha) ou envolver seu conteúdo multi-línea com 3 sinais de Crases (```) // Da mesma forma, podemos utilizar três acentos circunflexos (~) -->
<!-- Também podemos indicar a linguagem que estamos trabalhando (após as Crases ou após os acentos Circunflexos) para que o Markdown possa formatar conforme o esquema de cores da IDE - pois facilita a legibilidade do código -->

Comando para dizer: *"Olá, Mundo!"* <br>
`console.log("Olá, Mundo!")`

Comando para expressar um trecho maior de código:
```javascript 
if(ceu_ensolarado === true) {
    console.log("Bom dia, meu garoto!");
} else {
    console.log("Vai chover!!!");
}
``` 

Outro exemplo de código:
~~~javascript
for(let i in pearson) {
    console.log(pearson[i].toLowerCase());
}
~~~











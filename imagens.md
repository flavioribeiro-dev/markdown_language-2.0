# Inserindo Imagens em Markdown
<!-- O processo para se inserir Imagens em um arquivo Markdown é muito semelhante ao processo de inserção de Links, apenas com a diferença da necessidade de se incluir um sinal de Exclamação (!) antes dos parênteses -->
<!--    !(título da imagem)[endereço da imagem]    -->

![cidade "São Luís - MA"](IMAGENS/SAO%20LUIS%20-%20MA.jpg)
- Este método para inserção de imagens diretamente a partir da sintaxe do Markdown não permite a manipulação de suas dimensões. Ela será inserida de acordo com suas dimensões originais.
- Para conseguirmos fazer essa redefinição de tamanho, podemos utilizar a tag IMG do HTML com os atributos WIDTH e/ou HEIGHT:


<br>
<img src="imagens/SAO LUIS - MA.jpg" width="1000" alt="imagem Os Três Pescadores - São Luís, MA" title="imagem Os Três Pescadores - São Luís, MA">
Imagem definida com a Largura máxima de 1000px (adaptável conforme o tamanho da tela).
<!-- "1000px" é o valor máximo para definiçao de Largura/Altura em Imagens Markdown. Isso faz com a imagem ocupe a área máxima de exibição, se ajustando automaticamente conforme o tamanho da tela -->

<br><br>
<img src="imagens/SAO LUIS - MA.jpg" height="220px" alt="imagem Os Três Pescadores - São Luís, MA" title="imagem Os Três Pescadores - São Luís, MA"> <br>
Imagem definida com tamanho fixo de 220px.


<br>
- Outra vantagem da utilização da tag HTML para inserção de imagens é poder utilizar outros atributos, como o ALT e o TITLE.

# O que e CSS3, e sua historia

#### Aqui veremos.
 - 1.O que são seletores
 - 2.Conseitos básicos
 - 3.Principai seltores css
 - 4.ID x Classe
 - 5.Estilizando elementos
 - 6.Estilizando textos
 - 7.Estilizando listas
 - 8.Dimensão e alinhamento


---  
  #### Definição de Css
  Primeiramente, Css não e uma linguagem de programação, se assim como eu você pensava isso, errrrouuuu.kkk
  
  CSS e uma e uma linguagem de folha de estilo, ela foi criada no ano de 1996, é utilizado para definir como so documentos escritos na linguagem de marcação (HTML ou XML) irão ser apresentados em termos de marcação, de layout.Em quanto o HTML é usado para estruturar os conteúdos, o CSS é utilizado para formatá-los, o deixando do jeitinho que você quiser. 

  ###### Creditos: http://portalwebdesigner.com/programacao/css/
  ---
Uma regra Css e formatada, por um  Seletor, ou um clupo de Seletores.Seletores são apenas elementos HTML, exemplo (a,p,h1,h3) etc..

Dentro de um par de chaves temos declarações, exemplo(color:blue; font-size:14px;) uma declaração e formada por uma propriedade e um valor, mas existis varias outras propriedade.

#### 4. ID x Classe
No exemplo a sima, a regra a cima que foi usado como exemplo, ela mudaria a aparência de todo o nossa pagina, por isso e importante e muito importante porque significa que todos os elementos do nosso site ira ter a mesma aparência.então se você não quer este erro, ocorrendo no seu site, então presta bem atenção na importância dos ID e CLASS.A e muito importante, os ID e CLASS podem representar qualquer tipo de elemento, a algumas diferença entre eles, a mas obvio e que, na linguagem de MARCAÇÃO, HTML você declara seu ID com o nome ID, isso mesmo, difícil né kkk, e a sua <CLASS>, com a palavra <CLASS>.

E no CSS um ID, antes dele vem um ( . ) , exemplo .header{ padding: 10px; }. 

E uma CLASS antes dela vem ( # ), exemplo #header{ padding: 15px; }.

A e a ultima características e que um 9 ( ID ) só pode ser usado uma vez na pagina, isso mesmo.

---
### 5. Estilizando elementos



#### Box model
No processo de criação de um site, o navegador representa cada elemento HTML como uma caixinha retangular, chamamos isso de Box Model. Mas com o Css nos podemos alterar a aparência desta caixa como quisermos.O Box Model tem quatro areas.

 - 1-margen
 - 2-border
 - 3-padding
 - 4-content

##### Margin / Margin
E o espeçamentos entre elementos.

##### Border / Borda
As bordas elas circundam o paddim e o conteúdo, e nos conseguimos alterar a aparência delas como largura e cor.

##### Padding
O paddin e o espaçamento entre a borda e o conteúdo.

##### content
O conteúdo e o que o seu bloco representa, um texto uma imagem ou um video.

---
### 6. Estilizando textos

#### font-family
Ela e utilizada para mudar a fonte do nosso texto, e passível utilizar fonte da própria maquina ou da Web, por enquanto iremos ver as chamadas ( Web save fonts ) elas são chamadas assim porque elas se encontrão na maioria dos dispositivos, no exemplo a seguir 



 #title {

   font-family: verdana;

 }

 .post_title {

   font-family: verdana, arial;

 }
  

---

No primeiro exemplo esta sendo adicionada só Uma font, e no segundo exemplo estamos adicionando Duas, pós no caso da primeira falhar terá a segunda como backup.

#### font-size
O font-size altera o tamanho do nosso texto, 

Exemplo
 
 
#title {
   
    font-size: 30px;

 }

 .post-title [

     font-size: 18px;
 ]


---
#### sont-style
Ele altera a aparência do nosso texto, a muito importante presta atenção se a sua fonte tem suporte ao ITÁLICO, porque se não tiver, o navegador ira força a inclinação e pode não ficar legal.


Exemplo
 
 
#title {
   
     font-style: normal;

 }

 .subtitle [

     font-style: italic;
 ]


---
#### sont-weight
Ela altera o pesso do texto.


Exemplo
 
 
#title {
   
     font-weight: normal;

 }

 .subtitle [

     font-weight: bold;
 ]


---

#### text-transform
Ele altera o testo entre maiúsculo e minúsculo


Exemplo
 
 
#title {
   
     text-tranform: uppercase;

 }

 .subtitle [

     text-tranform: lowercase;
 ]

.post_title {

  text-transform: capitalisze;

}



 - ##### uppercase
Colocar todo texto em caixa alta.


 - ##### lowercase
Colocar todo text em caixa baixa.

 - ##### uppercapitaliszecase
Coloca todas as primeiras letras de cada palavra em maiúsculos.



---

#### text-decoration


Exemplo
 
 
#title {
   
     text-decorationht: underline;

 }

 .subtitle [

     text-decoration: overline;
 ]
 
 .post_title {

     text-decoration: line-through;

}



 - ##### underline
Coloca uma linha abaixo da palavra.

 - ##### overline
Coloca uma linha a cimada palavra.

 - ##### uppercaline-throughse
Coloca uma linha no centro da palavra, a linha fica cortando ao meio da palavra.

---

  #### 7. Estilizando listas
Para alterar o marcador desdas listas, utilizamos o ( list-style-type ).


Exemplo:

ul {

  list-style-type: square;
}

ol {

  list-style-type: upper-roman;
}

ul {

  list-style-type: " \1f44d ";
}

ul {

  list-style-image: url("Nome-do-arquivo-da-imagen")
}


- ####  list-style-type: square;
Altera o marcador de uma lita não ordenada, para um quadrado.

- ####  list-style-type: upper-roman;
Altera o marcador de uma lita não ordenada, para um algoritmo romado maiúsculo.

- ####    list-style-type: " \1f44d ";
Altera o marcador de uma lita não ordenada, para um simbolo.

---


### Dimensão e alinhamento


#### | width | heigt |
  
Eles servem para ajustar as larguras e alturas.

#### | max-width | max-heigt |
Eles servem para indicar, o máximo que o WIDTH e o HEIGT  deverá ir .


#### | margins |
Ele serve para colocar espaçamento em elementos, ele também serve para alinhar um elemento automaticamente.

#### | text align | 
Ele serve para alinhar texto, como o próprio nome já indica.kkkk

------

Se GOSTOU já sabe né, me SEQUE, e COMENTA me seque. se o artigo te ajudou, ou alguma coisa que ficou de fora, e seria útil, para adicionar ao artigo e para a comunidade.                     

GitHub: https://github.com/Janderson3223    

Linkdin: https://www.linkedin.com/in/janderson-costa-3435a4114/
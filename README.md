# Formulário
**Este formulário foi atualizado no dia 02 de outubro de 2024, sendo um projeto com finalidade de estudo.**

O modelo de formulário foi criado na linguagem HTML, contendo os campos: nome, cidade, idade e cpf para inserção de informações do usuário. Contêm um botão "enviar dados" abaixo dos campos, que finaliza o cadastro.
As informações de cadastro estão dentro de um quadrado, feito em CSS, de cor verde, para um maior destaque visual.
Tive uma certa dificuldade ao criar o quadrado em linguagem CSS, por falta de costume, juntamente com o botão que não foi possível deixar totalmente centralizado na tela.
E a inserção do CPF do usuário não está 100% completa, mas não aceita números negativos.

*  Os campos estão contidos em suas respecctivas 'divs', que por sua vez permanecem contidas dentro do campo 'form'.
*  O formato 'label' é utilizado para possibilitar preenchimento dos campos ao usuário.
*  São seguidos abaixo por 'input', seguido por 'type' para permitir apenas um determinado tipo ('text' ou 'number') em seus respectivos campos.

~~~ Código HTML:
  <form>
    <div>
      <label for="name"> Nome: </label>
      <input type="text" id="name" name="user_name"/> 
    </div>
~~~

*  Utilizo 'text-align:center', para deixar os textos centralizados.  
*  O código CSS foi feito de forma mais simples, não tendo tantas linhas de código
*  As bordas tem '0.6em', no formato 'outset'.

~~~ Código CSS:
html {
  height: 100%;
  width: 100%;
}
body {
  text-align: center;
}
form{
   border: 0.6rem outset #abe8b5;
}
~~~

*  Para maior controle de números, utilizo de 'min' ou 'max', a fim de regular os números que podem ser preenchidos pelo usuário.
~~~ Código:
<div>
      <label for="idade"> Idade: </label>
      <input type="number" id="idade" name="user_age" min="1" max="100"/>
    </div>
~~~
[Link para visualização do código](https://replit.com/@biaf0949/Formulario)

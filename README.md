#Breve resumo sobre Formulário e suas aplicações 

-->Compreensão sobre:
   --Label.
   --input.
   --Button.
   --Textarea.
   --E muito mais.
<html >
<head>
    <title>Formulários</title>
</head>
<body>
    <h1>Entendendo sobre Formulários</h1><br>
    
    <p><strong>Label:</strong>é uma etiqueta que especifica o rótulo de um input em um formulário<br>
        <br>
       <strong>Input:</strong>é uma tag que permite a criação de campos de entrada de dados em <br>
       formulários web ,permitindo que o usuário interaja com o site e forneça <br>
       informações.<br>
        Dentro de <strong>input</strong> podemos ter o <strong> type="" </strong> onde vamos definir o tipo do <br>
    da informação criada como: text,number,password.<br>
        Vamos definir também o <strong>name=""</strong> onde vamos identificar o valos de uma <br>
    variável. Podendo ser name,age,password e etc.<br>
     <br>
     Como vai aparecer no site :<br>
    </p>
    <ul>
    <li><p>Exemplo input tipo:text e name: name:</p><br></li>
    <label>Nome:</label><input type="text" name="name"><br>
    <br>
     
    <li><p>Exempo input tipo:number e name:age:</p><br></li><p>Exempo input tipo:number e name:age:</p><br>
    <label>Idade</label><input type="number" name="age"><br>
    <br>

    <li><p>Exemplo input tipo:passoword e name:passoword:</p><br></li>
    <label>Password</label><input type="password" name="password"><br>
    <br>
    </ul>

    <h1>Entendendo sobre o button</h1>
    <p><strong>Button:</strong>é o nome do botão que é enviado com os dos do formulário.<br>
       <strong>Button do tipo button :</strong>Você vai criar um botão.Ou seja ele não faz nada.<br>
       <strong>Observação:</strong>Observação:O botão só vai fazer algo caso tenha um JavaScript nele.<br>
    Você pode usar inumeros comandos vamos deixar alguns aqui abaixo.<br>
     <strong>Sobre os dados obrigatórios:</strong> É só colocar um * nele<br>
    </p>
    <ol>
     <li><p>Exemplo botão tipo button:</p></li> 
    <button type="button">clicável</button><br>
    
    <li><p>Exemplo botão tipo button com JavaScript onclick=alert</p></li>
    <button type="button" onclick="alert('cliquei aqui')" >Clicável</button><br>

    <li><p>Exemplo botão tipo button com JavaScript onclick=onmouseover</p></li><br>
    <button type="button" onmouseover="alert('passei aqui')" >Clicável</button><br>

    <li>Utilizando o button para dar um reset ou seja limpar.Atenção ele só limpa quem está dentro do form dele.</li>
    <form method ="get">
    <label>Nome:</label><input type="text" name="name"><br>
    <button type="reset">Limpar</button><br>
    </form><br>

    <li>Exemplo botão com tipo=submit onde ele envia o formulário.O onsubmit vai validar ele.</li><br>
    <form method ="get">
    <label>Nome:</label><input type="text" name="name"><br>
    <button type="submit">Enviar</button>
    </form><br>
     <p><Strong>Atenção !!!O botão enter no formulário submite ele apagando ele.</Strong></p>

    </form>
</ol>
    <h1>Select e seus tipos </h1>
    <p><strong>Select:</strong> é uma lista pré-definida que você quer que o usuário escolha.<br>
     Para isso vamos utilizar somente o label e a tag select<br>
    </p>
     
     <ol>
      <li><p>Exemplo select simples com role . Vai selecionar o cargo desejado de acordo com as metricas</p><br></li>
      <label>Cargo:</label>
      <select name="role">
         <option value="Administrativo" >Administrativo</option>
         <option value="Gerente" >Gerente </option>
         <option value="Diretor" >Diretor </option>
         <option value="Presidente" >Presidente </option>
         <option value="Técnico de TI" >Técnico de TI </option>
         <option value="Analista de dados" >Analista de dados </option>
         <option value="Cozinheiro" >Cozinheiro </option>
         <option value="Mestre de obras" >Mestre de obras </option>
      </select>
      <br>
     </ol>
     
     <h1>Textarea</h1>
     <p>Cria um texto com uma area maior do que a normal.</p><br>
        <label>Mensagem</label>
        <textarea name="message" ></textarea>
        <button type="submit" >Enviar </button>

        <h2>Atributos</h2>
        <p>cols colunas,rows numero de linhas </p><br>

</body>
</html>
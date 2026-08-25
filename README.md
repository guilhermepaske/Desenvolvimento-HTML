# Desenvolvimento-HTML
HTML, CSS


<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabela e Formulário WEB com HTML e CSS</title>
    <style>
        header{
            
            height: 150px;
            background-color: aqua;
            
        }

        main{
            
            height: 300px;
            background-color: rgb(0, 255, 42);
        }

        footer{
            
            height: 100px;
            background-color: rgb(47, 0, 255);
        }
        .estrutura{
         width: 800px;
        margin-left: auto;
        margin-right: auto;
        
        

        }
        h1{
            margin-left: auto;
            margin-right: auto;
            margin: 0px;
            /* padding: 50px; */
            background-color: rgba(89, 84, 94, 0.089);
        }
        .box{
            
            width: 100px;
            height: 200px;

            padding: 1px;
            border: 1px solid blue;
            margin: 1px;
        }
        .caixa {
    width: 400px;
    /* height: 200px; */

    /* padding: 40px; */
    border: 5px solid black;
    /* margin: 30px; */

    background-color: rgb(230, 173, 173);
}

table{ 
    font-family: Arial, Helvetica, sans-serif;
    background-color: rgb(218, 255, 196);
   

}
td{
    font-family:monospace
    background-color: gray
}
th {
background-color: #009ccc3a;
color: white;}
#cidade{
    width: 60%;
}
tr:nth-child(2n) {
background-color: #e9e9e9;
}
td:hover {
background-color: #0066cc30;
}
form, .caixa {
    margin-right: auto;
    margin-left: auto;
    background-color:coral
    
    
    
}
input{
    display: block;
    margin-bottom: 5px;
}

    </style>
</head>
<body>
    <header class="estrutura, box"></header>


    </header>
    <main class="estrutura ,">
          <h1>Tabela e Formulário WEB com HTML e CSS</h1>
          <table border ="1" width="800px" align="center"> 
            <tr>
                <th>Nome:</th>
                <th>Idade:</th>
                <th>Cidade:</th>
            </tr>
            <tr>
                <td>João</td>
                <td>21</td>
                <td>RJ</td>
            </tr>
              <tr>
                <td>Miguel</td>
                <td>67</td>
                <td>Tamandayork</td>
            </tr>
              <tr>
                <td>João</td>
                <td>21</td>
                <td>Bahia</td>
            </tr>
              <tr>
                <td>ESPASMOS22</td>
                <td>22</td>
                <td>RAJAAAAAH</td>
            </tr>
            <tr>
                <td>ESPASMOS22</td>
                <td>22</td>
                <td>RAJAAAAAH</td>
            </tr><tr>
                <td>ESPASMOS22</td>
                <td>22</td>
                <td>RAJAAAAAH</td>
            </tr><tr>
                <td>ESPASMOS22</td>
                <td>22</td>
                <td>RAJAAAAAH</td>
        
            </tr>
          </table>

    </main>
    <footer class="estrutura, caixa">
        <form action=""> 
            <h2>Formulário de contato</h2>
            <label for="">Nome:</label>
            <input type="text">
            <label for="">E-mail:</label>
            <input type="email">
            <label for="">Senha:</label>
            <input type="password">
            <button type="submit">Enviar Dados</button>
            
        </form>
       
          </form>
        
    </footer>
    
    
</body>
</html>

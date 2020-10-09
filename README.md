<!DOCTYPE html>
<html>    
    <head>
        <meta charset="utf-8"/>
        <title>Currículo</title>
        <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@700&display=swap" rel="stylesheet"/>
    <style>
        body{
            background-image: url(animais.png);
            background-attachment:scroll;
            background-position-y: 135px;
            background-size: 100%;
        }
        #BARRACABEÇALHO{
            position: fixed;
            top: 0px;
            left:0px;
            right: 0px;
            background-color:rgb(58, 34, 18);
            height:135px;
            border: 3px;
            border-style:solid;
            border-color: rgba(36, 21, 11, 0.384);
           }
        #s2{
            display: inline-block;
            height:60px;
            width: 400px;
            margin-top: 10px;
        }
        #s3{
            
            display: inline-block;
            height:100px;
            width: 550px;
        }   
        div{
            display:block;
            margin-left: auto;
            margin-right: auto;
        }
        #CORPO{
            background-color:rgba(0, 0, 0, 0.747);
            margin-top: 135px;
            height:2425px;
            width:700px;
            border: 3px;
            border-style:solid;
            border-color: rgba(36, 21, 11, 0.384);
        }
        #nome{
            font-family: 'Roboto', sans-serif;
        }
        #títulos{
            color:white;
            font-family: 'Roboto', sans-serif;
            text-shadow: 1px 1px 0px black; 
        }
        li{
            font-family: Arial, Helvetica, sans-serif;
            color:white;
        }
        #strong{
            color:rgb(255, 145, 0);
        }
        #ad{
            color: rgb(0, 255, 0);
        }
        #links{
            height: 50px;
            width: 250px;
            margin-left: auto;
            margin-right: auto;
        }
        #imagens{
            height: 1180px; 
            width: 650px;
        }
        #fonte2{
            color:rgb(222, 184, 135);
        }
        #textcolor{
            color:white;
            text-transform: 1000px;
        }
        #faixafinal{
            position: relative;
            background-color:rgb(70, 43, 25);
            margin-left: 0px;
            margin-right: 0px;
            display:block;
            height: 100px;
        }
        #faixadentro{
            position: relative;
            top: 20px;
            width: 400px;
            height: 60px;
        }
        #seila{
            font-family: 'Roboto', sans-serif;
        }
    </style>
</head>
    <body>
        <div> 
            <div align="center" id="BARRACABEÇALHO">
                <td>
                    <div id="s2" align="right"><font size="6" color="white"><strong>Mateus Durães dos Santos</font><br><font size="5" id="seila" color="lightgrey">Design</font></strong>
                    </div>
                        <img align="center" width="140" src="EU.png">
                    <div id="s3" align="left"><font color="lightgrey">Olá, tenho 19 anos e estou Cursando design. Sou cristão (protestante), gosto de tocar instrumetos músicais
                             de mexer no computador e criar artes. Nasci e sempre morei no estado de São Paulo, e agora que estou na faculdade estou a procura de oportunidades para
                              aprender, trabalhar e crescer profissionalmente no mercado de trabalho.</font>
                    </div>
                </td>        
            </div>
        </div>
        <div>
            <!-- DIV CORPO FUNDO PRETO-->
            <div id="CORPO">
                <div align="center">
                    <h1 id="títulos">
                        Formação
                    </h1>
                    <p>
                        <div align="left">
                            <li id="links">Design: <strong id="strong">Cursando</strong> (Mackenzie)</li>
                            <li id="links">Inglês: <strong id="strong">Cursando</strong> </li>
                            <li id="links">Ensino médio: <strong id="ad">Completo</strong></li>
                            <li id="links">Técnico em Montagem e Manutenção de
                            Computadores (Escotec, Senai) <strong id="ad">Completo</strong></li>
                        </div>
                    </p>
                    <h1 id="títulos">
                        Conhecimentos
                    </h1>
                    <!--ME EXPLICA, PORQUE "TR" E "TD" TEM QUE ESTAR DENTRO DE TABLE???????????? COMPLICADO....-->
                    <table>
                        <tr align="center">
                            <td width="325" height="180" bgcolor="white" align="center"><img src="habilidades11.png" width="300"></td>
                        </tr>
                    </table>
                    <h1 id="títulos">
                        Portifólio
                    </h1>
                    <p>
                        <div align="center">
                            <h1 id="links">
                                <div class="opt" onCLick="window.open('https://www.behance.net/mateusduraes','_blank');"><font id="fonte2"><p style="text-decoration: underline;">BEHANCE</font></div>
                            </h1>
                            <h1 id="links">
                                <div class="opt" onCLick="window.open('https://www.instagram.com/mateusduraesdesigner/','_blank');"><font id="fonte2"><p style="text-decoration: underline;">INSTAGRAM</font></div>
                            </h1>
                        </div>
                    </p>
                    <br>
                    <br>
                    <div id="imagens">
                        <div id="imagem">
                            <img align="left" height="304" src="portifólio/mockup.png"/>
                            <img align="right" width="320" src="portifólio/Peãomedieval.jpg"/>
                            <img align="left" width="330" src="portifólio/Cozinha.png"/>
                            <img align="left" height="355" src="portifólio/jóia 1.jpg"/>
                            <img align="right" width="355" src="portifólio/TABULEIRO.png"/>
                            <img align="left" width="295" src="portifólio/Rosas insta.png"/>
                            <img align="right" width="650" src="portifólio/L Mun 2.png"/>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div>
            <div id="faixafinal" align="center">
                <table id="faixadentro" >
                    <td>
                        <div align="center" class="opt" onCLick="window.open('https://www.instagram.com/mateusduraes_/','_blank');"><p style="text-decoration: underline;"><img align="center" height="30" src="inst.png"/><font size="4" color="white"> Instagram Pessoal</font></div>
                    </td>
                </table>
            </div>
        </div>
    </body>          
</html>

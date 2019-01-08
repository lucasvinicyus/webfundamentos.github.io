<!DOCTYPE html>
<!-- doctype informa ao agente de usuario a versão do html que deve ser
renderizada -->
<html lang="pt-br">
    <head>
        <title>pagina de exemplo estrutura basica</title>
        <meta charset="utf-8">
        <meta name="author" content="Lucas">
        <meta name="description" content="Lista de documentos">
        <meta name="keywords" content="HTML5, tecnologia">

        <link rel="stylesheet" href="estilo.css">
    </head>
    <body>

        <div id="principal">
            <header class="b">
                <nav>
                    <ul>
                        <li><a href="index..html">início</a></li>
                        <li><a href="#">projetos</a></li>
                        <li><a href="#">quem sou</a></li>
                    </ul>
                </nav>
                <div class="p">
                    <h1>Curso Web Fundamentos</h1>
                    <p>Aprenda HTML, CSS e JavaScript</p>
                </div>
            </header>

            <main>
                <section class="content-section">
                    <div class="card card_1">
                        <img src="images/card_01.png" alt="">
                        <p><b>Seletores</b></p>
                    </div>

                    <div class="card card_2">
                            <img src="images/card_04.jpg" alt="">
                            <p><b>Posicionamento</b></p>
                        </div>

                        <div class="card card_3">
                                <img src="images/card_05.jpg" alt="">
                                <p><b>Fontes e Icones</b></p>
                            </div>
                </section>

                <section class="content-section">
                    <article>
                        <header><h1 class="objetivo">Linguagens Usadas</h1></header>
                        <p><b>HTML5</b></p>
                        <p><b>CSS3</b></p>
                    </article>
                </section>
            </main>

            <footer id="copy">
                <p><b>copyright &copy; 2019</b></p>
            </footer>

        </div>
    </body>
</html>

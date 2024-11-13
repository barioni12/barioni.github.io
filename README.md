# barioni.github.io
_config.yml
theme: jekyll-theme-minimal
title: Octocat's homepage
description: Boolmark this to keep an eye on my project updates!
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" type="imagex/png" href="logo.jfif">
    <title>Campeonato de Xadrez - Projeto Escolar.</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Ubuntu:wght@400;500;700&display=swap');
        body {
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        .table {
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        body.dark-mode {
            background-color: #343a40;
            color: #f8f9fa;
        }

        .dark-mode .table {
            background-color: #212529;
            color: #f8f9fa;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2 class="text-center mt-5">Campeonato de Xadrez</h2>

        <section class="mt-4">
            <div class="row">
                <div class="col-md-6 offset-md-3">
                    <table class="table table-bordered table-striped">
                        <thead class="thead-light">
                            <tr>
                                <th>INSCRIÇÃO</th>
                                <th>PREMIO</th>
                                <th>ONG</th>
                                <th>ADMISTRAÇÃO</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>R$1,00</td>
                                <td>R$8,00</td>
                                <td>R$1,00</td>
                                <td>R$1,00</td>
                            </tr>
                            <tr>
                                <td>R$10,00</td>
                                <td>R$80,00</td>
                                <td>R$10,00</td>
                                <td>R$10,00</td>
                            </tr>
                            <tr>
                                <td>R$100,00</td>
                                <td>R$800,00</td>
                                <td>R$100,00</td>
                                <td>R$100,00</td>
                            </tr>
                            <tr>
                                <td>R$1000,00</td>
                                <td>R$8000,00</td>
                                <td>R$1000,00</td>
                                <td>R$1000,00</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </section>

        <section class="mt-4">
            <div class="row">
                <div class="col-md-6 offset-md-3">
                    <h3 class="text-center">Tabela de Brindes e Pontuação</h3>
                    <table class="table table-bordered table-striped">
                        <thead class="thead-light">
                            <tr>
                                <th>Brindes</th>
                                <th>Pontuação</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>Jogo de Panelas</td>
                                <td>250 Pontos</td>
                            </tr>
                            <tr>
                                <td>Celular</td>
                                <td>1500 Pontos</td>
                            </tr>
                            <tr>
                                <td>Tablet</td>
                                <td>2000 Pontos</td>
                            </tr>
                            <tr>
                                <td>Kit de Ferramentas</td>
                                <td>500 Pontos</td>
                            </tr>
                            <tr>
                                <td>Computador</td>
                                <td>2500 Pontos</td>
                            </tr>
                            <tr>
                                <td>Vale Compras de R$ 250,00</td>
                                <td>375 Pontos</td>
                            </tr>
                            <tr>
                                <td>Pix de R$ 500,00</td>
                                <td>500 Pontos</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </section>

        <section class="mt-4 text-center">
            <a href="https://www.youtube.com/watch?v=S1LsUT7jjDI" target="_blank">Como Jogar Xadrez</a> | 
            <a href="https://www.youtube.com/watch?v=8gfWyQb6fIU" target="_blank">Regras do Campeonato</a>
        </section>
    </div>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script>
        function applyTheme() {
            const isDarkMode = window.matchMedia('(prefers-color-scheme: dark)').matches;
            document.body.classList.toggle('dark-mode', isDarkMode);
        }

        applyTheme();
        window.matchMedia('(prefers-color-scheme: dark)').addEventListener('change', applyTheme);
    </script>
</body>
</html>

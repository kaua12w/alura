# alura


--------index

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <title>Meu portfólio</title>
</head>

<body>
    <header class="container text-center">
        <img src="img/avatar-perfil.png" alt="avatar da Fernanda" class="rounded-circle" width="150" height="150"
            srcset="">
        <p class="lead">Eu sou Fernanda_</p>
        <h1>Eu ensino Programação</h1>
        <p>Sou Engenheira de Computação e Pedagoga. Ensino pensamento computacional para estudantes do Ensino
            Fundamental e Médio. Ensino sobre pensamento computacional usando HTML, CSS e JavaScript. Veja os projetos
            que já desenvolvi!</p>
        <p>Minhas habilidades</p>
        <div>
            <p class="badge bg-secondary">HTML</p>
            <p class="badge bg-secondary">CSS</p>
            <p class="badge bg-secondary">JavaScript</p>
            <p class="badge bg-secondary">Scratch</p>
        </div>
    </header>
    <main class="container mt-5">
        <h2>Meus projetos</h2>
        <div class="row">
            <!-- Projeto 1 -->
            <div class="col-md-4">
                <div class="card">
                    <img src="img/projeto-1.png" class="card-img-top" alt="Imagem do projeto de biblioteca virtual">
                    <div class="card-body">
                        <h5 class="card-title">Minha Biblioteca: Uma Webpage Personalizada</h5>
                        <p class="card-text">Este projeto é uma página web que apresenta uma lista dos meus livros
                            favoritos, incluindo informações sobre os autores, datas de publicação e links para compra
                            na Amazon. A página é estilizada com CSS para uma visualização agradável e usa fontes
                            externas do Google Fonts.
                        </p>
                        <button type="button" class="btn btn-link" data-bs-toggle="modal" data-bs-target="#modal1">Veja
                            o projeto</button>
                    </div>
                </div>
            </div>
            <!-- Projeto 2 -->
            <div class="col-md-4">
                <div class="card">
                    <img src="img/projeto-2.png" class="card-img-top" alt="Imagem do projeto de biblioteca virtual">
                    <div class="card-body">
                        <h5 class="card-title">Decidindo o Futuro: Uma Jornada Interativa sobre a Inteligência
                            Artificial</h5>
                        <p class="card-text">Este projeto é um jogo interativo baseado em navegador que explora o
                            impacto e as implicações da Inteligência Artificial (IA) na sociedade, permitindo que as
                            pessoas jogadoras façam escolhas que influenciam o desenrolar de uma narrativa sobre o
                            futuro da IA.</p>
                        <button type="button" class="btn btn-link" data-bs-toggle="modal" data-bs-target="#modal2">Veja
                            o projeto</button>
                    </div>
                </div>
            </div>

            <!-- Projeto 3 -->
            <div class="col-md-4">
                <div class="card">
                    <img src="img/projeto-3.png" class="card-img-top" alt="Imagem do projeto de biblioteca virtual">
                    <div class="card-body">
                        <h5 class="card-title">Explorando o Universo: Uma Aventura Interativa em Astronomia com Scratch
                        </h5>
                        <p class="card-text">EEste projeto Scratch cria uma experiência interativa educativa sobre
                            astronomia, permitindo aos usuários explorar informações sobre constelações, eclipses, e a
                            forma da Terra através de cenários dinâmicos e diálogos informativos.
                        </p>
                        <button type="button" class="btn btn-link" data-bs-toggle="modal" data-bs-target="#modal3">Veja
                            o projeto</button>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- Modal 1 -->
    <div class="modal" id="modal1" tabindex="-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">Minha Biblioteca: Uma Webpage Personalizada</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <p>O projeto é uma página web criada com HTML e CSS, destinada a exibir uma coleção pessoal de
                        livros favoritos. O objetivo é criar um ambiente virtual onde seja possível compartilhar
                        seus livros preferidos, fornecendo uma descrição breve de cada um, incluindo o autor, o ano
                        de publicação e uma opção de compra.</p>
                    <p>A estrutura do site é baseada em HTML, que define a semântica e o layout do conteúdo,
                        enquanto o CSS é usado para estilizar a página visualmente, incluindo cores, tipografia e a
                        disposição dos elementos.</p>
                    <p>O HTML organiza o conteúdo em um cabeçalho com o título do site, seguido por uma divisão
                        principal (.container) que apresenta o propósito do site e a coleção de livros em uma seção
                        flexível (.livros). Cada livro é destacado em seu próprio contêiner (.livro), mostrando uma
                        imagem da capa, detalhes do livro e um link de compra. O design responsivo é garantido pelo
                        uso de uma meta tag viewport e um layout flexível que se adapta a diferentes tamanhos de
                        tela.</p>
                    <p>O CSS personaliza o visual do site, usando variáveis para cores, estilizando o texto com uma
                        fonte importada do Google Fonts e aplicando um esquema de cores suaves e botões interativos.
                        O uso de HTML e CSS é importante pois assim é possível criar um site acessível e
                        esteticamente agradável sem a necessidade de scripts complexos, com foco na usabilidade e na
                        experiência da pessoa usuária. A escolha da tipografia e do esquema de cores contribui para
                        a atmosfera acolhedora do site, incentivando a exploração da coleção de livros.</p>
                    <img src="img/projeto-1.png" alt="Imagem representativa do projeto de uma biblioteca online">
                </div>
                <div class="modal-footer">
                    <a href="https://femascheti.github.io/minhas-leituras/">Ver projeto ao vivo</a>
                    <a href="https://github.com/femascheti/minhas-leituras">Ver código do projeto</a>
                </div>
            </div>
        </div>
    </div>

    <footer class="container py-5">
        <h2>Entre em contato</h2>
        <div>
            <a href="https://github.com/femascheti">GitHub</a>
        </div>
        <p class="my-5 text-center">© Copyright 2024. Produzido por Fernanda Mascheti</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>


--------------------style.css

@import url('https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap');

:root {
    --cor-principal: #6E859F;
    --cor-secundaria: #284260;
    --cor-destaque: #C92BFC;
}

body {
    font-family: 'Chakra Petch', sans-serif;
}

h1, h2, h5 {
    color: var(--cor-secundaria);
    font-weight: 700;
}

footer a {
    color: var(--cor-principal)
}

footer a:hover {
    color: var(--cor-destaque);
}

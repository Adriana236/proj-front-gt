/* Estilizando o layout principal */
header {
    display: flex;
    flex-direction: column; /* Colocar elementos (logo e nav) em uma coluna */
    align-items: flex-start; /* Alinhar ao lado esquerdo */
    padding: 20px;
}

/* Estilo da logo */
.logo {
    max-width: 150px; /* Tamanho da logo */
    margin-bottom: 20px; /* Espaço entre a logo e a barra de navegação */
}

/* Estilo da barra de navegação */
nav {
    background-color: gray; /* Cor de fundo da barra cinza */
    padding: 10px;
    width: 200px; /* Definir a largura da barra de navegação */
}

/* Estilo dos links na barra */
nav a {
    text-decoration: none;
    color: white; /* Cor do texto */
    padding: 10px 15px;
    display: block; /* Exibir links como blocos para ficarem um embaixo do outro */
    position: relative; /* Necessário para a linha inferior */
}

/* Efeito de clique */
nav a:active {
    color: pink; /* Cor rosa ao clicar */
    text-decoration: underline; /* Palavra sublinhada ao clicar */
}

/* Adicionar linha ao clicar */
nav a:active::after {
    content: "";
    position: absolute;
    left: 0;
    bottom: -5px; /* Aumentar distância da linha para baixo da palavra */
    width: 100%;
    height: 2px;
    background-color: pink; /* Linha rosa */
}

/* Cor ao passar o mouse */
nav a:hover {
    background-color: darkgray; /* Somente como extra */
}

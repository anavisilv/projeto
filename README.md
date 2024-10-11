<body>

</body>
<body>
    <header class="cabeçalho">
        <span class="cabeçalho__menu-hamburguer"></span>
        <img src="img/Logo.svg" alt="Logo da AluraBooks">
    </header>
</body>
<body>
    <header class="cabeçalho">
        <span class="cabeçalho__menu-hamburguer"></span>
        <img src="img/Logo.svg" alt="Logo da AluraBooks">
        <a href="#"><img src="img/Favoritos.svg"></a>
        <a href="#"><img src="img/Compras.svg"></a>
        <a href="#"><img src="img/Usuario.svg"></a>
    </header>
</body>
<body>
    <header class="cabeçalho">
        <span class="cabeçalho__menu-hamburguer"></span>
        <img src="img/Logo.svg" alt="Logo da AluraBooks">
        <a href="#"><img src="img/Favoritos.svg" alt="Meus favoritos"></a>
        <a href="#"><img src="img/Compras.svg" alt="Carrinho de compras"></a>
        <a href="#"><img src="img/Usuario.svg" alt="Meu perfil"></a>
    </header>
</body>
.cabeçalho__menu-hamburguer {
    width: 24px;
    height: 24px;
    display: inline-block;
    background-image: url("../img/Menu.svg");
    background-repeat: no-repeat;
    background-position: center;
}
@import url("styles/header.css");
:root {
    --cor-de-fundo: #EBECEE;
    --branco: #FFFFFF;
}
.cabeçalho {
    background-color: var(--branco);
}
<header class="cabeçalho">
    <div class="container">
        <span class="cabeçalho__menu-hamburguer"></span>
        <img src="img/Logo.svg" alt="Logo da AluraBooks">
    </div>
    <a href="#"><img src="img/Favoritos.svg" alt="Meus favoritos"></a>
    <a href="#"><img src="img/Compras.svg" alt="Carrinho de compras"></a>
    <a href="#"><img src="img/Usuario.svg" alt="Meu perfil"></a>
</header>
<header class="cabeçalho">
    <div class="container">
        <span class="cabeçalho__menu-hamburguer"></span>
        <img src="img/Logo.svg" alt="Logo da AluraBooks">
    </div>
    <div class="container">
        <a href="#"><img src="img/Favoritos.svg" alt="Meus favoritos"></a>
        <a href="#"><img src="img/Compras.svg" alt="Carrinho de compras"></a>
        <a href="#"><img src="img/Usuario.svg" alt="Meu perfil"></a>
    </div>
</header>
.cabeçalho {
    background-color: var(--branco);
    display: flex;
    justify-content: space-between;
}
.cabeçalho {
    background-color: var(--branco);
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.container {
    display: flex;
    align-items: center;
}
<header class="cabeçalho">
    <div class="container">
        <span class="cabeçalho__menu-hamburguer container__imagem"></span>
        <img src="img/Logo.svg" alt="Logo da AluraBooks" class="container__imagem">
    </div>
    <div class="container">
        <a href="#"><img src="img/Favoritos.svg" alt="Meus favoritos" class="container__imagem"></a>
        <a href="#"><img src="img/Compras.svg" alt="Carrinho de compras" class="container__imagem"></a>
        <a href="#"><img src="img/Usuario.svg" alt="Meu perfil" class="container__imagem"></a>
    </div>
</header>
.container__imagem {
    padding: 1em;
}

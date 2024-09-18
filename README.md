index.html

<head>
    <title>Alura Plus</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
</head>
:root {
    --branco-principal: #FFFFFF;
    --cinza-secundario: #C0C0C0;
    --botao-azul: #167BF7;
    --cor-de-fundo: #00030C;
    --fonte-principal: 'Inter';
}
body {
    background-color: var(--cor-de-fundo);
    color: var(--branco-principal);
    font-family: var(--fonte-principal);
    font-size: 16px;
    font-weight: 400;
}
.container__aviso {
    font-size: 12px;
    color: var(--cinza-secundario);
}
.container__botao {
    background-color: var(--botao-azul);
    border-radius: 5px;
    padding: 1em;
    color: var(--branco-principal);
    display: block;
    text-decoration: none;
}
<section class="container principal">
        <div>
            <h1 class="container__titulo">Com o Combo+, você pode aproveitar a Alura+ e o Alura Língua por um preço
                único.
            </h1>
            <img src="img/Combo.png" alt="O combo+ é a junção do alura+ e o alura língua">
            <a href="www.alura.com.br" class="container__botao">Assine por 12x de R$ 120,00*</a>
            <a href="www.alura.com.br" class="container__botao botao_secundario">Assinar somente o Alura+</a>
            <p class="container__aviso">*O preço pode variar caso a assinatura seja feita em outros planos.</p>
        </div>
    </section>
    .container__titulo {
    font-size: 28px;
    font-weight: 700;
}

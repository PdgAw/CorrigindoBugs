| HTML |

<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />

    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <title>Móveis customizados</title>

    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Open+Sans:wght@400;700&display=swap"
      rel="stylesheet"
    />

    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <div id="hero">
      <img
        src="images/img1.jpg"
        alt="Desenho de uma pessoa vestindo uma camisa amarela em uma sala com Móveis"
      />

      <h1>Ambientes <span>únicos</span> para você!</h1>

      <p>
        Nós criamos ambientes <strong>exclusivos</strong> e
        <strong>únicos</strong>, com muito bom gosto e profissionalismo,
        investimos tempo e
        <span>dedicação no seu projeto.</span>
      </p>

      <br />
      <br />

      <p>
        Tenha <span>ambientes limpos</span> e bem decorados, transmitindo
        <strong>elegância </strong> e <strong>finesse</strong>
        para todo aquele que estiver ali.
      </p>
    </div>

    <div id="footer">
      <div class="line"></div>

      <a 
        target="_blank" 
        href="https://instagram.com/moveisparavoce">
        Instagram
      </a>

      <a 
        href="mailto:contato@moveisparavoce.com"> 
        Fale conosco 
      </a>
    </div>

    <img
      id="balls"
      src="images/balls.svg"
      alt="Bolinhas alaranjadas no canto inferior direito da tela"
    />
  </body>
</html>

| CSS |

body {
  font-family: 'Open Sans', sans-serif;
  text-align: center;
  margin: 0;   
}

#hero {
  width: 592px;
  margin: 0 auto 72px;
}

#hero img {
  margin-bottom: 72px;
}

h1 {
  font-family: 'Inter';
  font-size: 49px;
  line-height: 56px;
  font-weight: normal;

  margin-bottom: 32px;
}

h1 span {
  font-weight: bold;
}

span,
a {
  color: #ff9900;
}

p {
  color: #7d7987;
}

p,
#footer {
  font-size: 14px;
  line-height: 28px;
}

#footer a + a {
  margin-left: 28px;
}

.line {
  width: 568px;
  height: 0;
  margin: 0 auto 8px;

  border: 1px solid #eceff2;
}

#balls {
  position: fixed;
  bottom: 0;
  right: 0;
}


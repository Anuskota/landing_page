
PROYECTO INDIVIDUAL PARA CLIENTE FEMCODERS NORTE 

Este repositorio recoge el diseño sobre una aplicación multiplataforma enfocada a la optimización del tiempo de trabajo y con ello conseguir mejores resultados.

Se han utilizado los siguientes lenguajes:

- <a href="https://www.w3.org/TR/?tags%5B0%5D=html">HTML</a>
- <a href= "https://www.w3.org/TR/?tags%5B0%5D=css">CSS</a>

1. <a href="https://github.com/Anuskota/landing_page/blob/main/index.html">HTML</a> y <a href="https://github.com/Anuskota/landing_page/blob/main/index.css">CSS</a>
    
    Herramientas utilizadas:
   <ul>
   <li>Visual Studio Code</li>
   <li>Estructuras de etiquetas en HTML</li>
   <li>Estructuras de estilos CSS</li>
   <li><a href="https://www.figma.com">Figma</a></li>
   <li><a href="https://favicon.io">Favicon</a></li>
   <li><a href="https://fontawesome.com/">Fontawesome</a></li>
   <li><a href="https://github.com/Anuskota">GitHub</a></li>
   <li><a href="https://trello.com">Trello</a></li>


   </ul>

   @media (max-width: 768px) {
    .header {
        flex-direction: column;
        padding: 5px 5%;
    }

    .header .nav-links {
        flex-direction: row;
        align-items: center;
    }

    .header .nav-links li {
        padding: 10px 0;
    }
}


@media (min-width: 601px) and (max-width: 1024px) {
    .header {
        padding: 5px 7%;
    }
    .header .nav-links {
        justify-content: space-around;
    }
    .header .nav-links li {
        padding: 0 10px;
    }
}


@media (min-width: 1025px) {
    .header {
        padding: 5px 10%;
    }
    .header .nav-links {
        justify-content: flex-end;
    }
    .header .nav-links li {
        padding: 0 20px;
    }
}
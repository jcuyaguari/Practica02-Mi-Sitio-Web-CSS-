# Practica02-Mi-Sitio-Web-CSS-
ACTIVIDADES POR DESARROLLAR  
Crear un repositorio en GitHub con el nombre “Practica02 – Mi Sitio Web (CSS)” 
2.	Realizar un commit y push por cada requerimiento de los puntos antes descritos. 
C:\Users\JuancUyaguari>cd Desktop                                                                                                                                                                                                                                                                                                                                                                                                 C:\Users\JuancUyaguari\Desktop>cd Hipermedial                                                                                                                                                                                                                                                                                                                                                                                     C:\Users\JuancUyaguari\Desktop\Hipermedial>cd Deber2                                                                                                                                                                                                                                                                                                                                                                              C:\Users\JuancUyaguari\Desktop\Hipermedial\Deber2> git init
C:\Users\JuancUyaguari\Desktop\Hipermedial\Deber2> git add .
C:\Users\JuancUyaguari\Desktop\Hipermedial\Deber2> git commit -m “creacion”
C:\Users\JuancUyaguari\Desktop\Hipermedial\Deber2> git push -u origin master
3.	Al finalizar la práctica se debe validar todas las páginas HTML y hojas de estilos CSS creadas usando el W3C Validator. 
Generar informe de los resultados en el formato de prácticas. Debe incluir: 
•	El desarrollo de cada uno de los puntos antes descritos así como las reglas CSS utilizadas para resolver cada punto.  
1.	Una página HTML, un diseño a dos columnas con cabecera y pie de página.
#columna2{
    width: 78%;
    float: left;
    text-align: justify;
    padding-bottom: 10px;
    margin-left: 10px;
    margin-right: 0px;
    padding-left: 10px;
    padding-right: 10px;
    margin-bottom: 10px;
}

footer{
    clear: both;
    border-width: thin 0px;
    border-style: ridge;
    background-color: rgba(218, 221, 23, 0.945);
}
En la etiqueta div, llamamos al selector por id “columna2”.
<div id=columna2>
En la etiqueta <head> enlazamos los “css” donde se encuentra dicha configuración.
<head>
    <meta charset="utf-8" />
    <meta name="keywords" content="Pacari" />
    <title>Pacari Chocolate</title>
    <link href="css/reglas.css" rel="stylesheet" type="text/css"/>
    <link href="css/2columnas.css" rel="stylesheet" type="text/css"/>
</head>
2.Una página HTML, un diseño a tres columnas con cabecera y pie de página.
•	En la etiqueta <section> llamamos al identificador por id.
                <section class="seccion1">      <section class="seccion2">
•	En la etiqueta <head> enlazamos los “css” donde se encuentra dicha configuración.
               <link href="css/reglas.css" rel="stylesheet" type="text/css"/>
               <link href="css/2columnas.css" rel="stylesheet" type="text/css"/>
               <link href="css/3columnas.css" rel="stylesheet" type="text/css"/>
•	La evidencia del correcto diseño de las páginas HTML usando CSS. Para lo cuál, se puede generar fotografías instantáneas (pantallazos).  
Index.html
Consta de las etiquetas:
<head> </head>
<body></body>
<header> </header>
<nav> </nav>
<div> </div>
<section> </section>
<article> </article>
<aside> </aside>
•	Evidencia de las etiquetas con sus propiedades.

h1{
color:rgb(136, 122, 41); 
font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
text-decoration: underline;
font-size: 24px;
}
h2{
    color: goldenrod; 
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    text-decoration: darkred;
    font-size: 20px;
}
h4{
    color: brown;
    font-family: cursive;
    text-decoration: olive;
    font-size: 18px;
}
•	Evidencia de hipervínculos usando pseudo-clases. 
a{
    color:mediumslateblue;
    font-weight: bold;
}

a:visited{
    color: rgb(94, 94, 138);
}
a:hover,a:active,a:focus {
  color: rgb(199, 55, 55);
  text-decoration: none;
}

GitHub
Usuario:jcuyaguari
url: https://github.com/jcuyaguari/Practica02-Mi-Sitio-Web-CSS-

6. En el archivo README del repositorio debe constar la misma información del informe de resultados de la práctica que se indica en el punto anterior. 
•	La evidencia de la validación de las hojas de estilos CSS. 
1.	Validación para el css de dos columnas.

CONCLUSIONES:  
•	Gracias a esta práctica he podido aprender a como dar estilos a las etiquetas, así también entender un poco mas sobre las propiedades que posee html5.
•	A través de esta práctica aprendí mas a cerca de como asignar las configuraciones de css en html5 a sus respectivas etiquetas.
RECOMENDACIONES:  
•	Realizar la practica en un IDE que nos permita editar el código de forma más rápida, y probar constantemente, por los menos en dos navegadores lo que se va realizando para ver los cambios que se han hecho. 























#**Guía de color para Space Box**

El diseño de Space Box está compuesto por el logo en blanco, sobre un fondo degradado oscuro. Aunque también tiene una alternativa, donde se usa el logo en negro, sobre un fondo degradado claro.
Aparte de los colores ya mencionados, el diseño incluye colores auxiliares:  un color principal y tres colores alternativos,  para realzar y destacar detalles. Estos colores se pueden utilizar tanto sobre fondos oscuros, como claros.

A continuación se encuentran los códigos de todos los colores utilizados, junto al código CSS necesario para generar los gradientes de fondo; para adaptar el diseño a formato Web.

###Diseño oficial

Logo en color blanco plano:

>      #ffffff;
>      rgb(255, 255, 255);
>      hsl(0, 0%, 100%);

El fondo presenta un degradado entre dos tonos de azul oscuro:
Color superior:
>    topColor:
>      #091a51;
>      rgb(9, 26, 81);
>      hsl(226, 80%, 18%);

Color inferior (color más oscuro):
>    bottomColor:
>      #040a22;
>      rgb(4, 10, 34);
>      hsl(228, 79%, 7%);

Código CSS para degradado de fondo:
>	      .darkBgGradient{
>	        background: #091a51;
>	        background: linear-gradient(#091a51, #040a22);
>	        background: -moz-linear-gradient(#091a51, #040a22);
>	        background: -webkit-linear-gradient(#091a51,#040a22);
>	      };

###Diseño alternativo

Logo en color negro plano:

>	#000000;
>      rgb(0, 0, 0);
>      hsl(0, 0%, 0%);

El fondo presenta un degradado entre dos tonos de gris claro:
Color superior:
>topColor:
>      #f6f6f8;
>      rgb(246, 246, 248);
>      hsl(240, 13%, 97%);

Color inferior (color más oscuro):
>bottomColor:
>      #c8cad1;
>      rgb(200, 202, 209);
>      hsl(227, 9%, 80%);

Código CSS para degradado de fondo:
>		.lightBgGradient{
>	        background: #f6f6f8;
>	        background: linear-gradient(#f6f6f8, #c8cad1);
>	        background: -moz-linear-gradient(#f6f6f8, #c8cad1);
>	        background: -webkit-linear-gradient(#f6f6f8,#c8cad1);
>	      };

###Colores auxiliares

**Color auxiliar principal**
Utilizado para realzar elementos:

Naranja:
>highlightMain:
>	#f17043;
>	rgb(241, 112, 67);
>	hsl(16, 86%, 60%);

**Colores auxiliares alternativos**
Utilizados cuando el color principal no logra destacar entre otros elementos, o cuando se necesita más de un color:

Verde:
>highlightGreen:
>	#19b371;
>	rgb(25, 179, 113);
>	hsl(154, 75%, 40%);

Azul:
>highlightBlue:
>	#1d3597;
>	rgb(29, 53, 151);
>	hsl(228, 68%, 35%);

Amarillo:
>highlightYellow:
>	#f1cf43;
>	rgb(241, 207, 67);
>	hsl(48, 86%, 60%);


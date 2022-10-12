### DOCUMENTACIÓN

- se enlazo el HTML con la pagina de estilos.css
- se enlazo google fonts para tipografias en el body (Open Sans)
        <!DOCTYPE html>
		<html lang="en">
		<head>
    	<meta charset="UTF-8">
    	<meta http-equiv="X-UA-Compatible" content="IE=edge">
    	<meta name="viewport" content="width=device-width, initial-scale=1.0">
    	<title>Deezer</title>
    	<link rel="stylesheet" href="/style.css">
    	<link rel="preconnect" href="https://fonts.googleapis.com">
    	<link rel="preconnect" href="https://fonts.googleapis.com">
    	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    	<link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&family=Roboto:wght@100&display=swap" rel="stylesheet">
		</head>

- en el codigo html se utilizaron contenedores para poderle dar un a estructura a la pagina los cuales se modificaron desde css

     	<div class="contenedor">
        <div class="caja_texto1">
            <h3>Escucha música on demand</h3>
            <div class="color_text">
                <p >Escucha lo que quieras, disfruta de saltos ilimitados y arma tu propia colección de música, podcasts y más.</p>
            </div>
        </div>
        <div class="caja_texto1">
            <h3>Vive una experiencia sin anuncios</h3>
            <div class="color_text">
            <p>Escucha todo tu contenido en audio favorito sin interrupciones por anuncios.</p>
            </div>
        </div>
        <div class="caja_texto1">
            <h3>Escucha sin conexión</h3>
            <div class="color_text">
            <p>Descarga tu música y tus podcasts y escucha sin conexión.</p>
            </div>
        </div>
    </div>
- en el html se encuentran dos carpetas de imagenes las cuales contienen imagenes utilizadas en el proyecto.
- desde el css se modifico la estructura de algunas etiquetas, como las etiquetas (h1,h2,h3,h4..) para cambiar su tipografia; etiqueta (a) para cambiar sus parametros predeterminados
  	
    	 @font-face{
    	font-family: mabry;
   	 src: url(/imagenes/Mabry-Pro-Medium.ttf);
		}
		h1,h2,h3,h4,h5,h6{
    	font-family: "mabry";
		}

		header{
    	display: flex;
    	justify-content: space-between;
    	height: 60px;
    	align-items: center;
    	padding: 10px;
    	margin-right: 80px;
   
- en la carpeta de imagenes se encuentra la tipografia de deezer (mabry) en archivo .ttf



###End

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">
    <title>Pantallas</title>
    <link rel="stylesheet" href="Styles.css">
</head>
<body>
    <div class="ContainerMain">
        <nav>
            <img src="./images/logo1.png" alt="Logo">
            <a href="./Cuentas.html">Inicio</a>
            <a href="./Soporte.html">Soporte Técnico</a>
            <a href="./Login.html">¿Quieres Trabajar con Nosotros?</a>
        </nav>
    </div>
    <h2>Siguenos en nuestras redes sociales</h2>
    <div class="botones-redessociales">
      
        <a href="https://www.youtube.com/watch?v=eZxjWtmtbM0" target="_blank" class="boton">
            <img src="./Images/wasap.png" alt="Botón 1">
        </a>
    
        <a href="https://www.youtube.com/watch?v=eZxjWtmtbM0" target="_blank" class="boton">
            <img src="./Images/faceboock.png" alt="Botón 2">
        </a>
       
        <a href="https://www.youtube.com/watch?v=eZxjWtmtbM0" target="_blank" class="boton">
            <img src="./Images/instagram.png" alt="Botón 3">
        </a>
    </div>
    <hr>

    <h2>Pantallas disponibles</h2>

    <h3>MAS VENDIDOS</h3>

    <div class="CUENTAS">
        
        <div class="card">
            <img src="./Images/nefli.jpeg" alt="">
            <p>Netflix</p>
            <h3 class="cancel">24.900</h3>
            <h3>11.900</h3>
            <label for="modal-toggle-1" class="open-modal">Agregar</label>
        </div>
        <div class="card">
            <img src="/Images/Disney.jpeg" alt="">
            <p>Disney</p>
            <h3 class="cancel">22.900</h3>
            <h3>7.900</h3>
            <label for="modal-toggle-2" class="open-modal">Agregar</label>
        </div>
        <div class="card">
            <img src="./Images/pipol.png" alt="">
            <p>YouTube</p>
            <h3 class="cancel">29.900</h3>
            <h3>8.500</h3>
            <label for="modal-toggle-3" class="open-modal">Agregar</label>
        </div>
        <div class="card">
            <img src="./Images/spotify.jpeg" alt="">
            <p>Spotify</p>
            <h3 class="cancel">16.900</h3>
            <h3>3.500</h3>
            <label for="modal-toggle-4" class="open-modal">Agregar</label>
        </div>

        <div class="card">
            <img src="./Images/IPTV.jpeg" alt="">
            <p>IPTV</p>
            <h3 class="cancel">19.900</h3>
            <h3>6.500</h3>
            <label for="modal-toggle-5" class="open-modal">Agregar</label>
        </div>

        <div class="card">
            <img src="./Images/crunchy.png" alt="">
            <p>Crunchyroll</p>
            <h3 class="cancel">12.900</h3>
            <h3>3.500</h3>
            <label for="modal-toggle-6" class="open-modal">Agregar</label>
        </div>

        <div class="card">
            <img src="./Images/max.jpeg" alt="">
            <p>Max</p>
            <h3 class="cancel">22.900</h3>
            <h3>7.500</h3>
            <label for="modal-toggle-7" class="open-modal">Agregar</label>
        </div>
        

        <div class="card">
            <img src="./Images/prime.jpeg" alt="">
            <p>Prime</p>
            <h3 class="cancel">14.900</h3>
            <h3>4.500</h3>
            <label for="modal-toggle-8" class="open-modal">Agregar</label>
        </div>
        

        <div class="card">
            <img src="./Images/paramount.png" alt="">
            <p>Paramount</p>
            <h3 class="cancel">19.900</h3>
            <h3>6.500</h3>
            <label for="modal-toggle-9" class="open-modal">Agregar</label>
        </div>

        <div class="card">
            <img src="./Images/maji.png" alt="">
            <p>Magis</p>
            <h3 class="cancel">10.000</h3>
            <h3>2.500</h3>
            <label for="modal-toggle-10" class="open-modal">Agregar</label>
        </div>
        
        
    </div>
    
    <input type="checkbox" id="modal-toggle-1" class="modal-toggle" hidden>
    <div class="modal">
        <label for="modal-toggle-1" class="modal-overlay"></label>
        <div class="modal-content">
            <img src="./Images/nefli.jpeg" alt="">
            <p>Netflix</p>
            <input type="number" id="months" min="1" max="3" value="1">
            <button onclick="closeModal('modal-toggle-1')">Confirmar</button>
        </div>
    </div>
    
    <input type="checkbox" id="modal-toggle-2" class="modal-toggle" hidden>
    <div class="modal">
        <label for="modal-toggle-2" class="modal-overlay"></label>
        <div class="modal-content">
            <img src="/Images/Disney.jpeg" alt="">
            <p>Disney</p>
            <input type="number" id="months" min="1" max="3" value="1">
            <button onclick="closeModal('modal-toggle-2')">Confirmar</button>
        </div>
    </div>
    
    <input type="checkbox" id="modal-toggle-3" class="modal-toggle" hidden>
    <div class="modal">
        <label for="modal-toggle-3" class="modal-overlay"></label>
        <div class="modal-content">
            <img src="./Images/pipol.png" alt="">
            <p>YouTube</p>
            <input type="number" id="months" min="1" max="3" value="1">
            <button onclick="closeModal('modal-toggle-3')">Confirmar</button>
        </div>
    </div>
    
    <input type="checkbox" id="modal-toggle-4" class="modal-toggle" hidden>
    <div class="modal">
        <label for="modal-toggle-4" class="modal-overlay"></label>
        <div class="modal-content">
            <img src="./Images/spotify.jpeg" alt="">
            <p>Spotify</p>
            <input type="number" id="months" min="1" max="3" value="1">
            <button onclick="closeModal('modal-toggle-4')">Confirmar</button>
        </div>
    </div>
    
    <input type="checkbox" id="modal-toggle-5" class="modal-toggle" hidden>
    <div class="modal">
        <label for="modal-toggle-5" class="modal-overlay"></label>
        <div class="modal-content">
            <img src="./Images/IPTV.jpeg" alt="">
            <p>IPTV</p>
            <input type="number" id="months" min="1" max="3" value="1">
            <button onclick="closeModal('modal-toggle-5')">Confirmar</button>
        </div>
    </div>

    <input type="checkbox" id="modal-toggle-6" class="modal-toggle" hidden>
    <div class="modal">
        <label for="modal-toggle-6" class="modal-overlay"></label>
        <div class="modal-content">
            <img src="./Images/crunchy.png" alt="">
            <p>Crunchyroll</p>
            <input type="number" id="months" min="1" max="3" value="1">
            <button onclick="closeModal('modal-toggle-6')">Confirmar</button>
        </div>
    </div>

    <input type="checkbox" id="modal-toggle-7" class="modal-toggle" hidden>
    <div class="modal">
        <label for="modal-toggle-7" class="modal-overlay"></label>
        <div class="modal-content">
            <img src="./Images/max.jpeg" alt="">
            <p>Max</p>
            <input type="number" id="months" min="1" max="3" value="1">
            <button onclick="closeModal('modal-toggle-7')">Confirmar</button>
        </div>
    </div>


    <input type="checkbox" id="modal-toggle-8" class="modal-toggle" hidden>
    <div class="modal">
        <label for="modal-toggle-8" class="modal-overlay"></label>
        <div class="modal-content">
            <img src="./Images/prime.jpeg" alt="">
            <p>Prime</p>
            <input type="number" id="months" min="1" max="3" value="1">
            <button onclick="closeModal('modal-toggle-8')">Confirmar</button>
        </div>
    </div>

    <input type="checkbox" id="modal-toggle-9" class="modal-toggle" hidden>
    <div class="modal">
        <label for="modal-toggle-9" class="modal-overlay"></label>
        <div class="modal-content">
            <img src="./Images/paramount.png" alt="">
            <p>Paramount</p>
            <input type="number" id="months" min="1" max="3" value="1">
            <button onclick="closeModal('modal-toggle-9')">Confirmar</button>
        </div>
    </div>


    <input type="checkbox" id="modal-toggle-10" class="modal-toggle" hidden>
    <div class="modal">
        <label for="modal-toggle-9" class="modal-overlay"></label>
        <div class="modal-content">
            <img src="./Images/maji.png" alt="">
            <p>Paramount</p>
            <input type="number" id="months" min="1" max="3" value="1">
            <button onclick="closeModal('modal-toggle-10')">Confirmar</button>
        </div>
    </div>
    
    
    <script>
        // Función para cerrar el modal al hacer clic en el botón
        function closeModal(modalId) {
            document.getElementById(modalId).checked = false;
        }
    </script>





<!-- Checkbox oculto para controlar el estado del popup -->
<input type="checkbox" id="toggleCartPopup" class="cart-checkbox">

<!-- Carrito -->
<div class="shopping-cart">
    <label for="toggleCartPopup">
        <img src="./Images/carrito2.png" alt="Carrito de Compras">
    </label>
</div>

<!-- Ventana emergente -->
<div class="cart-popup">
    <div class="cart-popup-content">
        <h2>Tu Carrito</h2>
        <p>No hay productos en el carrito.</p>
        <label for="toggleCartPopup" class="close-popup">Cerrar</label>
    </div>
</div>

<hr>

<div class="ofertas-bomba">
    <a href="https://www.youtube.com/watch?v=eZxjWtmtbM0" target="_blank" class="oferta-imagen">
        <img src="./images/Carrito.png" alt="Icono de Ofertas Bomba">
    </a>
    <div class="oferta-texto">
        <h2>Ofertas Bomba</h2>
        <p>
            Algunas veces a nuestros administradores les sobran algunas pantallas disponibles, gracias a esto manejamos un apartado de ofertas con precios aún más competitivos.
            <strong>CONOCE NUESTRAS OFERTAS. </strong>
            (precione la imagen)
        </p>
    </div>
</div>

<hr>

<div class="quienes-somos">
<div class="somos-texto">
    <h2>¿Quiénes somos?</h2>
    <p>
        Una empresa que facilita la compra y venta de pantallas de streaming de diversas plataformas como Netflix, Disney+, Amazon Prime, Spotify, entre otras. 
        El objetivo principal es que los usuarios puedan seleccionar el servicio que desean adquirir de manera rápida, sencilla y con precios más accesibles para el público.
    </p>
</div>
<div class="somos-imagen">
    <img src="./images/logo.png" alt="Icono de Quiénes Somos">
</div>
</div>
</div>




</body>
</html>

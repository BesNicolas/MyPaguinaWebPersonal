/* RESETEO GENERAL */
* {
    margin: 0; /* Elimina márgenes por defecto */
    padding: 0; /* Elimina relleno por defecto */
    box-sizing: border-box; /* Hace que el padding y borde no aumenten el tamaño del elemento */
    font-family: "Roboto Condensed", sans-serif; /* Fuente predeterminada para toda la página */
}

html, body {
    height: 100%; /* Hace que el html y body ocupen toda la altura de la ventana */
    background: linear-gradient(to bottom, #314e45 10%, #418576 100%); /* Fondo degradado de arriba hacia abajo */
    color: white; /* Color de texto por defecto */
}

a {
    text-decoration: none; /* Quita el subrayado de los links */
    color: inherit; /* El color del enlace será el mismo que el del texto normal */
}

img {
    max-width: 100%; /* Las imágenes no serán más grandes que su contenedor */
    height: auto; /* Mantiene la proporción original de la imagen */
}

/* Fuente especial aplicada manualmente (no usada directamente aquí, por si la necesitas) */
.special-gothic-expanded-one-regular {
    font-family: "Special Gothic Expanded One", sans-serif;
    font-weight: 400;
    font-style: normal;
}

/* ========================= */
/* ======== HEADER ========= */
/* ========================= */
header {
    position: fixed; /* El header queda fijo arriba aunque hagas scroll */
    top: 0;
    right: 0;
    width: 100%; /* Ocupa todo el ancho de la pantalla */
    display: flex; /* Usa flexbox para alinear elementos */
    justify-content: space-between; /* Deja espacio entre el nombre y los contactos */
    align-items: center; /* Centra verticalmente los elementos */
    padding: 20px 5%; /* Espaciado interno arriba/abajo 20px, izquierda/derecha 5% */
    background: transparent; /* Fondo transparente */
    z-index: 100; /* Se asegura de estar arriba de otros elementos */
}

/* Estilos para el nombre principal */
.titulo {
    font-size: 48px; /* Tamaño grande del nombre */
    font-family: "Special Gothic Expanded One", sans-serif; /* Fuente especial para destacar */
}

/* Contenedor de los íconos de contacto */
.logos {
    display: flex; /* Flexbox para acomodar íconos en fila */
    gap: 50px; /* Separación entre íconos */
    justify-content: center; /* Centrar los íconos */
    font-size: 30px;
    font-weight: 600;
    width: 200px; /* Ancho máximo del contenedor */
}

/* Texto "Contactame como prefieras" */
.contactame.mi {
    font-size: 20px;
}

/* ========================= */
/* ===== HERO SECTION ====== */
/* ========================= */
.HERO {
    min-height: calc(100vh - 100px); /* Ocupa toda la pantalla menos el alto del header */
    display: flex; /* Flexbox para acomodar los elementos lado a lado */
    justify-content: center; /* Centra horizontalmente */
    align-items: center; /* Centra verticalmente */
    gap: 2rem; /* Espacio entre las cajas */
    padding: 100px 2rem; /* Espaciado interno */
    flex-wrap: wrap; /* Permite que se acomoden en varias filas si no entran en una */
}

/* Caja de imagen */
.hero-img {
    flex: 0 1 250px; /* No crecerá más de 250px */
    text-align: center; /* Centrar la imagen dentro del contenedor */
}

.hero-img img {
    width: 200px; /* Ancho fijo de la imagen */
    height: 200px; /* Alto fijo de la imagen */
    object-fit: cover; /* Ajusta la imagen recortando sin deformar */
    border-radius: 50%; /* Hace la imagen redonda */
    border: 4px solid white; /* Borde blanco alrededor */
    box-shadow: 0 4px 12px rgba(240, 239, 239, 0.2); /* Sombra ligera */
}

/* Caja de presentación de texto y habilidades */
.hero-text, .skills-box {
    flex: 1 1 300px; /* Crece de forma proporcional hasta 300px */
    background: white; /* Fondo blanco */
    color: #2c3e50; /* Texto oscuro */
    padding: 2rem; /* Espaciado interno */
    border-radius: 20px; /* Bordes redondeados */
    box-shadow: 0 8px 24px rgb(7, 2, 2); /* Sombra oscura para destacar */
    max-width: 400px; /* No serán más anchas que 400px */
}

/* Título de habilidades */
.skills-box h3 {
    margin-bottom: 1rem; /* Espacio debajo del título */
    font-size: 48px; /* Tamaño grande */
    color: #0b2c4d; /* Azul oscuro */
}

/* Lista de habilidades */
.skills-box ul {
    list-style-type: disc; /* Viñetas en forma de círculo */
    padding-left: 1.5rem; /* Sangría a la izquierda */
    color: #0b2c4d; /* Color azul oscuro */
    font-size: 1.1rem; /* Tamaño un poco más grande */
}

/* Título en la presentación */
.hero-text h5 {
    margin-bottom: 1rem;
    font-size: 48px;
}

/* Texto descriptivo */
.hero-text {
    list-style-type: disc; /* (Esto realmente no afecta en divs, sería para listas) */
    padding-left: 1.5rem;
    color: #0b2c4d;
    font-size: 1.1rem;
}

/* ======== RESPONSIVE ===== */
@media (max-width: 768px) {
    .HERO {
        flex-direction: column; /* En pantallas pequeñas pone los elementos uno debajo del otro */
        align-items: center; /* Centra los elementos */
        padding: 120px 1rem; /* Más espacio arriba para el header fijo */
    }

    .hero-text, .skills-box {
        max-width: 90%; /* Las cajas ocupan el 90% del ancho en móviles */
    }
}

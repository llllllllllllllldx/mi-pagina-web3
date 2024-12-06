/* Estilos generales */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f7e7e5;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    color: #333;
}

.container {
    text-align: center;
    background-color: #fff;
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.1);
    width: 80%;
    max-width: 500px;
}

h1 {
    font-size: 2.5em;
    color: #e74c3c;
    margin-bottom: 20px;
}

#mensaje {
    font-size: 1.5em;
    color: #2c3e50;
    margin-bottom: 30px;
}

.btn {
    background-color: #2ecc71;
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
    font-size: 1.2em;
    margin: 10px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.btn:hover {
    background-color: #27ae60;
}

/* Animación para el botón "No" que se mueve por la pantalla */
#noButton {
    position: relative;
}

/* Estilos para ocultar los botones después de aceptar */
#siButton, #noButton {
    display: inline-block;
}

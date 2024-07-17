# Proyecto de Cifrado en Figma

## Descripción
Este proyecto proporciona una herramienta de cifrado dentro de Figma, utilizando JavaScript para encriptar cualquier información que el usuario ingrese. La herramienta permite cifrar y descifrar texto, haciendo uso de un algoritmo de cifrado personalizado.

## Instalación
Para instalar y configurar este plugin de cifrado en Figma, sigue estos pasos:

1. **Clonar el repositorio**:
   ```sh
   git clone https://github.com/usuario/nombre-del-proyecto.git
Pagina: https://www.figma.com/design/5sFzfUlMwjZt3Nv5UqE0aH/Alura-Challenge---Desaf%C3%ADo-1--ElizArtund?node-id=0-1&m=dev 
codigo: 
function cifrarTexto(texto) {
    const key = 3; // Clave de cifrado
    let resultado = '';

    for (let i = 0; i < texto.length; i++) {
        let charCode = texto.charCodeAt(i) + key;
        resultado += String.fromCharCode(charCode);
    }

    return resultado;
}

function descifrarTexto(textoCifrado) {
    const key = 3; // Clave de cifrado
    let resultado = '';

    for (let i = 0; i < textoCifrado.length; i++) {
        let charCode = textoCifrado.charCodeAt(i) - key;
        resultado += String.fromCharCode(charCode);
    }

    return resultado;
    Descifrado
Selecciona el texto cifrado que deseas descifrar.
Ejecuta el plugin de descifrado desde Plugins > Development > Tu Plugin de Cifrado.
El texto seleccionado será descifrado y mostrado en su forma original.
Contribuciones
¡Contribuciones son bienvenidas! Para contribuir, sigue estos pasos:

Haz un fork del proyecto.
Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
Realiza los cambios y haz commits (git commit -m 'Añadir nueva funcionalidad').
Haz push a la rama (git push origin feature/nueva-funcionalidad).
Crea un Pull Request.
}

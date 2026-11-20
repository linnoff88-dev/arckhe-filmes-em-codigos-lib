# Películas en código

![El mismo templo junto al mar pasa de un dibujo de líneas a una pintura y a un paisaje realista.](guia/assets/banner.jpg)

[PT](README.md) · [EN](README.en.md) · [ES](README.es.md)

## Qué es

Quieres cambiar un detalle de la película y conservar lo que ya quedó bien. Esta biblioteca muestra cómo la IA puede escribir las instrucciones que dibujan cada imagen. Si tienes curiosidad y nunca has programado, empieza por una demostración y luego abre el proyecto para descubrir cómo hizo esa escena su autor. Para explorar, basta con el navegador.

[Abrir la guía](https://inematds.github.io/filmes-em-codigos-lib/guia/es/) · [Bibliotecas de estilos y películas en código](https://inematds.github.io/filmes-em-codigos-lib/guia/es/#biblioteca) · [Alto realismo en código](https://inematds.github.io/filmes-em-codigos-lib/guia/es/#realismo)

## El proceso, de principio a fin

1. Abres la guía, eliges estilo o alto realismo y ves una demostración.
2. Abres el repositorio del autor, la página que guarda los archivos del proyecto. Si quieres ayuda para leer el código, pega la solicitud de abajo en tu asistente junto con la dirección del proyecto.
3. El asistente explica cómo aparece el detalle en el fotograma. Compruebas la explicación en la película y en el código indicado.
4. Para crear tu escena, eliges una referencia. El asistente escribe el programa, el motor calcula un fotograma y comparas el resultado con la referencia antes de aprobar la secuencia.
5. El motor guarda los fotogramas aprobados y el programa de montaje combina los fotogramas con el audio.

> Explica cómo el autor de este proyecto dibujó un fotograma. Elige un detalle que pueda reconocer en la película y muéstrame dónde aparece en el código.

---

## Instalación técnica

Para ver la biblioteca en tu computadora, usa Git y Python 3. En una terminal, clona el proyecto, entra en su carpeta e inicia el servidor. Luego abre la dirección que aparece abajo.

```sh
git clone https://github.com/inematds/filmes-em-codigos-lib.git
cd filmes-em-codigos-lib
python3 -m http.server 8000
```

[localhost:8000/guia/es/](http://localhost:8000/guia/es/)

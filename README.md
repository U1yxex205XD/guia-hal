# HAL S3201 de estudio

Guía interactiva del simulador de paciente HAL S3201 de Gaumard: fichas por sistema con fragmentos de video, monitor animado con casos de ejemplo y modo examen. Mismo estilo que "Célula 3D de estudio".

Para publicarla en GitHub Pages sube `index.html`, `hal.gltf.json`, la carpeta `clips/` y la carpeta `img/` a un repositorio y activa Pages. Ábrela desde GitHub Pages o un servidor local; con doble clic algunos navegadores no cargan los videos.

Los fragmentos de video salen de los videos de demostración de Gaumard de la carpeta del proyecto (Hal 1 a Hal 15).

El maniquí 3D (`hal.gltf.json`, glTF con texturas incrustadas) se generó con Meshy AI (Text-to-3D). El visor usa three.js desde jsDelivr; si WebGL no está disponible, la guía vuelve al dibujo plano.

Subtítulos: cada fragmento tiene subtítulos en español incrustados en la página (objeto SUBS). La carpeta `subs/` guarda los mismos subtítulos como .vtt y la transcripción en inglés (`transcripciones-en.json`), hecha con Whisper small.en; la traducción se revisó a mano.

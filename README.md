# IA y lenguaje: actividades interactivas

Repositorio de actividades interactivas para entender cómo las redes neuronales aprenden a partir de textos. Están pensadas para la materia **IA para a Sociedade** de 4.º de ESO.

Las actividades funcionan directamente en el navegador: no hace falta instalar nada ni crear cuentas.

## Actividades

| Actividad | Descripción | Enlace |
|---|---|---|
| **Del texto al número** · ¿Cómo lee una IA? | Cómo un modelo de lenguaje convierte las palabras en números: codificación de letras, tokens, redes neuronales recurrentes y embeddings. | [Abrir la actividad](https://susanaoubina.github.io/llm/del-texto-al-numero-V4.html) |

## Del texto al número

A lo largo de seis misiones, el alumnado recorre el camino que sigue una IA para convertir el lenguaje en números:

1. **Las neuronas solo entienden números.** Del código Unicode a la codificación one-hot: por qué la forma de convertir las letras en números importa.
2. **Las tres generaciones.** Laboratorio para trocear frases letra a letra, palabra a palabra y en tokens.
3. **Entrena una red recurrente.** Una red neuronal recurrente real que aprende a escribir letra a letra en el propio navegador, con su curva de error, su memoria y un control de creatividad (temperatura).
4. **Reto: el tokenizador de verdad.** Comparar con el tokenizador de OpenAI cuántos tokens gastan el inglés, el español y el gallego.
5. **El mapa de las palabras.** Un mapa de embeddings simplificado para descubrir por qué las palabras con varios significados quedan entre varios grupos.
6. **Exploradores del Embedding Projector.** Explorar un embedding real de 20.000 palabras en español.

Cada misión incluye preguntas de respuesta múltiple con explicación inmediata y un marcador de aciertos. Además, se conecta con los contenidos del libro de la materia: redes neuronales, aprendizaje supervisado y no supervisado, espacio latente y Proyecto Nós.

### Duración orientativa

Tres sesiones de 50 minutos:

- **Sesión 1:** misiones 1 y 2.
- **Sesión 2:** misiones 3 y 4.
- **Sesión 3:** misiones 5 y 6.

### Herramientas externas

- [Tokenizador de OpenAI](https://platform.openai.com/tokenizer) (misión 4)
- [Embedding Projector en español](https://projector.tensorflow.org/?config=https://ecraft2learn.github.io/ai/word-embeddings/es/projector.json) (misión 6)

### Notas

- Las misiones 1, 2 y 5 usan simulaciones educativas simplificadas. La red de la misión 3 es una red recurrente real.
- La página no guarda datos: al recargarla se reinician las respuestas y la red entrenada.
- El vídeo introductorio se ve incrustado cuando la página se abre desde la dirección web. Si se abre el archivo HTML con doble clic, aparece un enlace para verlo en YouTube.

## Créditos

Creado por **Susana Oubiña Falcón** y **Claude (Opus 5.5)**.
Material educativo para la materia de **IA para a Sociedade** · 4.º ESO.

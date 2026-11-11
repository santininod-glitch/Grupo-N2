# 08 · Validación

**DRIVE.ON** · Valentina Pineda, Samuel Pinzón y Santiago Niño

En este documento describimos cómo validamos el prototipo de DRIVE.ON: un dron autónomo con piezas impresas en 3D, acompañado de una app que recibe el pedido, le asigna un dron y permite seguir la entrega en tiempo real. Comparamos cinco métodos de testeo Lean UX, elegimos el más adecuado para nuestra etapa y presentamos el plan de la prueba.

## 1. Comparación de métodos de testeo Lean UX

| Método | Qué valida | Cómo se aplica | Ventaja | Limitación | ¿Aplica a nuestro prototipo? |
|---|---|---|---|---|---|
| Prueba de usabilidad | Si el usuario entiende y completa tareas con el producto sin ayuda | Se le piden tareas concretas a una persona mientras el equipo observa y registra errores, tiempos y comentarios | Muestra con claridad dónde el usuario se confunde o se bloquea | Necesita un prototipo que funcione o se vea completo; con un modelo 3D sin funciones el usuario no puede completar el flujo real | Parcialmente: sirve para la app, pero el dron aún no opera |
| Mago de Oz | Si la solución resuelve el problema y si el usuario confía en ella, antes de construir la tecnología | El usuario interactúa con el prototipo como si fuera real, mientras el equipo opera manualmente, "detrás de la cortina", las respuestas del sistema | Permite probar la experiencia completa de un sistema autónomo sin desarrollarlo | Requiere coordinar al equipo y ensayar para que la simulación sea creíble; no mide el rendimiento técnico real del dron | **Sí**: el dron impreso en 3D y la app se simulan con apoyo del equipo |
| Test A/B | Cuál de dos versiones de una misma pieza funciona mejor | Se muestran dos variantes a grupos distintos y se comparan resultados | Aporta datos comparables entre alternativas | Requiere dos versiones definidas y muchos participantes para ser confiable | No: solo tenemos una versión (v0.1) y un participante por sesión |
| Prueba de 5 segundos | Si el mensaje o la pantalla principal se entiende de un vistazo | Se muestra una pantalla durante cinco segundos y luego se pregunta qué recuerda y qué entendió | Es rápida y barata para evaluar claridad visual | Solo evalúa la primera impresión, no el uso ni la entrega | No: no valida el recorrido del pedido ni el desempeño del dron |
| Puerta falsa | Si existe interés real en una funcionalidad o servicio | Se ofrece el servicio mediante un botón, anuncio o página que aún no existe y se mide cuántas personas lo eligen | Mide la demanda antes de construir | No evalúa la experiencia de uso ni la entrega física; depende de tráfico o volumen de usuarios | No: nuestra hipótesis trata de la entrega a tiempo y en buen estado, no del interés por el servicio |

## 2. Método elegido y por qué

Elegimos **Mago de Oz**, porque nuestro dron aún no vuela por sí solo y este método nos permite probar la experiencia completa de una entrega autónoma con el modelo impreso en 3D.
Así comprobamos si el vendedor confía en el sistema, entiende el flujo de pedido, asignación y seguimiento, y si la entrega simulada cumple lo que esperamos (a tiempo, sin derrames y en buen estado).
Con lo aprendido decidimos qué ajustar en el diseño del dron y de la app antes de invertir en una versión funcional.

## 3. Plan de testeo

**Hipótesis a validar**

> Creemos que el administrador del restaurante podrá entregar los pedidos a tiempo y sin comida fría, sin depender de domiciliarios en moto, si usa nuestro prototipo: una app que recibe el pedido, le asigna un dron autónomo y permite seguir la entrega en tiempo real.

**Participante:** un vendedor, quien gestiona pedidos de delivery en el área de ventas de un restaurante y representa al usuario del proceso. Realizamos una sesión individual de unos 20 minutos.

**Cómo funciona la simulación:** el participante recibe un pedido de prueba en la app y lo asigna al dron impreso en 3D. Un integrante del equipo, fuera de su vista, cambia las pantallas de la app y desplaza el dron por una ruta marcada hasta el punto de entrega. El participante cree que el sistema responde por sí solo.

**Tareas**

1. Recibir un pedido de prueba en la app y asignarle el dron.
2. Cargar el pedido en el compartimento del dron y autorizar el despacho.
3. Seguir la entrega en la app y confirmar la recepción en el punto de entrega.

**Métrica de éxito**

Consideramos validada la hipótesis si se cumple todo lo siguiente:

- El participante completa las 3 tareas sin ayuda del equipo.
- El pedido de prueba llega al punto de entrega sin derramarse.
- El tiempo de la entrega simulada es menor que el tiempo de referencia de un domiciliario en moto para la misma ruta, calculado previamente por el equipo con una aplicación de mapas.
- El participante considera que el pedido llegó en buen estado y sin enfriarse más de lo normal.
- El participante califica con 4 o más, en una escala de 1 a 5, su confianza en entregar pedidos con este sistema.

**Lugar:** Universidad EAN.

**Fecha:** viernes 6 de noviembre.

**Materiales**

- Modelo del dron impreso en 3D con compartimento de carga.
- Pedido de prueba (recipiente cerrado con comida o líquido).
- Pantallas de la app simuladas en un celular, y un segundo celular para el equipo.
- Ruta de entrega marcada, con punto de salida y punto de entrega.
- Cronómetro.
- Cámara para grabar la sesión.
- Formato de consentimiento y formato de observación.
- Cuestionario breve de cierre.

**Responsables por rol**

| Rol | Responsable | Función |
|---|---|---|
| Facilitador | Samuel Pinzón | Explica la actividad, da las tareas y hace las preguntas de cierre sin sugerir respuestas |
| Mago (operador de la simulación) | Santiago Niño | Cambia las pantallas de la app y mueve el dron por la ruta |
| Observador y registro | Valentina Pineda | Toma notas, mide tiempos y anota las frases textuales del participante |
| Grabación del video | Valentina Pineda y Santiago Niño | Graban la sesión y recopilan el material para el video |

## 4. Resultados

### Qué observamos

### Qué dijo el usuario

### Qué vamos a cambiar

Video: [[ENLACE]
](https://youtu.be/Jpeq9opt8VI?si=sw42DiArQ-_4AYIE)

# nvestigación: ¿esto ya existe? ¿quién lo dice?

**Autor:** Guillermo Barrios Muñoz  
**Fecha:** 20 de septiembre de 2026  
**Ideas analizadas:** ver [ideas-proyecto.md](ideas-proyecto.md).

---

## Parte 1. Un ejemplo que ya existe, por cada idea

### Idea 1: Alerta Jitomate

- **Qué encontré:** SensorPush HT.w, un sensor comercial de temperatura y humedad.
- **Enlace:** [SensorPush HT.w](https://www.sensorpush.com/products/p/ht-w).
- **Qué hace:** Registra las condiciones y permite consultarlas en el teléfono. Con el equipo adicional G1 permite recibir avisos a distancia por internet.
- **Por qué no resuelve mi caso:** Puede servir, pero necesita comprar el sensor y el G1 para el monitoreo remoto. Quiero buscar una alternativa de menor costo y construirla como proyecto escolar.

### Idea 2: NutriJitomate

- **Qué encontré:** Bluelab Guardian Monitor Wi-Fi.
- **Enlace:** [Bluelab Guardian Monitor Wi-Fi](https://global.bluelab.com/products/bluelab-guardian-monitor-wi-fi).
- **Qué hace:** Mide pH, conductividad y temperatura de la solución nutritiva; permite consultar datos y recibir alertas en una aplicación.
- **Por qué no resuelve mi caso:** No informa por separado cuánto calcio, potasio y magnesio hay. Sirve como referencia para la versión básica, pero no cubre la idea completa.

### Idea 3: Campo Directo

- **Qué encontré:** Smattcom, una aplicación de compraventa de productos agroalimentarios.
- **Enlace:** [Smattcom: Compra o Vende](https://ayuda.smattcom.com/compra-vende).
- **Qué hace:** Permite publicar ofertas, contactar compradores y vendedores, y negociar directamente.
- **Por qué no resuelve mi caso:** Sí podría resolver parte del problema. Falta comprobar si hay productores y compradores de mi comunidad que la utilicen; no he demostrado que haga falta otra aplicación.

---

## Parte 2. Fuentes de la idea que elegí

### Fuente 1

|Campo|Contenido|
|---|---|
|Autor u organización|Richard L. Snyder y J. Paulo de Melo-Abreu; FAO.|
|Título|Frost protection: fundamentals, practice, and economics. Volumen 1, capítulo 5.|
|Año|2005.|
|Enlace|[Consultar capítulo sobre predicción y seguimiento](https://www.fao.org/4/y7223e/y7223e0b.htm).|
|Tipo|Sitio institucional / publicación técnica.|
|Por qué le creo|Identifica a sus autores, incluye referencias y está publicada por la FAO.|
|Qué dato me dio|Los pronósticos regionales deben ajustarse a las condiciones locales; medir cerca del cultivo ayuda a vigilar una noche fría.|

### Fuente 2

|Campo|Contenido|
|---|---|
|Autor u organización|Open-Meteo.|
|Título|Free Weather API.|
|Año|Sin fecha visible; consultado el 20 de septiembre de 2026.|
|Enlace|[Open-Meteo](https://open-meteo.com/).|
|Tipo|Sitio oficial / documentación técnica.|
|Por qué le creo|Explica los modelos utilizados y las condiciones de acceso a su servicio.|
|Qué dato me dio|Ofrece pronósticos por coordenadas y acceso gratuito limitado para uso no comercial. Son datos de modelos, no lecturas directas del invernadero.|

### Fuente 3

|Campo|Contenido|
|---|---|
|Autor u organización|Telegram.|
|Título|Bots: An introduction for developers.|
|Año|Sin fecha visible; consultado el 20 de septiembre de 2026.|
|Enlace|[Documentación de bots de Telegram](https://core.telegram.org/bots).|
|Tipo|Documentación técnica.|
|Por qué le creo|Es la documentación oficial del servicio, dirigida a quienes desarrollan sus bots.|
|Qué dato me dio|Su plataforma de bots es gratuita y permite integrar avisos sin crear una aplicación móvil propia.|

---

## Parte 3. Qué haría distinto

Me enfocaría en productores de jitomate en invernadero de mi comunidad.  
Mediría la temperatura exterior y usaría 2 °C como umbral de aviso del proyecto.  
Combinaría un sensor local con pronósticos disponibles, diferenciando ambos datos.  
Buscaría reducir costos con materiales reutilizados y piezas pequeñas.  
Usaría una aplicación existente para enviar los avisos.

## Parte 4. Qué me falta averiguar

- ¿Cómo mantener una alarma local cuando falle internet y recuperar los avisos al reconectarse?
- ¿Qué estación cercana ofrece datos útiles y cuánto costarán realmente los componentes y la fabricación?
- ¿Qué diferencia hay entre el pronóstico y la temperatura exterior medida junto al invernadero?

---

## Declaración de uso de IA

- **Herramienta utilizada:** ChatGPT de OpenAI, modelo GPT-6 Astra Pro.
- **Qué le pedí:** Buscar ejemplos y fuentes, comprobar enlaces y organizar la investigación.
- **Qué modifiqué o rechacé de su respuesta, y por qué:** Pedí un enfoque de bajo costo. También precisé que el proyecto debe vigilar la temperatura exterior del invernadero.
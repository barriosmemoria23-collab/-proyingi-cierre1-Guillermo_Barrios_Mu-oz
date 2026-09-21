# Tres ideas de proyecto

**Autor:** Guillermo Barrios Muñoz  
**Fecha:** 20 de septiembre de 2026

---

## Criterios de viabilidad

Una idea es viable para esta materia si cumple los cuatro criterios:

1. Atiende un **problema concreto de mi entorno**.
2. Tiene una **parte física fabricable** con impresión 3D, corte láser o router CNC.
3. Usa **al menos un sensor o un actuador** controlado por un microcontrolador pequeño.
4. Lo puede construir un **equipo de principiantes en unas ocho sesiones**, con materiales accesibles.

---

## Idea 1: Alerta Jitomate

**Problema.** En la producción de jitomate en invernadero necesitamos vigilar las bajas de temperatura exterior, especialmente cuando se acerca a los 2 °C. Queremos enterarnos a tiempo sin revisar constantemente el clima.

**A quién le pasa.** A los productores de jitomate en invernadero de mi comunidad, entre quienes me incluyo.

**Dónde lo he visto.** En la producción de jitomate de mi comunidad, donde estamos pendientes del frío exterior. Falta anotar una situación específica que haya observado.

**Cómo funcionaría.**

- **Qué mide o detecta —sensor—:** Un sensor conectado a un ESP32 mediría la temperatura fuera del invernadero.
- **Qué hace con eso —actuador, aviso, pantalla—:** Enviaría avisos al teléfono al llegar a 2 °C o menos. También consultaríamos pronósticos para avisar con anticipación, distinguiéndolos de las mediciones locales.
- **Qué pieza habría que fabricar:** Un soporte ventilado para el sensor y una carcasa impresa en 3D para la electrónica.

Los 2 °C serían el umbral exterior elegido para el proyecto, no una medición de la temperatura interior.

---

## Idea 2: NutriJitomate

**Problema.** Los productores necesitamos conocer mejor las condiciones de nutrición del jitomate. Me interesa revisar calcio, potasio, magnesio, pH y conductividad para dar seguimiento a la fertilización.

**A quién le pasa.** A los productores de jitomate de mi comunidad que necesitan revisar la nutrición de sus cultivos.

**Dónde lo he visto.** La idea surge de la actividad agrícola de mi comunidad. Todavía necesito documentar un caso concreto relacionado con la medición de nutrientes.

**Cómo funcionaría.**

- **Qué mide o detecta —sensor—:** El prototipo inicial mediría pH y conductividad de una solución nutritiva con sensores y un microcontrolador. Medir cada nutriente por separado quedaría pendiente.
- **Qué hace con eso —actuador, aviso, pantalla—:** Mostraría las lecturas en el teléfono y avisaría cuando salieran de los límites establecidos.
- **Qué pieza habría que fabricar:** Una base impresa en 3D para sujetar las sondas y el recipiente de muestra.

---

## Idea 3: Campo Directo

**Problema.** Quiero facilitar el contacto entre productores de jitomate y compradores, para que puedan negociar directamente sin depender necesariamente de intermediarios.

**A quién le pasa.** A los productores de mi comunidad que buscan vender su cosecha y a las personas o negocios que desean comprarles.

**Dónde lo he visto.** La idea surge de la comercialización agrícola de mi comunidad. Falta describir una situación de venta que haya observado personalmente.

**Cómo funcionaría.**

- **Qué mide o detecta —sensor—:** No utilizaría sensores; los usuarios registrarían producto, cantidad, precio y contacto.
- **Qué hace con eso —actuador, aviso, pantalla—:** La aplicación mostraría las publicaciones y permitiría contactar al vendedor.
- **Qué pieza habría que fabricar:** Ninguna en su planteamiento actual; por eso no cumple este requisito de la materia.

---

## Tabla de viabilidad

|Criterio|Idea 1|Idea 2|Idea 3|
|---|---|---|---|
|Problema concreto de mi entorno|Sí|Parcial|Parcial|
|Parte física fabricable|Sí|Sí|No|
|Sensor o actuador|Sí|Sí|No|
|Construible en ocho sesiones por principiantes|Parcial|Parcial|Parcial|
|Qué tan seguro estoy de lo anterior —alto / medio / bajo—|Medio|Bajo|Medio|

## Mi elección

**Idea elegida:** Alerta Jitomate.

**Por qué.** Es la que mejor se ajusta a la necesidad que identifico como productor y a los requisitos de la materia. Incluye un sensor y piezas fabricables. Podemos reducir el alcance a medición y avisos, sin desarrollar una aplicación desde cero.

**Qué todavía no sé.** Falta cotizar si podemos ajustarnos a la meta de $450 a $650 MXN, reutilizando alimentación USB y con Wi-Fi disponible. También debemos confirmar dónde fabricar las piezas y probar las alertas.

---

## Declaración de uso de IA

- **Herramienta utilizada:** ChatGPT de OpenAI, modelo GPT-6 Astra Pro.
- **Qué le pedí:** Organizar mis tres ideas y revisar su viabilidad.
- **Qué modifiqué o rechacé de su respuesta, y por qué:** Aclaré que el jitomate está en invernadero y que los 2 °C corresponden al exterior. Pedí considerar poco presupuesto y separar las propuestas de la investigación.
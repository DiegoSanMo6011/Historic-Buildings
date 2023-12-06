
# Historic Buildings Mod - México Edition
Este repositorio contiene el desarrollo en curso del mod Historic Buildings para City Skylines, enfocado en la inclusión de monumentos históricos de México en el juego, con impacto visual y cambios en el gameplay. A continuación, se presenta un resumen de los avances, ideas y decisiones tomadas hasta el momento.

## Monumentos Seleccionados para Implementación
### Teatro de la República

Ubicación: Centro histórico de Querétaro.
Justificación: Valor histórico y político; promulgación de la Constitución de 1917.
Impacto en el juego: Incremento de cultura y entretenimiento; efectos positivos en comercio y seguridad en ubicaciones céntricas.
Imagen del Teatro de la República

### Ex Convento de San Francisco

Ubicación: Centro histórico de Querétaro.
Justificación: Conjunto arquitectónico del siglo XVI; Patrimonio Cultural de la Humanidad por la UNESCO.
Impacto en el juego: Atracción turística; efectos positivos en felicidad y educación de los ciudadanos.
Imagen del Ex Convento de San Francisco

### Casa de la Corregidora

Ubicación: Centro histórico de Querétaro, Plaza de Armas.
Justificación: Significancia en la Independencia de México; Patrimonio Cultural de la Nación.
Impacto en el juego: Mejora de la identidad y patriotismo; efectos positivos en turismo y economía en zonas históricas.
Imagen de la Casa de la Corregidora

## Proceso de Desarrollo
Inicio del Proyecto: Utilización de Visual Studio y exploración de foros en línea, especialmente el foro CITIES SKYLINES MODDING OPEN DISCUSSION.

Implementación Inicial: Creación de un Asset de prueba mediante el aprendizaje de la generación de assets en el juego.

Selección de Clases y Aprendizaje: Utilización de la clase MonumentAI para definir el tipo de edificio como monumento.

Creación de Asset de Prueba: Se creó un Asset basado en un diseño descargado de la Steam Workshop para verificar la carga y reconocimiento del mod en el juego.

Desafío Actual: Aunque el mod compila y se carga, no genera el edificio en el juego. La siguiente etapa implica la lectura de los .dll, realizando ingeniería inversa con la herramienta dotPeek para entender y modificar las funciones necesarias.

## Resultados

Enlace al Mod: https://steamcommunity.com/sharedfiles/filedetails/?id=3106513088

Enlace al Asset: https://steamcommunity.com/sharedfiles/filedetails/?id=3106514616

 ## Próximos Pasos
 
Ingeniería Inversa con dotPeek: Continuar explorando los .dll del juego utilizando la herramienta dotPeek para identificar las funciones específicas que deben modificarse para lograr la generación exitosa de edificios.

Uso de Modding Tools: Investiga y utiliza las Modding Tools disponibles para facilitar y optimizar el proceso de modificación del código del juego. Esto podría agilizar el desarrollo y mejorar la compatibilidad del mod con futuras actualizaciones del juego.

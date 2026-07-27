# Hola

## Mitre Atlas - Vulnerabilidades en IA

https://atlas.mitre.org/matrices/ATLAS

## Análisis de vulnerabilidades

- La inyección de mensajes: ocurre cuando un atacante anula las instrucciones originales proporcionadas a un modelo. A un chatbot de juegos de rol se le podría indicar que mantenga su personaje y que nunca revele su infraestructura subyacente. La inyección de indicaciones se produce cuando la entrada del usuario se manipula de forma que anula o elude esas instrucciones, lo que provoca que el modelo se comporte de forma indebida, ya sea revelando información confidencial, generando contenido dañino o actuando fuera de su ámbito definido.

- Envenenamiento de datos: es cuando un atacante manipula eldatos de entrenamiento utilizado para construir un modelo de IA, lo que provoca que sus resultados sean incorrectos o sesgados. Tomemos como ejemplo un filtro de spam entrenado con datos de correo electrónico. Si un atacante puede manipular esedatos de entrenamientoAntes de que el modelo esté entrenado, pueden provocar que clasifique erróneamente el correo no deseado como correo legítimo, cegándolo de hecho para que no detecte los correos electrónicos que fue diseñado para identificar.

- El robo de modelos: ocurre cuando un atacante obtiene acceso no autorizado a unAImodelo, ya sea para robar la propiedad intelectual que representa o para usarla con fines maliciosos. Un método consiste en consultar repetidamente el modelo.APIy utilizar los resultados para entrenar un clon que replique su comportamiento, sin necesidad de acceder directamente a los pesos originales.

- La fuga de privacidad: se refiere a la posibilidad de unaAImodelo revelando inadvertidamente información sensible de sudatos de entrenamientoUn modelo entrenado con historiales médicos privados, por ejemplo, podría, bajo las condiciones adecuadas, revelar detalles sobre pacientes reales que nunca se pretendió que fueran accesibles. Esta información no desaparece al finalizar el entrenamiento; queda integrada en los parámetros del modelo.

- La deriva del modelo: se produce cuando su rendimiento se degrada con el tiempo a medida que cambia el entorno en el que fue entrenado. Un modelo entrenado con los patrones de tráfico de red del año pasado puede empezar a tener un rendimiento deficiente a medida que evolucionan las técnicas de ataque. Por eso, monitorizar los modelos implementados no es opcional, sino un requisito de seguridad. La deriva puede pasar desapercibida hasta que el modelo ya esté fallando en producción.

- 

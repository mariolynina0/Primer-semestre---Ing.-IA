# Reporte: Transfer Learning 
## ¿Qué es Tranfer Learning?
El ***transfer learning*** es una técnica de Deep Learning que permite utilizar un modelo que ya ha sido entrenado, para resolver un nuevo problema. En lugar de comenzar desde cero, se utiliza el conocimiento que un modelo ya adquirió al entrenarse con grandes cantidades de datos. Esto permite reducir el tiempo de entrenamiento, la cantidad de datos necesarios y el costo que requeriria normalmente hacerlo de cero. Es aprender algo nuevo basándose en conocimientos previos, lo que hace que este proceso sea mucho más eficiente.
## ¿Qué modelo usaste?
Se utilizo el modelo pre-entrenado de *MobileNetV2*.
Sus principales características son:
 
 - Es ligero y rápido
 - Tiene millones de parámetros ya entrenados con *ImageNet*
 - Está optimizado para diferentes dispositivos

Se eligió este modelo porque permite realizar Transfer Learning de manera rápida sin necesidad de hardware avanzado
## Resultado de la predicción
Se utilizó una imagen de prueba descargada desde internet, era de un perro. El modelo predijo correctamente la clase *golden retriever* con un alto porcentaje de confianza, mayor al noventa porciento. Esto demuestra que el modelo a tiene un conocimiento visual sólido.
## Parámetros congelados vs entrenables
Durante el proceso de *fine-tuning*:

- Se cargó el modelo sin la capa superior (include_top=False)
- Se congelaron las capas base (base.trainable = False)
- Se agregó una nueva cabeza clasificadora

Resultados: Más del 95% de los parámetros quedaron congelados. Menos del 5% fueron entrenables.
Esto permite que el modelo conserve su conocimiento original y solo aprenda lo necesario para la nueva tarea, evitando el problema de *catastrophic forgetting*.
## Aplicaión potencial
El Transfer Learning podría aplicarse en:

- Clasificación de imágenes de productos

- Reconocimiento de objetos en seguridad

- Diagnóstico médico mediante imágenes

Por ejemplo, se podría usar para clasificar tipos de viviendas o detectar características específicas en imágenes inmobiliarias.
## Opinión
Lo más sorprendente de la sesión fue ver cómo un modelo ya entrenado puede adaptarse rápidamente a un nuevo problema con muy pocos datos. Pensaba que entrenar una red neuronal siempre requería muco tiempo y recursos, pero con el *Transfer Learning* se puede trabajar de  manera mucho más eficiente.
### Datos recolectados (CSV sesión 3)
Recolecté un dataset de alquileres con las siguientes variables:

- Zona (ubicación)

- Número de habitaciones

- Precio mensual

- Garantía

Este dataset contiene información de distintas zonas como Centro, Norte, Cala Cala, entre otras. Los precios varían entre 1200 y 3200 Bs, y la garantía generalmente es igual al precio mensual, aunque en algunos casos es menor o cero.

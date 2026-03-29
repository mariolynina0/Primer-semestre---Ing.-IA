# REPORTE TÉCNICO: ALGORITMO DE TIKTOK
## ¿Qué datos recopila el sistema? 
El algoritmo de TikTok recopila mayormente datos de comportamiendo del usuario dentro de su plataforma. No depende tanto de lo que el usuario dice explícitamente, como likes, sino de cómo interactúa con el contenido.
## ¿Cómo genera recomendaciones? 
El *pipeline* que utiliza el sistema de TikTok se basa en la parte de **"para ti"** o ***"for you"***, comienza con un video que se muestra a alrededor de 200 usuarios aleatorios. 

Después, el algoritmo mide el rendimiento del video puesto, señales clave como: la retención; si el video se ve completo, compartido, comentarios y reacciones. Si se logro obtener métricas altas, el video se "distribuye" a más usuarios. Si no, su difusión se detiene.

Posteriormente, el algoritmo empareja los videos con usuarios, combina el perfil del contenido con el historial de comportamiento del usuario. Esto hace que videos donde el usuario nunca buscó aparezcan en su "para ti".

Finalmente, Tiktok genera la secuencia infinita de videos personalizados, optimizada para que mas usuarios se mantengan viendo el contenido.
## ¿Cuál es el objetivo que optimiza?
El objetivo de TikTok al utilizar ese algoritmo, es maximizar el tiempo en el cual alguien permanece viendo el contenido. Para el algoritmo, lo más importante no es el *like* sino cuánto tiempo pasa viendo el contenido.

El sistema busca constantemente mantener la atención del usuario, ofreciendo contenido relevante y atractivo para el usuario en cada momento.
## Un riesgo ético del sistema 
Un riesgo ético relevante, respaldado por investigación reciente, es el impacto negativo en la salud mental de los adolescentes debido a la amplificación de contenido extremo por parte del algoritmo. Un estudio interdisciplinario publicado por **Cambridge University Press** **(Costello et al., 2024)** evidenció que TikTok puede exponer rápidamente a usuarios jóvenes a grandes volúmenes de contenido perjudicial.

Por ejemplo, una investigación del ***Wall Street Journal*** citada en el estudio mostró que cuentas simuladas de usuarios de 13 años recibieron en pocas semanas miles de videos sobre pérdida de peso extrema, incluyendo prácticas poco saludables como consumir menos de 300 calorías al día. Este tipo de exposición constante puede contribuir a problemas como mala imagen corporal, trastornos alimentarios y otros riesgos para la salud mental.

Además, el modelo de negocio basado en publicidad incentiva a las plataformas a maximizar el tiempo de pantalla, incluso si esto implica promover contenido que genere mayor *engagement* aunque sea dañino. Se estima que las redes sociales generan miles de millones de dólares en ingresos publicitarios dirigidos a menores, lo que refuerza estas prácticas.

Esto plantea un dilema ético importante: el algoritmo no solo refleja preferencias, sino que también puede moldearlas activamente, especialmente en usuarios jóvenes vulnerables. Por ello, diversos expertos sugieren la necesidad de regulaciones, auditorías de algoritmos y medidas de protección para menores.

## Opinión Personal
Considero que el algoritmo de TikTok es muy efectivo, porque logra recomendar contenido relevante e importante para el usuario sin necesidad de que lo busque. Esto lo hace muy eficaz en que la experiencia del usuario sea buena.

Sin embargo, también creo que puede ser peligroso, ya que está diseñado para captar y mantener la atención de forma constante. Esto puede llevar a un uso excesivo, a una adicción de la aplicación sin que el usuario se dé cuenta.

En mi opinión, sería importante encontrar un equilibrio donde el algoritmo no solo optimice el tiempo de pantalla, sino también el bienestar del usuario.

## Fuente
Costello et al.,(2024, febrero 12). Algorithms, addiction and adolescent mental health. Cambridge University Press. [Artículo](https://www.cambridge.org/core/journals/american-journal-of-law-and-medicine/article/algorithms-addiction-and-adolescent-mental-health-an-interdisciplinary-study-to-inform-statelevel-policy-action-to-protect-youth-from-the-dangers-of-social-media/EC9754B533553BDD56827CD9E34DFC25)

Ingeniería inversa de Productos IA. (s.f.). [Material de clase de introducción a la IA]. Universidad Privada Boliviana(UPB).

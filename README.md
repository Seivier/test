# Introducción

Durante el verano de 2023 se realizó la practica profesional 2 en la empresa Adventure Chile Spa ,  la cual es una empresa nueva en el área de turismo, su principal producto es la aplicación web Trypo (www.trypo.cl), desarrollada por TecnoApps (https://www.tecnoapps.cl/), la cual es una agencia de viajes online dedicada a actividades outdoor como camping y motorhome.

Trypo fue lanzada al mecado a principios de año, previamente a esto la compañia hizo múltiples contratos con asociados para que estos publicaran sus hostales en el sitio web. Dicha asociación funcionaba de manera rudimentaria donde un encargado en Trypo enviaba correos al contacto de todos los socios solicitando los datos de disponibilidad e inventario. Debido este sistema existieron muchos intersados que no se asociaron porque su hostal funcionaba bien haciendo uso de aplicaciones como AirBnB y Booking, y el integrase con Trypo supondría más problemas que beneficios para ellos.

Esto provocó que al momento de lanzamiento la cantidad de socios no fuera la deseada. Si bien, en el inicio los números de Trypo no fueron decepcionantes, la empresa evalúo que para tener una mayor atracción era necesario aumentar la cantidad de socios. Es por esto que surgió la necesidad de hacer una investigación de las tecnologías y estándares de la industria que permitiera agilizar el proceso de sincronización de inventario y disponibilidad, asi como, integrar a los usuarios de AirBnB y Booking. Es por esto que la empresa buscó a un practicante capaz de realizar dicha tarea.

Es por esto que la presente práctica consistió en realizar una investigación de las posibles soluciones que permitan de implementar las funcionalidades necesarias. Donde en una primera instancia de evalúa la creacion de un sistema propietario, que luego fue descartado por problemas técnicos; y después de esto se buscó empresas que ofrecieran servicios similares con las cuales establecer un contrato de colaboración. En la última parte de la práctica también se identificó las diferencias entre Trypo y la competencia para luego buscar implementar dichas funcionalidades de una forma similar a la anteriormente mencionada.

----

# Problema Abordado

Al inicio de la práctica el equipo de Trypo tenia la problemática de que no contaban con un sistema eficiente y moderno de integración con el resto de aplicaciones del rubro, esto hacia que para una persona quisiear inscribir su hostal en la aplicación tenga sincronizar manualmente la disponibilidad del sitio mediante correos con el equipo. Esto provocaba que diversos dueños no quieran integrase con Trypo, puesto que o ya contaban con un ambiente de trabajo ya establecido y la integración supondría trabajo extra; o trabajan en diversas plataformas por lo que sincronizar manualmente la disponibilidad les resultaría tedios e ineficiente.

El equipo de trabajo reconoce este problema como algo urgente a resolver puesto que como startup necesitan mantenerse vigentes y conseguir la mayor cantidad de clientes posibles para atraer a inversionistas y asi hacer crecer la aplicación. La falta de socios (oferta de experiencias) es uno de los factores que provocaría una caida en el interes por parte del usuario final.


---

# Objetivos de la Práctica

El objetivo principal de la práctica fue encontrar una solución que permita a Adventrue añadir las acracterísitcas a Trypo, para asi aumentar su atractivo. Para conseguir esto el practicante con ayuda del equipo de Trypo realizaron un análisis de carencias de la aplicación que llevo a establecer los siguientes objetivos específicos:

- Un motor de reserva con gestor de canales, o Booking Engine con Channel manager en inglés, el cual le permita a los socios gestionar la disponibilidad de sus propiedades y publicarla en los canales que estimen convientes. Por canales se entienden cualquier tipo de agencia de viaje online, o OTA por su siglas en inglés, tales como Booking, Airbnb o el propio Trypo.
- Un sistema de reseñas que permita al usuario final o cliente tanto criticar la experiencia que tuve durante y despues del viaje, asi como juzgar si una experiencia es buena o no basándose en los comentarios del resto.

Por otro lado, en general, a nivel técnico los desafíos para concretar estos objetivos fueron de tiempo y escala. Es decir, que el equipo de Trypo era muy pequeño para la cantidad de caracterísiticas que se debían implementar y en el tiempo que se necesitaba hacerlo.  A nivel organizacional se tenia que al ser una startup o PYME la mayoria de integrantes del equipo trabajaban en el proyecto a media jornada o jornada flexible. Los únicos con jornada completa eran el practicante y el desarrollador de TecnoApps, por lo que se debían agendar constantemente reuniones en horarios que permitieran a todos los involucrados asistir.

De lograrse lo propuesto, los beneficios se repartirían para todos los involucrados. Por un lado se tiene que el equipo de Trypo sería capaz de poseer un producto robusto y único para un mercado poco explotado a nivel nacional y latinoamericano. Y por el otro lado, los socios conseguirían una herramienta completa que les permita gestionar todo desde un mismo lugar, y los usuarios finales tendrían un sitio donde buscar lugares y experiencias para hacer camping con mayor variedad y alcance.


---

# Metodología

Para concretar estos objetivos al practicante se le presento una metodologia general de parte del supervisor, la cual fue modificada para dar a lugar a un plan dividido en 4 pasos.

En primer lugar se hizo una investigación de conceptos, definiciones y tecnologías relacionadas al problema, donde se trato de elaborar una solución propetaria de manera prematura. En esta instancia esta se discutió la posibilidad de realizar incluir las características de manera nativa en Trypo con ayuda de TecnoApps. Lo cual se descartó por problemas técnicos.

En segundo lugar, una vez descartada la solución propietaria, se planteo un esquema del diseño esperado de la solución, donde se incluyó sus características claves y las opcionales. Despues de esto el practicante debería realizar una investigación o discovery del área, enfocandose en encontrar proveedores capaces de ofrecer un producto que se ajuste a lo minimo requerido.

Finalmente, se esperaba que el practicante se pusiera en contacto con los proveedores como representante de Trypo. En general, se realizaba un intercambio de información donde el practicante consultaba al proveedor sobre su producto, el modelo de negocio, casos de éxito similiares a Trypo, y se trataba de negociar la posibilidad de extender el producto de modo que se acomode a las necesidades claves del proyecto. Una vez hecho esto se agendaba una reunion con el equipo completo de Trypo y la empresa, donde se discutían los detalles más técnicos a nivel de software, infraestructura y negocio.

Con esta metodología se esperaba añadir las funcionalidades que la aplicación requería con urgencia de manera rápida y directa. Por esto mismo, desde un punto de vista empresarial, se considera que esta forma de añadir características es muy eficaz a corto plazo, pero a largo plazo el tener como característica el producto de un tercero hace que la aplicación en si misma depende en buena parte de este.

Finalmente para evaluar la calidad de la solución se basaran en la cantidad de socios nuevos se unan a la plataforma, en su feedback y la cantidad de uso que le den a las características empleadas. Como la práctica realizada tuvo un duración de 2 meses, la validación que fuera del alcance de esta por lo que no se proporcionaron al practicante extensos detalles en esta área.

---

# Descripción de la solución
Como se describio al inicio, durante la práctica se participó en dos problemáticas las cuales desenvocaron en dos soluciones respectivas: integración de un motor de reserva con channel manager y la implementación de un sistema de reseñas.

## Motor de reserva con gestor de canales
Inicialmente, como se mencionó, el equipo de Trypo había encontrado una oportunidad desaprovechada en posibles socios que no consideraban usar la aplicación debido a su sistema manual y cerrado de sincronización. Es por esto que al momento de ingresar a la práctica la empresa ya estaba evaluando la creación de un sistema propietario, después de una semana de investigación esto fue descartado debido a que la API de AirBnB y Booking no estaban disponible para todo público.

Con esto, el equipo decidió atacar el problema de otra forma, debido al tamaño del equipo y el cerrado ecosistema, se opto por buscar un socio que pueda ofrecerle a Trypo el backend necesario. Para esto se le encargó al estudiante realizar un discovery, donde en haciendo uso de Excel este resumió todos los candidatos posibles. Los requerimientos establecidos por el supervisor fueron los siguientes:

- El channel manager debe incluir Booking y/o AirBnB como canales
- Debe vender su producto por volumen
- Idealmente debe ofrecer un booking engine
- Idealmente debe contar con una API que facilite la conexión

Para resguardar la privacidad de los usuarios de Trypo la idea original era que la conexion se realizará entre la empresa y el socio, donde la primera actuaría como un usuario con múltiples propiedades para el sistema del segundo. Eso también le daría control al equipo sobre la gestión del servicio de cara al cliente final.

Con esto en mente el practicante su puso en contacto con todos los clientes que cumplieran, al menos, en grandes rasgos con los requerimientos. Por consejo del supervisor, se utilizo ese enfoque para después mediante correos conseguir información que no esta disponible públicamente.

Luego de este proceso, los candidatos se redujeron a (...), para los cuales se trato de conseguir una reunión por la plataforma Zoom. Con esto la empresa decidió trabajar con OTASync, esto debido a que cumplían perfectamente con los requerimientos. 

Los socios ofrecían un producto acorde a las necesidades de la aplicación: Poseían un channel manager con bookinh engine que se conectaba a AirBnB y Booking, ofrecían precios por volumen, poesían una API dedicada, junto con widgets para hacer la integración más sencilla y ofrecían, incluso borrar la marca OTA Sync para darle la sensación al usuario final de un sistema integrado completamente.

Este proyecto quedo en su etapa final al momento de finalización de la práctica, donde se había firmado ya un NDA y establecido un contrato. Lo único que faltaba era organizar los horarios para gestionar una reunión de demo e inducción del sistema con el equipo técnico de Trypo, para luego pasar a la integración.

Finalmente, el practicante considera que de concretizar la solución daría una ventaja fundamental a corto plazo a Trypo en el mercado latinoamericano, dando pie a la oportunidad de ser líderes en el área y, como mínimo, establecerse de manera robusta. Sin embargo, de cara al futuro se identifican problemas de gestión claves a medida que la aplicación crezca ya que esta funcionalidad depende estrictamente entre un acuerdo de Trypo con OTASync, por lo que si una de las partes cambia ciertos aspectos del sistema, podría ser muy perjudicial. En particular, si existiera una gran cantidad de socios de la aplicación que hicieran uso de estas funcionalidades, el poder de decisión de OTASync sería mayor que el de Trypo. Por lo que se recomienda diseñar una solución propia de todas formas, una vez conseguidos los accesos a las API de AirBnB y Booking.

## Sistema de reseñas
A partir de la segunda mitad de la practica, el supervisor decidió cambiar el proyecto del estudiante, debido a que la solución anterior se había estancado por problemas de contacto. Mientras esto se desarrollaba, el practicante se enfocó en encontrar las principales diferencias entre Trypo y el resto de aplicaciones similares en el mercado. Para ello la comparativa considero a AirBnB, Booking, TripAdvisor, Expedia y Rutero; y se centro en el viaje del consumidor o cliente desde la página de inicio hasta hacer una reserva exitosa.

Los resultados se pueden ver en la tabla X del anexo, donde se encontró que la diferencia principal fue la falta de un sistema de reviews. Por lo que el equipo le encargó al practicante encontrar un producto que, de una forma similar a la anterior, se pudiera integrar de manera sencilla al sistema de Trypo mediante una API. 

Un sistema de reviews, por lo general, suele incluir diversas formas de visualizar las valoraciones y opiniones. En el caso de un eccomerce la recolección de opiniones ocurre mediante correos, usando un link que da acceso a un formulario especializado para el tipo de producto que el cliente compro. Algunas funcionalidades extra son la capacidad de mandar distintos tipos de formularios para un mismo producto en distintos momentos de la compra, incluir categorías para hacer las valoraciones y publicar las valoraciones en redes sociales y metabuscadores. El sistema también suele contemplar la posibilidad de valorar la experiencia en si del uso de la página.

Inicialmente, por recomendación del supervisor,  se consideró la opcion ofrecida por (...) la cual tenía la gran ventaja de poseer un plan gratuito limitado pero con acceso a una API. La especificaciones de la API permitia hacer las operaciones básicas para un sistema de reseñas, por lo que el practicante mediante scripts de Javascript, usando JSON y XML básico creo un ambiente de testeo de la solución. Sin embargo, por problemas técnicos propios del servicio, esta solución no era capaz de cumplir con lo que prometía, por lo que se descartó inmediatamente.

El principal factor limitante era la escala del sistema, ya que la mayoria de opciones populares ofrecían un manejo de una enorme cantidad de reseñas para la cantidad de usuarios que se tenia en Trypo. Esto hacía que en la práctica la cantidad de dinero por reseña efectiva no fuera ideal. Con esto los requerimientos esta vez eran sólo 2:

- Contar con un plan con precio accesible.
- Permitir obtener reseñas en dos instancias distintas.

La primera fue previamente explicada, la segunda hace referencia a la naturaleza del producto. Para la mayoría de e-commerces la reseña solo ocurre al momento de finalizar la compra, no obstante, en Trypo se evalúo que obtener información tanto como durante la experiencia como al final de esta serviría de cara al usuario final para poder hacer una compra con confianza.

Es por esto que de misma forma que el anterior proyecto, el practicante hizo una investigación y acercamiento de candidatos cuyos productos se acercarán a los requerimientos de la compañia. Se investigaron 30 productos de distintas empresas, de los cuales se destacaron 4: Reviews.io, TrustedShops, Yotpo y Nicejob.

Lamentablemente, la práctica terminó antes de que Trypo se decidiera por una de las ofertas principales. A continuación una descripción breve de cada solución ofrecida por los principales candidatos:

- Reviews.io:
- TrustedShops:
- Yotpo:
- Nicejob:

Por otro lado, se considera que de concretarse este proyecto con una de estas cuatro opciones, a manera general, las ventas de experiencia en Trypo aumentarían drásticamente. Actualmente la página web tiene un gran flujo de visitas para el tiempo que lleva, pero falla en conseguir concretar una compra. Esto debido a que los clientes a la hora de plantearse el hacer compras por internet suelen tener mucha desconfianza en especial de sitios poco conocidos o pequeños. El hecho de contar con opiniones de personas reales que compraron (o experimentaron en este caso) el producto le da seguridad al comprador para adquirir los productos. 

Por último, al igual que el proyecto anterior, el hecho de que esta herramienta sea parte de un sistema de un tercero provoca que a futuro pueda existir problemas de gestión. No obstante, en este caso no sería tan grave ya que este sistema funciona de manera independiente y no requiere de ningún tipo de acceso extra. La mayoria del mercado de startup de eccomerce suelen decantarse por esta opción, por lo que no es un riesgo mayor a largo plazo.

---

# Discusión

## Búsqueda de un buen proveedor
Por como esta diseñada la metodología y la naturaleza de la solución deseada, la gran mayoría de cosas presentes en esta práctica poseeyeron un gran grado de incertidumbre, puesto que al ser un discovery, no se tenia certeza de que existiera un producto que se ajustara a las necesidades del proyecto. Al inicio de la primera fase de la práctica ocurrío en diversas ocasiones que varias propuestas tuvieron que ser descartadas por el equipo debido a que técnicamente no cumplía lo mínimo como para funcionar con los estándares definidos. Además esta siempre la posibilidad de que los candidatos potenciales se demoren en responder una vez contactados o directamente no lo hagan.

## Api
Sin embargo, lo que llevo a la empresa a escoger ese camino fue debido al obstáculo más importante de que las API de tanto Booking como AirBnB no fueran públicas ni de pago, si no que son ellos los que deciden de manera arbitraria quien tiene acceso basándose en criterios que son desconocidos. 


## Conocimientos del practicante
Para el desarrollo de la practica, al estudiante le resultaron muy útiles los conocimientos técnicos entregados por los cursos de Desarrollo de Aplicaciones Web, Base de datos e Ingeniera de software, ya que con estos no hubo necesidad de capacitación de ningún tipo, a diferencia de la primera práctica. Por otro lado, el curso que entrego mayor utilidad fue el de Evaluación y Gestión de Proyecto, ya que gracias a este el alumno fue capaz de evaluar correcta y eficazmente los proveedores, teniendo encuenta las necesidades del equipo y sus recursos. 

La principal debilidad del practicante esta vez fue que este no estaba acostumbrado a trabajar de manera independiente y a responder con resultados sin procedimiento específico. Concretamente, al inicio de la práctica hubieron lapsos de tiempo donde el estudiante no realizo ningún avance puesto que el tenía una actidud responsiva, donde este espera que le asignaran metas semanales con fecha limite, en cambio, en Trypo trabajaban sin fecha limite exacta y con metas mensuales o bimensuales. 

Entonces, por ejemplo, cuando al practicante se le asigno investigar potenciales proveedores, este trabajo durante una semana investigando y recolectando información la cual la resumió en un tabla y se la entregó al supervisor. El estudiante erróneamente esperó una respuesta sin avanzar más, cuando el supervisor esperaba que este actuará con más proactividad, independencia y libertad.

No obstante, al inicio de la practica el supervisor le aclaro al estudiante que parte de la idea de esta practica era que este desarrollara una actitud más proactiva y aprendiera a trabajar de manera más independiente. Por lo que el ambiente laboral fue dispuesto de esa forma, donde el practicante podía hacer consultas gracias a la interacción fluida entre este y el supervisor, con lo cual fue el ambiente en si mismo y la orientación proporcionada por el equipo lo que ayudo a resovler esta debilidad.

## Reflexión final
Finalmente, se destaca que durante toda la práctica el estudiante nunca se tuvo que enfrentar a ningún dilema ético debido a que el ambiente laboral fue agradable y honesto en todo momento. Por otro lado, con respecto a la experiencia vivida, se menciona en lineas generales fue positiva para el practicante, pero si se tuviera que rehacer, se cambaría el enfoque que se tuvo el cual estuvo demasiado alejado al de una práctica tradicional de computación. Donde no se tuvo oportunidad de crear software de ningún tipo, si no que más bien se actúo para solucionar problemas de tecnología.

---

# Conclusión

Considerando lo expuesto en el presente informe, se concluye que la en la práctica realizada por el estudiante no se consiguió cumplir con la mayoría de objetivos en su completitud. Dicho de otra manera, si bien para el caso del CM y BE se consiguió establecer un contrato con un proveedor del software deseado, la integración todavia no esta hecha, por otro lado, el sistema de reseñas solo fue reducido a unos candidatos y fue puesto en pausa debido a que el flujo de clientes actual no hace rentable el sistema. 

Se destaca los conocimientos proporcionados por los cursos cc y cc ya que estos permitieron al alumno administrar y gestionar los recursos, horarios y tiempos, así como tener el conocimiento técnico necesario para realizar la práctica en su totalidad. No obstante, cabe mencionar que la práctica fue más orientada en la adquisición de conocimientos del mundo empresarial, tales como negociar con terceros, gestionar soluciones a problemas inminentes y a elaborar una metodología que favorezca la proactividad.

A nivel personal, se considera que la experiencia vivida fue enriquecedora debido a que fortaleció un área de desarrollo profesional que normalmente no lo hace la Universidad, aunque también cabe mencionar que a nivel técnico fue muy deficiente. Si bien la metodología enseñada tiende a favorecer la adquisión de contactos en el mundo empresarial, en general es más bien desordenada y poco estructurada. 

Finalmente, a modo de síntesis y reflexión final, resulta curioso pensar en que la primera práctica fue enfocada a un lado muy técnico y mecanizado, mientras que en este segunda instancia se enfocó en la gestión y resolución de problemas. De ambas experiencias el estudiante concluye la clave para ascender y encontrar un lugar en el mundo profesional es saber adaptarse, tener una actitud proactiva, manteniendo, sin embargo, la robustez y perfeccionismo para el lado más artesanal de este rubro.

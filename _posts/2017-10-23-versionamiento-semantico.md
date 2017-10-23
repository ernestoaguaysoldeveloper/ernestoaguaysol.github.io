---
layout: post
title: "Versionamiento Semántico."
description: ¿Qué es el versionamiento semántico y por qué es importante?.
image: 'http://res.cloudinary.com/dm7h7e8xj/image/upload/c_scale,w_760/v1504807365/now-you-see-me_wtv89q.jpg'
'http://res.cloudinary.com/ernestoaguaysol/image/upload/v1508773455/semantic-version_lnrorp.png'
category: 'developer'
tags:
- semantic version
- versionamineto semántico
- orden
twitter_text: ¿Qué es el versionamiento semántico y por qué es importante?.
introduction: ¿Qué es el versionamiento semántico y por qué es importante?.
---

A la hora de trabajar con proyectos grandes de software siempre es importante tener un control de lo que se el cómo va creciendo nuestro código, siempre hay que mantener un orden. En nuestros inicios como desarrolladores de aplicaciones (en cualquier plataforma) siempre optamos en primera instancia por los comentarios al inicio del proyecto. En las primeras líneas especificamos qué funcionalidades fueron agregadas y qué otras fueron quitadas. A su vez, a las funcionalidades nuevas optamos por colocarle una fecha y el nombre del autor. Esta práctica hace el trabajo, pero surge la gran duda: ¿cómo le decimos al consumidor del software que la aplicación ha cambiado mucho o poco sin que vea los comentarios iniciales?

Para eso, tenemos una técnica que hoy en día se conoce como “Versionamiento semántico” y ¿qué es eso? Es una manera de identificar la versión de nuestro software usando un patrón específico y estándar, así; cualquiera que se interese en nuestro software y vea el historial de versiones vea cuánto se ha mejorado a través de cada una de las actualizaciones.

Ahora, ¿cómo usarlo? El número de la versión se identifica con tres dígitos, lo cual es un patrón X.Y.Z y cada posición tiene su significado:

+ X o major: es cuando se hace un cambio muy grande en el software, se borran o se añaden múltiples funcionalidades. Generalmente la versión anterior a ésta es incompatible con la nueva, por eso; al descargarla para el uso hay que tener consideraciones. Un ejemplo es la reciente versión 3.1.0 de jQuery, a comparación con la 2.2.4 hay muchas cosas que varían, quizá funciones nuevas o algunas removidas que pueden ocasionar incompatibilidad.
+ Y o minor: Es la manera de agregar una nueva funcionalidad pero esta sigue siendo compatible con la versión anterior. También es considerada cuando se marca algo del software como obsoleto.
+ Z o patch: Se utiliza cuando se corrigen fallas. No sólo se usa para corrección de funcionalidad, también es posible usar este dígito cuando se cambian aspectos estéticos. La compatibilidad con versiones anteriores se mantiene perfectamente.

## Identificadores de estabilidad

Además de poder definir los cambios en el código como major, minor o patch, se suelen añadir unos identificadores que ayudan a marcar versiones específicas que quieres diferenciar, indicando la estabilidad de esa versión.

Por ejemplo, tienes tu aplicación a la versión 1.4.6 pero decides empezar el desarrollo de la próxima gran versión, la 2. Entonces los primeros desarrollos en esa versión nueva irán a la 2.0.0, pero como todavía estás empezando y probando cosas, podrías ponerle un identificador que le dijese a la gente la estabilidad de esa versión. Tu versión quedaría en algo como 2.0.0-alpha, por ejemplo, y la gente sabría que es una versión _alpha_ no muy estable.

Según fueses avanzando en el desarrollo, llegarías a una versión beta la cual marcarías por ejemplo como 2.1.3-beta. Así hasta que todo estuviese listo para publicarse, y marcases una versión como candidata para ser publicada como 2.1.5-rc1.

Si dos versiones iguales tienen distinto identificador, da igual: se consideran iguales a todos los efectos. Esto nos permite ir actualizando la estabilidad de una versión, pudiéndola pasar de _alpha_ a _beta_ o incluso a release candidate.

También por convenio, encontrarás otro identificador conocido como dev-master. Este identificador apunta a la última revisión enviada al repositorio, que no tiene por qué ser la última estable. Si dependes en esta versión estarás al día con todos los últimos cambios, pero te arriesgas a recibir cambios no retrocompatibles.

-----

¿Quieres saber más?, leer documentación oficial en <a href="http://semver.org/lang/es/">Versionado Semántico 2.0.0-rc.2.</a>

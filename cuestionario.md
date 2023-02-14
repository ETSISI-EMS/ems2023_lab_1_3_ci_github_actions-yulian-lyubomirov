1. ¿Qué es un pipeline o workflow?

Es un procedimiento automatizado que describe el flujo de trabajo o pipeline (build, test, package, release
o deploy). Se puede configurar para que reaccione a ciertos eventos (por ejemplo, cuando se hace un nuevo
push a una rama del repositorio de código), automáticamente de forma periódica (ej. al final de cada jornada
de trabajo) o por eventos externos.

2. Representar en un esquema el pipeline implementado (especificando las tareas automatizadas con el
mayor detalle posible)

3. ¿Qué es un runner? ¿para qué sirve?

Es la instancia en un servidor que ejecuta un workflow, pudiendo utilizar un runner hosteado por
Github (es decir, utilizando los datacenters de GitHub) o añadir un host propio.

4. ¿Qué es un action? ¿para qué sirve?

Son comandos de ejecución del pipeline, ejecutados en un step de un job. Son el bloque de construcción
más pequeño que hay. Puedes crear tus propios actions o utilizar aquellos creados por la comunidad de
GitHub. 

5. ¿Qué otra funcionalidad de GitHub Actions te hubiese gustado aprender?

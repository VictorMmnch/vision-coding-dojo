# vision-coding-dojo - Blog 
Conociendo Grails con el REST profile

Grails
===

[Grails](http://grails.org/) es un framework para crear aplicaciones web con el lenguaje de programación [Groovy](http://groovy-lang.org/). Groovy? Si, Groovy, una historia digna de otro Coding Dojo. 

 - Robusto
 - Dinámico
 - Rápido



REST -  Representational State Transfer
===
 - POST
 - GET
 - PUT
 - DELETE

Vamos a comenzar
===

Debimos haber realizado la configuración para **GRAILS**, usando nuestro mero mero chipocludo amigo [SDKMAN](http://sdkman.io/) o, en Windows, _seteado_ **JAVA_HOME, GRAILS_HOME** como variables de entorno.

Ahora si, vengan las pedaleadas!

Primero que todo, necesitamos crear nuestro proyecto base **Grails** y para lograr esto usaremos unos de los _profiles_ disponibles para **rifarnos de más**. Desde nuestra linea de comandos **(una vez accedido a nuestra carpeta de workspace: CD ~/nuestroWorkspace)** debemos ejecutar el siguientes comando 

```
$ grails create-app vision-coding-dojo --profile rest-api
```

Esto generará la estructura base lista para desarrollar. 

Paquetes importantes para este dojo

- domain
- controller

**Domains**




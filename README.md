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

Para generar nuestras clases de dominio, definieremos el siguiente paquete

```
mx.com.vswf.dojo
```

con el siguiente commando **Grails** se deberá generar 

```
$ grails create-domain-class mx.com.vswf.dojo.User

$ grails create-domain-class mx.com.vswf.dojo.Post

$ grails create-domain-class mx.com.vswf.dojo.Comment
```

El proposito de la aplicación es proporcionar los servicios **REST** de un simple Foro en el cual hay usuarios y cada usuario puede realizar publicaciones (Post) y tambièn hacer comentarios sobre esas publicaciones, por lo tanto, un User tiene muchos Post, un post pertenece a un usuario y un usuario puede hacer comentarios sobre un post.

Entonces, mi propuesta de modelo de dominio queda así:

### User

|Campo | Tipo  |
|--------------------------|---|
|firstName|String|
|lastName|String|
|age|Integer|
|email|String|

String firstName
	String lastName
	Integer age
	String email

### Post

|Campo | Tipo  |
|--------------------------|---|


### Comment

|Campo | Tipo  |
|--------------------------|---|


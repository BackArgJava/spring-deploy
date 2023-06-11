## Despliegue de apps Spring boot en Railway

Crear archivo `system.properties` en el proyecto de contenido:

```
java.runtime.version=19
```
1. Crear cuenta en Railway y github.com

2. Tener configurado git en el ordenador (ejecutar únicamente la primera vez que se instala git)

3. `git config --global user.name "BackArgJava"`
4. `git config --global global user.email  "mail"` 


5. Subir el proyecto a GitHub desde IntelliJ IDEA desde la opción: VCS > Share project on GitHub

6. Desde Heroku, crear app y elegir método GitHub y buscar el repositorio subido 
7. Habilitar deploy automático y ejecutar el Deploy


Ejercicio 1

Probar a empaquetar la aplicación con maven package desde Intellij IDEA

Desde terminal en Intellij IDEA verificar que se se ejecuta correctamente con el comando:
java -jar target/spring-deploy-1.0.jar

Crear un perfil para dev y otro para test con una propiedad nueva que carguemos en el controlador.

Ejercicio 2

Desplegar el API REST de Laptops en Heroku y verificar funcionamiento desde POSTMAN.

Ejercicio 3

Añadir Spring Security sobre el proyecto API REST de Laptops y configurar 2 usuarios en memoria utilizando una clase WebSecurityConfig.
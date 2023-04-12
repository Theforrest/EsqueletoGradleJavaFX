# Esqueleto gradle con las dependencias para JavaFX

#### Autor: José Ramón Jiménez Reyes

#### Descripción

En este repositorio encontrarás el esqueleto de un proyecto para **Eclipse** (aunque podría utilizarse en otros IDEs).

Dicho proyecto contiene las dependencias **gradle** para trabajar con **JavaFX** y para empaquetarlo correctamente.

También contiene una clase pricipal de ejemplo `Main` y la correspondiente clase lanzadora `LanzadoraMain`.

#### Uso

Lo primero que debes hacer es clonar el repositorio en Eclipse. 

Una vez clonado, deberás cambiar el nombre del proyecto para adecuarlo a tus preferencias. Para ello pincha con el botón derecho sobre el proyecto y elije la opción `Refactor | Rename`.

Finalmente deberás abrir el archivo `settings.gradle` y cambiar el nombre de proyecto ahí también, ya que eso no lo hace Eclipse en la refactorización. Por último, pincha con el botón derecho sobre el proyecgto y elige la opción `Gradle | Refresh Gradle Project`.

#### Ejecución

Utiliza la tarea `run` asociada para ejecutarlo o desde la línea de comandos puedes utilizar el comando `./gradlew run`.


# REPRODUCTOR_VLC-JAVA

https://github.com/caprica/vlcj-examples/blob/master/src/main/java/uk/co/caprica/vlcj/test/streaming/StreamRtsp.java


![vlcj](https://github.com/caprica/vlcj/raw/master/etc/vlcj-logo.png "vlcj")

REPRODUCTOR JAVA USA: vlcj
====

El proyecto vlcj proporciona un marco Java para permitir una instancia de un nativo
[VLC](http://www.videolan.org/vlc "VLC") reproductor multimedia para ser incrustado en un Java
AWT Window o Swing JFrame.

Obtiene más que solo enlaces simples, también obtiene un marco de trabajo de nivel superior
eso oculta muchas de las complejidades de trabajar con LibVLC.

vlcj se desarrolla principalmente y, por lo tanto, se prueba exhaustivamente en Linux;
también funcionan bien en Windows y MacOSX, aunque puede haber algunos
limitaciones en OSX.

Se requiere al menos JDK 1.6 y funciona sin cambios en JDK 1.7+.

Esta es la página del proyecto vlcj de código abierto, consulte también la 'oficial'
[página de inicio](http://capricasoftware.co.uk/#/projects/vlcj "Página de inicio oficial de vlcj en Caprica Software")
donde puede encontrar más información, así como algunos nuevos tutoriales sencillos.

La versión 3.0.0+ de vlcj requiere la versión 2.1.0+ de VLC, versiones anteriores de VLC
*no* son compatibles y *no* funcionarán.

La versión 3.0.0+ de vlcj requiere la versión 3.5.2 de JNA.

Algunas características de la versión 3.0.0+ de vlcj (como la nueva API de ecualizador de audio)
requiere la versión 2.2.0+ de VLC.

Si aún necesita usar VLC 2.0.x, debe quedarse con vlcj 2.x.x en su lugar
de actualizar a la nueva serie vlcj 3.0.0.

Maven Dependency
----------------

Add the following Maven dependency to your own project pom.xml:

```
<dependency>
    <groupId>uk.co.caprica</groupId>
    <artifactId>vlcj</artifactId>
    <version>3.10.1</version>
</dependency>
```

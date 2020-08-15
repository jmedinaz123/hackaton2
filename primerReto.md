1. ¿Qué es un control de versiones? 

Los sistemas de control de versiones son una categoría de herramientas de software que ayudan a un equipo de software a gestionar los cambios en el código fuente a lo largo del tiempo. El software de control de versiones realiza un seguimiento de todas las modificaciones en el código en un tipo especial de base de datos. Si se comete un error, los desarrolladores pueden ir atrás en el tiempo y comparar las versiones anteriores del código para ayudar a resolver el error al tiempo que se minimizan las interrupciones para todos los miembros del equipo.

2. ¿Cuáles son los problemas al no usar un control de versiones? 

Los problemas serian el no poder dar seguimiento de todos los cambios individuales de cada colaborador y al contribuir a evitar que el trabajo concurrente entre en conflicto.
Otro problema puede ser el atraso que puede generar en el desarrollo a los programadores y que no exista eficacia.
Tambien un problema de no usar control de versiones, es que no se cuenta con copias de seguridad en caso surga algun inconveniente.


3. ¿Cuáles son los beneficios? 

El control permite que los desarrolladores se muevan más rápido y posibilita que los equipos de software mantengan la eficacia y la agilidad a medida que el equipo se escala para incluir más desarrolladores.

Es posible trabajar en varias cosas al mismo tiempo con diferentes personas.

Permite gestionar los cambios y tener una trazabilidad del proyecto.

4. ¿Qué tipos de control de versiones existen? 

Existen 2 grandes grupos:

A.Centralizados
En un sistema de control de versiones centralizado todos nuestros fuentes y sus versiones están almacenados en un único directorio (llamado repositorio de fuentes) de un ordenador (un servidor). Todos los desarrolladores que quieran trabajar con esos fuentes, deben pedirle al sistema de control de versiones una copia local para trabajar. En ella realizan todos sus cambios y cuando están listos y funcionando, le dicen al sistema de control de versiones que guarde los fuentes modificados como una nueva versión.Algunos ejemplos son CVS y subversión.

B.Distribuidos
En un sistema de control de versiones distribuido no hay un repositorio central. Todos los desarrolladores tienen su propia copia del repositorio, con todas las versiones y toda la historia. Por supuesto, según van desarrollando y haciendo cambios, sus fuentes y versiones van siendo distintas unas de otras. Sin embargo, los sistemas de control de versiones distribuidos permiten que en cualquier momento dos desarrolladores cualesquiera puedan "sincronizar" sus repositorios. Si uno de los desarrolladores ha tocado determinados fuentes y el otro no, los modificados se convierten en la versión más moderna.Ejemplos:Git y Mercurial.
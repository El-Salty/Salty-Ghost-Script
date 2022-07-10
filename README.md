# Salty-Ghost-Script
Herramienta de optimizacion y mantenimiento de Windows 10/11

![image](https://user-images.githubusercontent.com/108878822/177781276-e28583a6-c2a3-4837-b8c6-4b7c4e1b099c.png)


Hola, gracias por seguir este proyecto. 
Esta es una herramienta que por el momento se encuentra dividida en 5 secciones:

![image](https://user-images.githubusercontent.com/108878822/177790726-08e635bb-9d81-484b-bf30-556f65514d18.png)

El objetivo de esta seccion es remover por completo las aplicaciones/bloatware instaladas por defecto en Windows, asi mismo se configuraran servicios para deshabilitar aquellos que no tienen funciones para la mayoria de los usuarios no empresariales. Se remueve Windows Defender, One Drive y se purga el panel de control dejando solo opciones basicas para el usuario. A pesar de las modificaciones Windows Update no esta desactivado ha sido mejorado para solo ofrecer actualizaciones de seguridad.
Esto lo hemos logrado modificando y reparando el codigo original de los AME scripts. Quienes desactivaban por completo Windows Update ademas de presentar ciertos errores y no eliminar por completo los componentes de nuevas versiones de Windows. Tiene como objetivo ser usada por cualquier individuo sin la necesidad de utilizar Linux como en el script original requeria.

![image](https://user-images.githubusercontent.com/108878822/177790800-40d30faf-edb4-4c94-ac08-3210c15da2bd.png)

En esta seccion se complementara con software de codigo abierto el sistema ya que reemplazara el hueco dejado por Windows Defender y entre otras utilidades como: 

1 SDIO. Para la actualizacion de drivers debido a que se deshabilita la opcion de Windows Update para ofrecer Drivers.

2 VLC. Reproduccion de contenido multimedia por modificaciones a Windows Media Player

3 7Zip Al no haber herramienta de descompresion de Windows.

4 jpegview  Como visor de imagenes 

5 Immunet Como una alternativa ligera de Antimalware por la ausencia de Windows Defender.

Estas herramientas son descargadas en tiempo real desde los repositorios de Chocolatey.

![image](https://user-images.githubusercontent.com/108878822/177790229-a1274a9f-912e-43ca-b324-c88b91dfa53f.png)

El objetivo de esta seccion es desactivar los privilegios de administrador para seleccionar un tipo de usuario standard en nuestra cuenta de uso diario, la razon de esto es por el estudio de seguridad realizado por la firma de Ciberseguridad Avecto quienes determinaron que hasta el 94% de las 530 vulnerabilidades que se habian detectado en 2016, pueden mitigarse deshabilitando estos privilegios.
El sistema funcionara con normalidad para el usuario comun, inclusive si requiere de funciones avanzadas se le pedira el permiso requerido, lo cual no causara problemas en la mayoria de los usuarios domesticos.

![image](https://user-images.githubusercontent.com/108878822/178128341-30711a53-fea3-4c13-b340-25430d41e4ec.png)

Esta seccion tiene como objetivo aprovechar las mismas herramientas de Windows para brindar un simple y rapido mantenimiento que incluye la herramienta de Windows Disk Clean-Up, eliminacion extra de archivos temporales, preload y archivos en la papelera de reciclaje, al finalizar este proceso concluira con la desfragmentacion de la unidad utilizando el mismo desfragmentador de Windows.

![image](https://user-images.githubusercontent.com/108878822/177790335-78a77594-eb84-4f4c-bf39-a8c01a6af7a5.png)

Como su nombre lo indica es un acceso inmediato para reiniciar el sistema al final del proceso. Lo cual recomendamos ampliamente para ver aplicados los cambios en su totalidad.

Como ultimo cabe recordar que este Script es recomendado para usuarios individuales domesticos no empresariales y su uso es completa responsabilidad del usuario.

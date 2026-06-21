# Inicio

[![Ver video explicativo](https://github.com/BenjaminGuzman/ExcelProtectedGrades/raw/refs/heads/master/instructivo.mp4)](https://github.com/BenjaminGuzman/ExcelProtectedGrades/raw/refs/heads/master/instructivo.mp4)

Excel protected grades using VBA macros with AES symmetric encryption

Al ingresar le pedirá su identificación, si desea consultar la información de un alumno cuya matrícula está en el documento, ingrésela.

Si desea modificar el documento, ingrese su contraseña de administración del programa. Esta contraseña se deberá encontrar en un archivo de texto plano de nombre `exceles.txt` adentro de la carpeta de su usuario, `C:\Users\<su nombre de usuario>\exceles.txt`. La contraseña deberá estar escrita en una sola línea.

## Uso como administrador

Una vez haya ingresado como administrador le aparecerán los datos que tenga el excel desglosados y desencriptados (si no es así, seleccione las celdas ocultas de las filas que desee revisar y presione "Desencriptar y mostrar").

### Llenar información

Usted podrá realizar las modificaciones que sean necesarias a las filas y columnas que necesite con una excepción: 

**Las matrículas de los alumnos siempre deben estar colocadas en la primera columna, la columna A**.

### Ocultar información

Una vez ingresada la información de los alumnos es momento de terminar, encriptar y guardar, para ello seleccione sólo las celdas que contienen las matrículas de los alumnos a esconder y presione TERMINAR, surgirá un cuadro de diálogo pidiendo su confirmación, revise que el texto no esté previamente encriptado y que en efecto sólo haya seleccionado las matrículas de los alumnos a esconder. Para evitar cualquier inconveniente, es recomendable antes realizar una copia de seguridad de esas calificaciones.

El programa a la brevedad encriptará y esconderá todo, listo para que pueda distribuir ese archivo de Excel a sus alumnos, es importante que guarde los cambios antes de hacer esto.

## Uso como alumno

Una vez ingresado como alumno solamente es útil revisar las calificaciones otorgadas, si bien, es posible realizar modificaciones en el documento, esto no afectará evidentemente situaciones externas al mismo.

# Desarrollo del proyecto

Puede revisar el código para cerciorase de que no hay instrucciones maliciosas que puedan comprometer la seguridad o privacidad de su hoja de Excel, para evitar que los alumnos vean el código, éste se protegió con la contraseña **`BenjaminGuzmanA01750156`**.

Obviamente es libre de modificar el proyecto y agregar o quitar características, dispense usted si la calidad con la que fue hecho no fue la mejor, este de hecho es mi primer programa con VBA.

# Algoritmia-Programacion


![JefCar]()

# Proyecto de Asignación de Estudiantes a Cursos

Este proyecto tiene como objetivo asignar estudiantes a distintos cursos según su semestre y nivel académico, generando archivos CSV y Excel con las asignaciones realizadas. Además, el proceso de asignación se registra en un archivo de log.

## Requisitos

Para ejecutar este script en Google Colab, no es necesario instalar las librerías manualmente ya que se importan directamente en el código.

## Descripción del Código

### Configuración Inicial

Se configura la ruta donde se guardarán los archivos generados y se crea el directorio si no existe.

### Función de Log

La función `MensajeLog` agrega mensajes a una lista de logs y también los imprime en la consola.

### Carga de Datos

Se cargan los datos de estudiantes y la malla curricular desde archivos CSV proporcionados en la URL.

### Funciones Auxiliares

- `AsignaturaCode`: Genera el código de la asignatura.
- `HTD`: Calcula las horas de trabajo docente (HTD).
- `HTI`: Calcula las horas de trabajo independiente (HTI).

### Función Principal

La función `FuncionPrincipal` realiza la asignación de los estudiantes a los cursos y genera los archivos CSV y Excel correspondientes, además de registrar mensajes de log en cada paso importante.

### Ejecución de la Función Principal

Se ejecuta la función `FuncionPrincipal` para varios semestres y niveles.

### Guardado de los Logs

Al final del script, se escriben todos los mensajes de log en un archivo de log.

## Uso

Para ejecutar el script en Google Colab, copia y pega el código en una celda de Colab y ejecútalo. Asegúrate de que las rutas de los archivos CSV sean correctas o modifica las rutas según sea necesario.

## Licencia

Este proyecto está bajo la licencia MIT.

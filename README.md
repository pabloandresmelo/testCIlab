# Estructura de directorios repositorio laboratorios
## _Versión 1.0_

![Ntt Ico](https://financialit.net/sites/default/files/ntt_data.jpg)

La siguiente es la definición borrador para la estructura de directorios de almacenamiento
de repositorios para laboratorios de excelencia técnica de NTT DATA - BeDevOps
## Carpetas principales

| Carpeta | Descripción |
| ------ | ------ |
| [Assets][PlAs] | Almacenamiento de imagenes y archivos relacionados a las guias |
| [Guides][PlGu] | Almacenamiento de guias de cada laboratorio |
| [SourceCode][PlSo] | Almacenamiento de código fuente y scripts que se usan para los laboratorios |

## Ejemplo de almacenamiento de laboratorio

Para este ejemplo vamos a crear la estructura de un laboratorio llamado `Continuous Integration`
Los archivos MD guia del laboratorio deben ir en la subcarpeta `ContinuosIntegration`
Dentro de esta carpeta deben crearse dos carpetas para el almacenamiento de información para `Facilitador` y `Estudiante`

###### Según lo anterior, la estructura de la carpeta `Guides` para este curso quedaría de la siguiente forma:


Carpeta del curso

```sh
../Guides/ContinuosIntegration
```

Carpeta de guia facilitador

```sh
../Guides/ContinuosIntegration/Facilitador
```

Carpeta de guia estudiante

```sh
../Guides/ContinuosIntegration/Student
```
###### Los archivos de imagenes y otros que hagan parte de la composición de la guia del laboratorio deben ir en la carpeta `Assets`

Dentro de esta carpeta deben crearse tres carpetas para el almacenamiento de información para `Facilitador`, `Estudiante` y `Configuration`

Carpeta del curso

```sh
../Assets/ContinuosIntegration
```

Carpeta de assets guia estudiante

```sh
../Assets/ContinuosIntegration/Student
```

Carpeta assets de guia estudiante

```sh
../Assets/ContinuosIntegration/Student
```

Carpeta assets de configuración (Almacena scripts u otros archivos que mejoren la experiencia y visualización de los MD)

```sh
../Assets/ContinuosIntegration/Student
```

###### Los archivos de codigo fuente, scripts de configuración de laboratorios y otros que hagan parte de la ejecución de la guia del laboratorio deben ir en la carpeta `SourceCode`

Dentro de esta carpeta deben crearse tantas carpetas carpetas como ejercicios se definan para la guia

Carpeta del curso

```sh
../SourceCode/ContinuosIntegration
```

Carpeta de código ejercicios

```sh
../SourceCode/ContinuosIntegration/Exercise1
../SourceCode/ContinuosIntegration/Exercise2
../SourceCode/ContinuosIntegration/ExerciseN..
```

Carpeta de código configuración lab

```sh
../SourceCode/ContinuosIntegration/LabPlatformConfiguration
../SourceCode/ContinuosIntegration/LabConfigurationStudentPrerequisites
```



[PlAs]: <https://umane.everis.com/git/GDNFBDO/techlabs/-/tree/main/Assets>
[PlGu]: <https://umane.everis.com/git/GDNFBDO/techlabs/-/tree/main/Guides>
[PlSo]: <https://umane.everis.com/git/GDNFBDO/techlabs/-/tree/main/SourceCode>

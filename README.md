# TALLER 1: Consolidación de la Poo en Java 21 y Entorno Profesional

Proyecto Maven del **Taller 1: Configuración del entorno profesional** (Programación 3, POO avanzada). Deja funcionando, en equipo, el entorno de trabajo con **Java 21, IntelliJ IDEA, Maven, JUnit 5 y Git/GitHub**.
## 1 Información del Grupo
| | |
|---|---|
| **Universidad** | Universidad Agraria del Ecuador, Facultad de Ciencias Agrarias "Dr. Jacobo Bucaram Ortiz" |
| **Carrera** | Computación en Línea |
| **Grupo** | 08 · Cuarto semestre, paralelo C |
| **Asignatura** | Programación 3 (POO) |
| **Período** | 2026-2027 CII |
| **Docente** | Ing. Hamilton Francisco Villamar Barros, MSc. |

## 2 Integrantes y roles

| Integrante | Rol en el taller | Usuario de GitHub |
|---|---|---|
| María Anchundia | Líder de integración | 
| Narciso Galarza | Responsable de pruebas | 
| Brithany Rivera | Responsable de pruebas | 
| Alfonso Olvera | Responsable de documentación | 
| Michael Caicedo | Verificador | 
 
 ## 3. Objetivo
Configurar en equipo el entorno profesional de desarrollo de la asignatura JDK21, IntelliJ IDEA, Maven, JUnit 5 y Git con GitHub y demostrarlo con un proyecto Maven compartido, con pruebas unitarias aprobadas y un historial de commits en el que participen todos los integrantes.

Creación del repositorio
<img width="1168" height="919" alt="Captura de pantalla 2026-10-27 231812" src="https://github.com/user-attachments/assets/9a2755e5-6521-4834-aebf-2195c4698d51" />

Enlace al repositorio: https://github.com/grupo8-uagraria/finca-grupo8
Evidencias de la Preparación Individual (Parte A)

Capturas de pantalla de la terminal de cada integrante ejecutando java -versión (comprobando que sea la versión 21) y git --version.

<img width="1777" height="885" alt="image" src="https://github.com/user-attachments/assets/218647ca-d6ac-4de7-8291-8e30fc205772" />
Pc de la compañera Brithany captura 1_Verificación del entorno


<img width="1777" height="885" alt="image" src="https://github.com/user-attachments/assets/4aa54d9a-7919-4c7a-9d85-d95c31fff2cf" />
Pc del compañero Alfonso captura 2_Verificación del entorno


<img width="1777" height="885" alt="image" src="https://github.com/user-attachments/assets/99950429-8031-4e12-9172-d314942df524" />
Pc del compañero Caicedo captura 3_Verificación del entorno


<img width="1777" height="885" alt="image" src="https://github.com/user-attachments/assets/a1d41b49-76e6-4c71-8151-c049d12553a9" />
Pc de la compañera Verónica captura 4_Verificación del entorno


<img width="1777" height="885" alt="image" src="https://github.com/user-attachments/assets/e4788ba0-25da-4214-b04e-08530ac19396" />
Pc del compañero Narciso captura 5_Verificación del entorno

Evidencias del Proyecto y Pruebas Unitarias (Parte B)

<img width="1919" height="1025" alt="Captura de pantalla 2026-10-21 220039" src="https://github.com/user-attachments/assets/1b763a74-7964-4de6-bed6-76e258e49577" />
Ejecución exitosa de pruebas unitarias con Maven 

Evidencias de Trabajo Colaborativo Parte C y D

<img width="509" height="272" alt="image" src="https://github.com/user-attachments/assets/96a9052e-d555-43ac-96e9-6258cbfc43d7" />

Ejecución exitosa de pruebas

Parte D documentación y cierre
<img width="1919" height="1022" alt="image" src="https://github.com/user-attachments/assets/79b41df2-a9b5-48b8-94df-56d833c9595a" />


## Versiones utilizadas

| Integrante | Java (Temurin) | Git | IntelliJ IDEA |
|---|---|---|---|
| María Anchundia | 21.0.3 | 2.52.0 | 2025.3.1 |
| Narciso Galarza | 21 y 25.0.3 (usa el 21 para el taller) | 2.52.0 | 2025.3.1 |
| Brithany Rivera | 21.0.7 | 2.52.0 | 2025.3.1 |
| Alfonso Olvera | 21.0.3 | 2.52.0 | 2025.3.1 |
| Michael Caicedo | 21.0.3 | 2.52.0 | 2025.3.1 |

## Estructura del proyecto

```
finca-grupo08
├── pom.xml
├── .gitignore
├── README.md
└── src
    ├── main/java/ec/edu/uagraria/finca/Parcela.java
    └── test/java/ec/edu/uagraria/finca/
        ├── ParcelaTest.java
        └── Parcela<Apellido>Test.java   (una por integrante)
```

- **GroupId:** `ec.edu.uagraria.prog3`
- **Dependencia de pruebas:** JUnit 5 (Jupiter) 5.10.2
- **Compilación:** Java 21 (`maven.compiler.release`)

## Cómo ejecutar las pruebas

1. Clonar el repositorio:
   ```
   git clone https://github.com/galarzanarciso-lab/finca-grupo8.git
   cd finca-grupo8
   ```
2. Verificar las versiones instaladas:
   ```
   java -version
   git --version
   ```
   La primera línea de `java -version` debe comenzar con `openjdk version "21`.
3. Abrir el proyecto en IntelliJ IDEA con el JDK 21.
4. En la ventana **Maven**, abrir **Lifecycle** y hacer doble clic en **test**, o ejecutar:
   ```
   mvn test
   ```
5. El resultado esperado termina en:
   ```
   Tests run: N, Failures: 0, Errors: 0, Skipped: 0
   BUILD SUCCESS
   ```
   La primera vez Maven descarga bibliotecas y puede tardar; no cancelar el proceso.

## Flujo de trabajo en equipo

Cada integrante agrega su propia clase de prueba (un archivo por persona para evitar conflictos) y la publica desde su cuenta:

```
git add .
git commit -m "Agrega prueba de <Apellido>"
git pull --rebase
git push
```

## Honestidad académica

Cada integrante realiza sus propios commits desde su propia cuenta de GitHub. El uso de asistentes de inteligencia artificial se declara en el informe del taller.

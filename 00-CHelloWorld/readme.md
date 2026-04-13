TP0: Configuración del entorno y "Hello, World!" en C.

## Datos del Compilador y Entorno
- **Compilador:** GCC
- **Versión del compilador:** gcc.exe (MinGW.org GCC-6.3.0-1) 6.3.0
- **Versión del lenguaje C:** 

## Ejecución
- **Acceso y clonación del Repositorio**:
git clone https://github.com/sol-novellino/SySL.git  
cd SySL
- **Acceso a la carpeta**:
cd 00-CHelloWorld
- **Compilación del archivo fuente**:
gcc hello.c -o hello -std=c23  
compilador - nombre archivo fuente - nombre archivo ejecutable - versión del lenguaje
- **Ejecución del archivo ejecutable**:
.\hello
- **Redirección a output.txt**:
./hello > output.txt
- **Para ver la versión del compilador:** gcc --version

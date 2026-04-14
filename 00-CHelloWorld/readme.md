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
gcc hello.c -o hello  
compilador - nombre archivo fuente - nombre archivo ejecutable
- **Ejecución del archivo ejecutable**:
.\hello
- **Redirección a output.txt**:
./hello.exe > output.txt
- **Para subir el archivo output.txt al GitHub**:
git add output.txt
git commit -m "TP0: Archivo de salida listo"
git push origin main  
- **Para ver la versión del compilador:** gcc --version

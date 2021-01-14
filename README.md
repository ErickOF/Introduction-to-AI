# **Introducción a la Inteligencia Artificial - Curso de Maestría**

## **Antes de iniciar**
Debe asegurarse de tener instalado Git en su computadora. Si no lo tiene,
puede descargarlo [aquí](https://git-scm.com/downloads).


## **Instalación**
1. Descargar [Anaconda](https://repo.anaconda.com/archive/Anaconda3-2019.10-Windows-x86_64.exe).
2. Instalar Anaconda en `C:\Users\<Usuario>\Anaconda3`. Cuando se realiza la
instalación, debe marcar la opcion que dice "Registrar Anaconda como mi
Python 3.7 por defecto". Confirmar la instalación y esperar a que termine.
3. Crear un directorio de trabajo y asegurarse de que los scripts `setup.bat`
e `install.bat` estén dentro de este. También puede clonar el repositorio y
usar la carpeta creada como folder de trabajo (`git clone https://github.com/ErickOF/Introduction-to-AI-Master-Degree.git`).
4. Ejecutar en el directorio de trabajo, el script `setup.bat` en una terminal
de Windows.
5. Posteriormente, ejecutar el script `install.bat`
6. Si todo salió correctamente, deberá ver un mensaje verde al final diciendo:
`419 passed in xs (0:xx:xx)`.

![test](src/imgs/Test.PNG)


## **Posibles fallos**

### **Se requiere una versión de Visual C++ 2014 o superior**

Para solventar lo de la versión de Visual C++ existen dos posibles opciones:

* Si se tiene instalado Visual Studio Community, se puede abrir Visual Studio
Installer y actualizar las herramientas de Compilación de C++. Cuando termine
se debe reiniciar la computadora, abrir una terminal nueva y realizar del
paso 3 en adelante.

* De no tener instalado Visual Studio Community, se debe descargar Visual
Studio Community 2015 o superior (se recomienda esta última), con las
herramientas de Compilación de C++. Si no se quiere instalar esto, se debe ir
a la página oficial de Microsoft y descargar todas las herramientas de
compilación por a parte, esto se puede hacer [aquí](https://visualstudio.microsoft.com/visual-cpp-build-tools/).

![build-tools](src/imgs/BuildTools.PNG)


## **Reportar fallos**

# avuln_tareas
## Tareas
#### Tarea1
Investigar:  
Significado de la “R” en los registros de propósito general  de 64 bits(*)  
Investigar tipos de datos en ensamblador y su tamaño  

#### Tarea2
Generar el código ensamblador de las sentencias switch,  y for(comentadas linea por linea), entregar binarios y archivos ASM.

#### Tarea3
Realizar el diagrama de comportamiento de la pila paso a paso, de acuerdo a las instrucciones.  
Cada instruccion debe ir dentro de un bloque con lo siguiente:  
	registros (EBP,ESP y EIP)  
 	instruccion a ejecutar  
  Comentario de la ejecucion  
	pila despues de la ejecucion.  

Por ejemplo:  
```
ebp            0x0      	0x0  
esp            0xffffd2ac       0xffffd2ac  
eip            0x565561e0       0x565561e0 <main>  
0x565561e0 <main>       	push   ebp  
; se guarda la direccion de la base que llamo a main  
; para ello primero se decrementa esp (cada que se hace push )y se inserta en la pila el valor  
| ebp = 0 | <- 0xffffd2a8 = esp
```
#### Tarea 4:
Contestar el cuestionario https://forms.gle/hs99n8uku8FU84xc7

## Practicas
#### Practica 1  
Generar un programa que cifre una cadena con al menos  5 instrucciones de ensamblador distintas, al menos una de  las instrucciones debe ser SHR o SHL con un corrimiento  mínimo de 3.  
Entregar el ASM y el binario.

#### Practica 2  
Generar un programa que descifre la cadena previamente  cifrada.  

#### Practica 3
Instalar Android Studio https://developer.android.com/studio y crear un AVD con la API 25.  
Agregar la instalacion al path, de manera que los binarios emulator y adb, puedan utilizarse globalmente.  


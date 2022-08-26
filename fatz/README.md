# Fatz Code
 
## Go, Instalación en Windows y Primera aplicación en VSCode 
Pasos para instalar Go en VS Code segun el vídeo [YTB-channel=FatzCode-video=Go, Instalación en Windows y Primera aplicación en VSCode](https://www.youtube.com/watch?v=lQVhwSJpkqg&ab_channel=FaztCode)

- Instalar el programa desde la web oficial https://go.dev/doc/install
  
- Seguir las instucciones del video:
  
    - Creamos el fichero go.mod que contiene las librerias y módulos de los que depende el proyecto con la instrucción.

``` bash
go mod init github.com/jescuderobus/go-agosto
```
    - Al crear el fichero main.go, VS Code nos ofrecera instalar las extensiones para GO, le damos a "Instalar TODAS"
    - Creamos el Fichero en Go que muestre por pantalla "Hola Mundo"
```
package main

import "fmt"

func main(){
	fmt.Println("Hello World")
}
```
    - Desde un terminal se ejecuta con el comando "go run ."
    - Para construir el fichero ejecutable se ejecuta el comando "go build ."

----
 
 Veamos ahora como modificar el fichero main para que nos dé un uuid distinto cada vez que lo ejecutemos.

``` bash
go get github.com/google/uuid
```




 
# Saludos en Go

Este paquete envia envia un saludos simple aliatoriamente

# Instalación
Ejecuta el siguente comando para la instalación del paquete

```bash
go get -u github.com/Juanjonet77/greetings
```

# Uso

Aqui tienes un ejemplo de como utilizarlo

```go
package main

import (
    "fmt"
    "github.com/Juanjonet77/greetings"
)

func main ()  {
    
    message, err := greetings.Hello("Juanjo")
    if err !=nil {
        fmt.Println("Ocurrio un error: ",err)
        return
    }
    fmt.Println(message)
}


```
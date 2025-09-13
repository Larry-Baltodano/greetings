# Saludos en Go

Este paquete proprociona una forma simple de obtener saludos personalizados.

## Instalación
Ejecuta el siguiente comando para instalar el paquete:
```bash
go get -u github.com/Larry-Baltodano/greetings
```

## Uso
Aqui tienes un ejemplo de cómo utilizar el paquete en tu código:
```bash
packege main

import (
    "fmt"
    "github.com/Larry-Baltodano/greetings"
)

func main() {
    message, err := greetings.Hello("Larry")

    if err != nil {
        fmt.Println("Ocurrió un error:", err)
        return
    }

    fmt.Println(message)
}
```

Este ejemplo importa el paquete github.com/Larry-Baltodano/greetings y llama a la funcion Hello para un saludo personalizado. Si ocurre un error, se imprime un mensaje de error.
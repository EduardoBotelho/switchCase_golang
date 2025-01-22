# Programa de Exemplo em Go (Example Program in Go)

## Descrição (Description)

Este programa em Go demonstra o uso do laço `for` combinado com uma declaração `switch` para iterar de 0 a 5 e imprimir os nomes dos números em português. Cada número é identificado em seu respectivo caso no `switch`. (This Go program demonstrates the use of a `for` loop combined with a `switch` statement to iterate from 0 to 5 and print the names of numbers in Portuguese. Each number is identified in its respective case in the `switch`.)

## Como Funciona (How It Works)

1. Um laço `for` é usado para iterar de 0 a 5. (A `for` loop is used to iterate from 0 to 5.)
2. Para cada valor de `i`, a declaração `switch` verifica o número e imprime o nome correspondente em português. (For each value of `i`, the `switch` statement checks the number and prints the corresponding name in Portuguese.)
3. O programa termina após imprimir todos os números de 0 a 5. (The program terminates after printing all numbers from 0 to 5.)

## Saída Esperada (Expected Output)

Ao executar o programa, a saída será: (When running the program, the output will be:)

```
Zero
Um
Dois
Três
Quatro
Cinco
```

## Como Executar (How to Run)

1. Certifique-se de ter o Go instalado na sua máquina. (Ensure you have Go installed on your machine.)
2. Salve o código em um arquivo chamado `main.go`. (Save the code in a file named `main.go`.)
3. Abra o terminal, navegue até o diretório onde o arquivo está salvo e execute: (Open the terminal, navigate to the directory where the file is saved, and run:)

   ```bash
   go run main.go
   ```

4. Você verá a saída no terminal. (You will see the output in the terminal.)

## Código (Code)

```go
package main

import "fmt"

func main() {

	for i := 0; i <= 5; i++ {

		switch i {
		case 0:
			fmt.Println("Zero")
		case 1:
			fmt.Println("Um")
		case 2:
			fmt.Println("Dois")
		case 3:
			fmt.Println("Três")
		case 4:
			fmt.Println("Quatro")
		case 5:
			fmt.Println("Cinco")
		}
	}
}
```

## Licença (License)

Este programa é gratuito para uso e modificação. (This program is free for use and modification.)

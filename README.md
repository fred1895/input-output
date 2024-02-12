<h1>Entrada -> Processamento -> Saída de dados</h1>

Todo sistema, do mais básico ao complexo, se baseia nesses 3 pilares. Neste repositório há 3 exemplos disso, nas linguagens **[Javascript](https://github.com/fred1895/input-output/blob/master/in-out.js)**, **[Go](https://github.com/fred1895/input-output/blob/master/in-out.go)** e **[Python](https://github.com/fred1895/input-output/blob/master/in-out.py)**.

### Melhoria do código e exercícios
Antes de tudo, aqui estão alguns sites para você praticar as 3 llinguagens online:
- [Javascript](https://playcode.io/javascript)
- [Go](https://go.dev/play/)
- [Python](https://www.online-python.com/)

#### Funções
Que tal adicionarmos uma funcionalidade onde, um bloco de código, executa uma determinada ação. Esse bloco de código é chamado de função. Essa funcionalidade recebe alguns dados, que são chamados de parâmetros. Após receber esses dados, esse bloco de código processa os dados e retorna algum resultado específico ou simplesmente apenas executa a ação desejada.

Por exemplo, nos exemplos deste respositório, os dados estão sendo processados para retornar o número da entrada multiplicado por três. Que tal colocarmos essa ação, de multiplicar por três em uma função e executar a função.

Para visualizar melhor como isso é feito, aqui está um exemplo de uma função de soma nas três linguagens:

##### Javascript
- Código sem função
```
firstNumber = 5;
secondNumber = 10;

sum = firstNumber + secondNumber;

console.log(`Sum of ${firstNumber} and ${secondNumber} is ${sum}`);
```
<br>

- Código com função
```
firstNumber = 5;
secondNumber = 10;

sum = sumNumbers(firstNumber, secondNumber);

console.log(`Sum of ${firstNumber} and ${secondNumber} is ${sum}`);

function sumNumbers(a, b) {
    return a + b;
}
```

Neste código JavaScript, declaramos uma função chamada sumNumbers para calcular a soma de dois números. Em seguida, declaramos as variáveis firstNumber e secondNumber, chamamos a função sumNumbers para calcular a soma e, finalmente, imprimimos o resultado usando console.log

##### Golang
- Código sem função
```
func main() {
    firstNumber := 5
    secondNumber := 10

    sum := firstNumber + secondNumber;

    fmt.Printf("Sum of %d and %d is %d\n", firstNumber, secondNumber, sum)
}

func sumNumbers(a, b int) int {
    return a + b
}
```
<br>

- Código com função
```
func main() {
    firstNumber := 5
    secondNumber := 10

    sum := sumNumbers(firstNumber, secondNumber)

    fmt.Printf("Sum of %d and %d is %d\n", firstNumber, secondNumber, sum)
}

func sumNumbers(a, b int) int {
    return a + b
}
```
Neste código Go, declaramos as variáveis firstNumber e secondNumber, chamamos a função sumNumbers para calcular a soma e, em seguida, imprimimos o resultado usando fmt.Printf. A função sumNumbers é definida para calcular a soma dos números fornecidos.

##### Python
- Código sem função
```
def sumNumbers(a, b):
    return a + b

firstNumber = 5
secondNumber = 10

sum_result = firstNumber + secondNumber;

print(f"Sum of {firstNumber} and {secondNumber} is {sum_result}")
```
<br>

- Código com função
```
def sumNumbers(a, b):
    return a + b

firstNumber = 5
secondNumber = 10

sum_result = sumNumbers(firstNumber, secondNumber)

print(f"Sum of {firstNumber} and {secondNumber} is {sum_result}")
```
Neste código Python, definimos a função sumNumbers para calcular a soma de dois números. Em seguida, declaramos as variáveis firstNumber e secondNumber, chamamos a função sumNumbers para calcular a soma e, finalmente, imprimimos o resultado usando print.

## Exercício
Tente fazer uma função que execute a ação de multiplicar por três os números fornecido. Faça as mudanças necessárias no código para isso.

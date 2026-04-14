Foi feita solicitado a IA que fizesse uma calculadora em Java, que tivesse interface gráfica.
Esse foi o prompt utilizado: Faça uma calculadora básica, que contenha as 4 operações, faça usando JavaScript
Esse foi o resultado obtido:

function calculadora(num1, num2, operacao) {
    switch (operacao) {
        case "+":
            return num1 + num2;
        case "-":
            return num1 - num2;
        case "*":
            return num1 * num2;
        case "/":
            if (num2 === 0) {
                return "Erro: divisão por zero";
            }
            return num1 / num2;
        default:
            return "Operação inválida";
    }
}

Segue abaixo, provas da interação com a IA:

<img width="699" height="503" alt="Image" src="https://github.com/user-attachments/assets/a6d56efd-9632-490a-a4da-9a327c5f8080" />

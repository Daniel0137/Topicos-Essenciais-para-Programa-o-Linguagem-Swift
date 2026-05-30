# Exemplos de código

### Gustavo Rorigo
---
Calculadora

    import Foundation

    func calculadora(num1: Double, num2: Double, operacao: String) {
        switch operacao {
        case "+":
            print("Resultado: \(num1 + num2)")
        case "-":
            print("Resultado: \(num1 - num2)")
        case "*":
            print("Resultado: \(num1 * num2)")
        case "/":
            if num2 != 0 {
                print("Resultado: \(num1 / num2)")
            } else {
                print("Erro: divisão por zero!")
            }
        default:
            print("Operação inválida!")
        }
    }

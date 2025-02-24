# Exercício em TypeScript

Este exercício consiste na criação de duas funções utilizando **TypeScript** com tipagem adequada. Abaixo está a descrição do que foi solicitado e como foi implementado.

## Descrição do Exercício

1. **Função de Multiplicação**:
   - Deve receber como argumentos dois números.
   - Retorna a multiplicação dos dois números.

2. **Função de Saudação**:
   - Deve receber como argumento uma string representando um nome.
   - Retorna a concatenação da saudação: `"Olá " + nome`.

## Estrutura do Código

```typescript
// Função de multiplicação
function multiplicacao(numberOne: number, numberTwo: number): number {
    return numberOne * numberTwo;
}

// Função de saudação
function saudacao(nome: string): string {
    return `Olá ${nome}`;
}

// Exemplos de uso
console.log(multiplicar(5, 3)); // Saída: 15
console.log(saudacao("Matheus")); // Saída: Olá Matheus
```

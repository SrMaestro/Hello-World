Hello World em várias linguagens
Olá, Mundo! em 6 Linguagens Diferentes, Incluindo Assembly
O tradicional "Olá, Mundo!" é um dos primeiros programas que muitos aprendizes de programação criam. Ele serve como uma introdução básica à sintaxe de uma linguagem e ao processo de execução de um programa. Vamos ver como ele se parece em algumas das linguagens mais populares, incluindo Assembly:
Observação: O código em Assembly pode variar significativamente dependendo da arquitetura do processador e do assembler utilizado. O exemplo abaixo é uma aproximação e pode precisar de ajustes para funcionar em um sistema específico.
Python
Python
print("Olá, Mundo!")

Use o código com cuidado.
JavaScript
JavaScript
console.log("Olá, Mundo!");

Use o código com cuidado.
C++
C++
#include <iostream>

int main() {
    std::cout << "Olá, Mundo!" << std::endl;
    return 0;
}

Use o código com cuidado.
Java
Java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Olá, Mundo!");
    }
}

Use o código com cuidado.
Assembly (x86)
Snippet de código
section .data
    msg db 'Olá, Mundo!', 0x0A

section .text
    global _start

_start:
    mov eax, 4
    mov ebx, 1
    mov ecx, msg
    mov edx, 12 ; Tamanho da mensagem
    int 0x80

    mov eax, 1
    mov ebx, 0
    int 0x80

Use o código com cuidado.


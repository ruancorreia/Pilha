Conceito de Pilha em Estruturas de Dados
A pilha é uma estrutura de dados linear que segue o princípio LIFO (Last In, First
Out), ou seja, o último elemento inserido é o primeiro a ser removido. Essa estrutura é
comparável a uma pilha de pratos: o último prato colocado no topo é o primeiro a ser
retirado.
As principais operações de uma pilha são:
1. push() – Insere um elemento no topo da pilha.
2. pop() – Remove e retorna o elemento do topo da pilha.
3. peek() – Retorna o elemento do topo sem removê-lo.
4. isEmpty() – Verifica se a pilha está vazia.
5. size() – Retorna a quantidade de elementos na pilha.
A pilha pode ser implementada de diferentes formas:
• Usando arrays (estrutura estática).
• Usando listas encadeadas (estrutura dinâmica).

Implementação de Pilha em Java
Podemos implementar uma pilha de duas maneiras em Java: usando arrays ou listas
encadeadas. Além disso, a própria linguagem fornece a classe Stack na biblioteca
java.util.

# Estrutura de Dados em C / Data Structures in C

[![Language](https://img.shields.io/badge/language-C-blue.svg)](https://en.wikipedia.org/wiki/C_(programming_language))
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains C implementations of fundamental data structures and solutions to competitive programming problems. It was developed for the Data Structures course.

<details>
<summary>🇧🇷 Ver em Português</summary>

Este repositório contém implementações em C de estruturas de dados fundamentais e soluções para problemas de programação competitiva, desenvolvido para a disciplina de Estrutura de Dados.

</details>

---

## 📂 Repository Structure

The project is organized into two main directories:

-   `./data_structure/`: Contains generic implementations of common data structures. Each structure is located in its own directory, typically with an interface (`.h`), an implementation (`.c`), and a test client (`main.c` or `client.c`).
-   `./beecrowd/`: Contains solutions to problems from the [Beecrowd](https://www.beecrowd.com.br/) platform (formerly URI Online Judge). Each subdirectory is named after the problem ID and includes the source code and a sample input file (`in.txt`).

<details>
<summary>🇧🇷 Estrutura do Repositório</summary>

O projeto está organizado em dois diretórios principais:

-   `./data_structure/`: Contém implementações genéricas de estruturas de dados comuns. Cada estrutura está localizada em seu próprio diretório, geralmente com uma interface (`.h`), uma implementação (`.c`) e um cliente de teste (`main.c` ou `client.c`).
-   `./beecrowd/`: Contém soluções para problemas da plataforma [Beecrowd](https://www.beecrowd.com.br/) (antigo URI Online Judge). Cada subdiretório é nomeado com o ID do problema e inclui o código-fonte e um arquivo de entrada de exemplo (`in.txt`).

</details>

## ✨ Data Structures Implemented

This repository provides implementations for the following data structures:

-   **List**
    -   `contiguous/`: Array-based list with dynamic resizing.
    -   `linked/`: Singly linked list.
    -   `doubly_linked/`: Doubly linked list.
-   **Stack**
    -   `contiguous/`: Array-based stack.
    -   `linked/`: Linked list-based stack.
-   **Hash Table**
    -   `hash_table/`: Hash table with separate chaining for collision resolution.
-   **Tree**
    -   `binary_tree/`: Binary Search Tree.
-   **Heap**
    -   `max_heap/`: Max Heap.
-   **Bitfield**
    -   `bitfield/`: A simple bit array.

<details>
<summary>🇧🇷 Estruturas de Dados Implementadas</summary>

Este repositório fornece implementações para as seguintes estruturas de dados:

-   **Lista**
    -   `contiguous/`: Lista baseada em array com redimensionamento dinâmico.
    -   `linked/`: Lista simplesmente encadeada.
    -   `doubly_linked/`: Lista duplamente encadeada.
-   **Pilha (Stack)**
    -   `contiguous/`: Pilha baseada em array.
    -   `linked/`: Pilha baseada em lista encadeada.
-   **Tabela Hash (Hash Table)**
    -   `hash_table/`: Tabela Hash com encadeamento separado para resolução de colisões.
-   **Árvore (Tree)**
    -   `binary_tree/`: Árvore Binária de Busca.
-   **Heap**
    -   `max_heap/`: Max Heap.
-   **Bitfield**
    -   `bitfield/`: Um array de bits simples.

</details>

## 🏆 Beecrowd Problem Solutions

This repository includes solutions for the following problems on Beecrowd:

-   [1022 - TDA Rational](https://www.beecrowd.com.br/judge/en/problems/view/1022)
-   [1062 - Rail](https://www.beecrowd.com.br/judge/en/problems/view/1062)
-   [1063 - Rails](https://www.beecrowd.com.br/judge/en/problems/view/1063)
-   [1069 - Diamonds and Sand](https://www.beecrowd.com.br/judge/en/problems/view/1069)
-   [1077 - Infix to Postfix](https://www.beecrowd.com.br/judge/en/problems/view/1077)
-   [1110 - Throwing Cards Away](https://www.beecrowd.com.br/judge/en/problems/view/1110)
-   [1256 - Hash Tables](https://www.beecrowd.com.br/judge/en/problems/view/1256)

<details>
<summary>🇧🇷 Soluções de Problemas Beecrowd</summary>

Este repositório inclui soluções para os seguintes problemas no Beecrowd:

-   [1022 - TDA Racional](https://www.beecrowd.com.br/judge/pt/problems/view/1022)
-   [1062 - Trilhos](https://www.beecrowd.com.br/judge/pt/problems/view/1062)
-   [1063 - Trilhos de Novo](https://www.beecrowd.com.br/judge/pt/problems/view/1063)
-   [1069 - Diamantes e Areia](https://www.beecrowd.com.br/judge/pt/problems/view/1069)
-   [1077 - Infixa para Posfixa](https://www.beecrowd.com.br/judge/pt/problems/view/1077)
-   [1110 - Jogando Cartas Fora](https://www.beecrowd.com.br/judge/pt/problems/view/1110)
-   [1256 - Tabelas Hash](https://www.beecrowd.com.br/judge/pt/problems/view/1256)

</details>

## 🚀 How to Compile and Run

You can compile the source files using a C compiler like GCC.

#### Example: Compiling a data structure test client

```bash
# Navigate to a data structure directory, e.g., binary_tree
cd data_structure/binary_tree

# Compile the files
gcc binary_tree.c main.c -o binary_tree_test

# Run the executable
./binary_tree_test
```

#### Example: Compiling and running a Beecrowd solution

```bash
# Compile the main source file for a problem
gcc beecrowd/1022/main.c -o solution_1022

# Run the solution, using the provided input file
./solution_1022 < beecrowd/1022/in.txt
```

<details>
<summary>🇧🇷 Como Compilar e Executar</summary>

Você pode compilar os arquivos-fonte usando um compilador C como o GCC.

#### Exemplo: Compilando um cliente de teste de estrutura de dados

```bash
# Navegue até o diretório de uma estrutura, ex: binary_tree
cd data_structure/binary_tree

# Compile os arquivos
gcc binary_tree.c main.c -o teste_arvore_binaria

# Execute o programa
./teste_arvore_binaria
```

#### Exemplo: Compilando e executando uma solução do Beecrowd

```bash
# Compile o arquivo principal de um problema
gcc beecrowd/1022/main.c -o solucao_1022

# Execute a solução, usando o arquivo de entrada
./solucao_1022 < beecrowd/1022/in.txt
```

</details>

## ⚖️ License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

<details>
<summary>🇧🇷 Licença</summary>

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

</details>

---

_Developed by [Lucas E Neiva](https://github.com/lucaseneiva)._

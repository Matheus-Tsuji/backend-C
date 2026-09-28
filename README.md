# Backend em C

Este repositório contém um sistema de cadastro de produtos desenvolvido em **C puro**.

## Sobre o Projeto
O diferencial deste projeto é a implementação de uma **Interface Gráfica (GUI)** construída nativamente utilizando a **API do Windows (Win32)**, demonstrando que é possível criar janelas, botões e campos de texto sem depender de bibliotecas externas complexas (como Qt ou GTK), utilizando apenas as bibliotecas padrão do Windows (`windows.h`).

## Funcionalidades
- **Interface Gráfica Nativa**: Janela interativa para interação com o usuário.
- **Cadastro de Produtos**: Adição de novos produtos (Código, Nome, Quantidade e Preço).
- **Listagem de Produtos**: Visualização dos produtos cadastrados.
- **Persistência de Dados**: Os dados são salvos em um arquivo de texto (`produto_interface.txt`), permitindo que as informações não sejam perdidas ao fechar o programa.

## Como Executar
O repositório já contém o arquivo executável (`BackendC.exe`). Para utilizá-lo, basta baixar o projeto e abrir o executável no Windows.

Caso queira compilar o código fonte manualmente com o GCC (MinGW):
```bash
gcc main.c -o BackendC.exe -mwindows
```

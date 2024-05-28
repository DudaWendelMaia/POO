# 📚 Automatização da Biblioteca

<div align="center"> 
<img width="300" height="200" src="https://img.freepik.com/fotos-premium/jogo-de-xadrez-com-rainha-dourada-e-pecas-de-xadrez-prateadas-em-fundo-escuro-representando-equipe-de-lideranca_908985-40886.jpg">
</div>

## ℹ️ Informações
- **Autores:** Maria Maia
- **Data:** 08/04/2023
- **Linguagem:** Java
- **Status:** Concluído
- **Descrição:** Solução do problema da automatização da biblioteca.
- **Link:** https://github.com/DudaWendelMaia/POO

## 🎯 Problema
O trabalho consiste em desenvolver um aplicativo para automatizar o gerenciamento de livros e autores em um catálogo. O sistema deve incluir as seguintes classes principais:

- **Biblioteca**: Responsável pelo cadastro e pesquisa de livros por ISBN e ano.
- **Grupo**: Gerencia o cadastro de autores por código.
- **Livro**: Representa um livro com métodos para adicionar autores.
- **Autor**: Representa um autor com métodos para adicionar livros e listar seus livros.
- **ACMEPublishing**: Classe principal que coordena a execução do sistema através do método executa(), lendo dados de um arquivo de texto e realizando operações de cadastro e consulta.
- **Main**: Classe inicial do sistema que instancia ACMEPublishing e inicia a execução.

O sistema deve ler um arquivo de texto ('dados.txt'), processando operações como cadastrar livros, cadastrar autores, adicionar livros a autores, e realizar consultas específicas. As saídas são formatadas conforme especificações, mostrando quantidades cadastradas e detalhes dos livros e autores conforme operações são concluídas com sucesso.

## ▶️ Como Executar
Certifique-se de ter o JDK instalado. Clone o repositório e compile o código Java.

1. Clone o repositório:
    ```sh
    https://github.com/DudaWendelMaia/POO
    ```

2. Navegue até a pasta do projeto:
    ```sh
    cd Trabalho1
    ```

3. Compile o código:
    ```sh
      javac Main.java
    ```

4. Execute o programa:
    ```sh
      java Main
    ```

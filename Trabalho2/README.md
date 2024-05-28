# 💿 Acervo Audiovisual

<div align="center"> 
<img width="200" height="200" src="https://png.pngtree.com/png-clipart/20220117/original/pngtree-audio-visual-audio-visual-play-promotional-video-mobile-internet-2-5d-png-image_7150034.png">
</div>

## ℹ️ Informações
- **Autores:** Maria Maia
- **Data:** 10/05/2023
- **Linguagem:** Java
- **Status:** Concluído
- **Descrição:** Solução do problema da automatização da biblioteca.
- **Link:** https://github.com/DudaWendelMaia/POO

## 🎯 Problema

A ACMEFun comercializa itens de audiovisual (blu-rays e games) e possui dados do acervo em um arquivo-texto. A empresa deseja uma aplicação para processar esses dados, e você será responsável pelo desenvolvimento.

### Especificações da Aplicação

#### Interface `Cobravel`

1. `calculaPrecoVenda()`: Calcula e retorna o preço de venda de um item.
2. `calculaImposto()`: Calcula e retorna o valor do imposto de um item.

#### Subclasses da Classe Abstrata `Audiovisual`

1. **BluRay**: Possui duração (em minutos).
   - Preço de venda: \((preço \, base \times duração) / 100\)
   - Imposto: 40% do preço de venda.
2. **Game**: Possui categoria (ACAO, ESPORTE, ESTRATEGIA, SIMULACAO, RPG).
   - Preço de venda: Preço base + percentual conforme a categoria:
     - ACAO: 20%
     - ESPORTE: 30%
     - ESTRATEGIA: 40%
     - SIMULACAO: 50%
     - RPG: 70%
   - Imposto: 50% do preço de venda.

#### Método `executa()` da Classe `App`

1. **Ler audiovisuais**: Lê os dados e escreve a quantidade de itens carregados: `1;quantidade de itens carregados`.
2. **Escrever informações dos itens**: Escreve informações para cada item: `2;título;valor do preço final;valor do imposto`.
3. **Contar games RPG**: Escreve a quantidade de games RPG: `3;quantidade de games RPG`.
4. **BluRay com imposto mais próximo da média**: Calcula a média dos impostos dos BluRays e escreve o BluRay com imposto mais próximo da média: `4;média dos valores de impostos de BluRays;título do BluRay com imposto mais próximo da média`. Caso não haja BluRays: `4:Nenhum BluRay`.

#### Entrada e Saída de Dados

- **Entrada**: Arquivo `dados.csv`.
- **Saída**: Arquivo `resultado.csv`.

## ▶️ Como Executar
Certifique-se de ter o JDK instalado. Clone o repositório e compile o código Java.

1. Clone o repositório:
    ```sh
    https://github.com/DudaWendelMaia/POO
    ```

2. Navegue até a pasta do projeto:
    ```sh
    cd Trabalho2
    ```

3. Compile o código:
    ```sh
      javac Main.java
    ```

4. Execute o programa:
    ```sh
      java Main
    ```


# Conversor de Moedas Java

Este é um projeto de um Conversor de Moedas desenvolvido em Java. O objetivo principal é permitir que os usuários realizem conversões entre diferentes moedas, utilizando taxas de câmbio obtidas dinamicamente de uma API. A interação com o usuário é feita via console, oferecendo um menu com no mínimo 6 opções de conversão e suporte para os idiomas Português e Inglês.

## Funcionalidades

* **Múltiplas Conversões:** Oferece opções de conversão entre USD, EUR, GBP, JPY, BRL e CAD.
* **Taxas de Câmbio Dinâmicas:** As taxas de conversão são obtidas em tempo real através da API [exchangerate-api.com](https://www.exchangerate-api.com).
* **Interface via Console:** A interação com o usuário é realizada através do console.
* **Suporte a Múltiplos Idiomas:** O conversor oferece suporte para os idiomas Português e Inglês.

## Como Funciona

O processo de desenvolvimento deste conversor envolveu as seguintes etapas:

1.  **Configuração do Ambiente Java:** Preparação do ambiente de desenvolvimento Java.
2.  **Criação do Projeto:** Inicialização do projeto Java.
3.  **Consumo da API:** Realização de requisições à API de taxas de câmbio para obter os dados necessários.
4.  **Análise da Resposta JSON:** Processamento da resposta da API, que está no formato JSON.
5.  **Filtro de Moedas:** Seleção e tratamento das moedas de interesse (USD, EUR, GBP, JPY, BRL, CAD).
6.  **Exibição de Resultados aos Usuários:** Apresentação das opções de conversão e dos resultados para o usuário no console, com suporte a Português e Inglês.

## Organização do Desenvolvimento (Trello)

Para acompanhar o desenvolvimento deste projeto, utilizei o Trello com as seguintes colunas:

* **Pronto pra iniciar:** Tarefas que ainda não foram iniciadas.
* **Desenvolvendo:** Tarefas que estão sendo desenvolvidas no momento.
* **Pausado:** Tarefas que foram iniciadas, mas estão temporariamente interrompidas.
* **Concluído:** Tarefas que já foram finalizadas.

**Observação:** O Trello é uma ferramenta para controle individual do progresso e não será avaliada.

## Como Executar

1.  Clone este repositório para sua máquina local.
2.  Certifique-se de ter o Java Development Kit (JDK) instalado.
3.  Compile os arquivos `.java`:
    ```bash
    javac Main.java ExchangeRateFetcher.java
    ```
4.  Execute o programa:
    ```bash
    java Main
    ```
5.  Siga as instruções no console para escolher o idioma e realizar as conversões.

## Código Fonte

O código fonte principal está nos seguintes arquivos:

* `Main.java`: Contém a lógica principal da aplicação, incluindo a interação com o usuário e a chamada para a busca de taxas.
* `ExchangeRateFetcher.java`: Responsável por fazer a requisição à API de taxas de câmbio e obter os dados.

## Autor

[Yuri - Aluno Oracle next Education]
Atividade proposta - Challenge

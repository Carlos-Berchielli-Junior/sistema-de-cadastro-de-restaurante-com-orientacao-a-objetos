# 🍽️ Sistema de Gerenciamento de Restaurantes

Este é um projeto desenvolvido em Python com foco em **Programação Orientada a Objetos (POO)**. Trata-se de um sistema de linha de comando (CLI) que permite criar restaurantes, gerenciar seus status de funcionamento e receber avaliações de clientes, calculando automaticamente a média de notas.

## 🚀 Funcionalidades

* **Cadastro de Restaurantes:** Criação de restaurantes com nome e categoria.
* **Gestão de Status:** Alternância do status do restaurante entre ativo (✅) e inativo (❌).
* **Sistema de Avaliações:** Capacidade de receber múltiplas avaliações de clientes diferentes para um mesmo restaurante.
* **Cálculo de Média Dinâmico:** O sistema calcula a média de notas de forma automática sempre que os restaurantes são listados.
* **Listagem Formatada:** Exibição em tabela no terminal mostrando o nome, categoria, nota média e status atual de cada restaurante cadastrado.

## 📂 Estrutura do Projeto

O projeto foi refatorado para seguir boas práticas de separação de responsabilidades (Modularização e Composição), contendo três arquivos principais:

* `app.py`: É o arquivo principal (entry point) do programa. Ele importa as classes e executa o código.
* `modelos/restaurante.py`: Contém a classe `Restaurante`. Responsável por gerenciar os dados do restaurante, armazenar as avaliações e ditar as regras de negócio.
* `modelos/avaliacao.py`: Contém a classe `Avaliacao`. Uma classe modelo focada unicamente em estruturar os dados do cliente e a nota que ele deu.

# Calculadora de IMC - Flutter

**Desenvolvido por:** Gabriel do Carmo Felipe  
**Disciplina:** PAM (Programação de Aplicativos Mobile)

Projeto de uma aplicação para cálculo do Índice de Massa Corporal (IMC), desenvolvido utilizando Flutter e Dart como atividade prática da disciplina de Programação de Aplicativos Mobile, orientada pelo Prof. Nilson J. Alcides.

## Tecnologias utilizadas

- **Dart:** linguagem de programação utilizada para desenvolver a lógica do aplicativo.
- **Flutter:** framework utilizado para desenvolver a interface e os componentes da aplicação.

## Funcionalidades

- Entrada de dados de peso (kg) e altura (cm).
- Conversão da altura de centímetros para metros.
- Cálculo automático do IMC utilizando a fórmula peso / altura².
- Exibição do resultado com sua respectiva classificação.
- Botão de atualização para limpar os campos e reiniciar o cálculo.

## Componentes e conceitos utilizados

Durante o desenvolvimento, foram utilizados conceitos e widgets do Flutter, como:

- `StatefulWidget` e `setState()` para gerenciamento do estado da aplicação.
- `Scaffold` e `AppBar` para estruturar a tela.
- `TextField` e `TextEditingController` para entrada e controle dos dados.
- `ElevatedButton` para executar o cálculo.
- `IconButton` para reiniciar a aplicação.
- `Column`, `Padding` e `Container` para organizar os elementos da interface.
- `SingleChildScrollView` para permitir a rolagem da tela.
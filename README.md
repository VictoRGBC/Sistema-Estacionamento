# 🚗 Sistema de Estacionamento em C#

Este é um projeto simples em C# que simula um sistema de estacionamento. A aplicação permite cadastrar veículos, removê-los com cálculo do valor a ser pago pelo tempo estacionado, e listar os veículos atualmente no estacionamento.

## 🎯 Objetivo do Projeto

Este sistema foi desenvolvido com o propósito de **estudar lógica de programação** e os **princípios da programação orientada a objetos (POO)** em C#. Ele serve como base prática para fixar conceitos fundamentais como classes, objetos, métodos, encapsulamento e manipulação de listas.

## 📋 Funcionalidades

- ✅ Cadastro de veículos (nome e número)
- ✅ Remoção de veículos com cálculo do valor a pagar
- ✅ Listagem de todos os veículos estacionados
- ✅ Interface via terminal/console

## 📁 Estrutura do Projeto

```
SistemaEstacionamento/
├── Program.cs                    # Ponto de entrada da aplicação
├── Entities/
│   ├── Estacionamento.cs        # Lógica principal do sistema de estacionamento
│   └── Veiculo.cs               # Representação de um veículo
```

## ▶️ Como Executar

1. **Clone o repositório** ou copie os arquivos para seu ambiente de desenvolvimento:
   ```bash
   git clone https://github.com/seu-usuario/sistema-estacionamento.git
   ```

2. **Abra o projeto no Visual Studio** ou outro editor compatível com C#.

3. **Compile e execute o programa.**

4. Siga as instruções exibidas no terminal:
   - Digite o **preço inicial** e o **preço por hora**.
   - Escolha uma opção no menu:
     ```
     1 - Cadastrar veiculo
     2 - Remover veiculo
     3 - Listar veiculos
     4 - Encerrar
     ```

## 💡 Exemplo de Uso

```
Seja bem-vindo ao sistema de estacionamento!
Digite o preço inicial: 5
Digite o preço por hora: 2

Digite a sua opcao:
1 - Cadastrar veiculo
2 - Remover veiculo
3 - Listar veiculos
4 - Encerrar
```

## 🧱 Tecnologias Utilizadas

- Linguagem: **C# (.NET)**
- Plataforma: **Console Application**
- Paradigma: **Programação Orientada a Objetos**

## ✍️ Autor

Desenvolvido por Victor como exercício de aprendizado.

# Bank System (Java Console)

Sistema bancário em **Java (console)** criado para praticar **Lógica**, **POO** e **boas práticas de organização de código**.

> Projeto de estudo com foco em Backend (base), preparando evolução para API com Spring Boot no futuro.

---

## ✨ Funcionalidades

- Cadastro de cliente (Nome, CPF, Data de nascimento)
- Depósito
- Saque (com validações)
- Extrato (saldo atual / informações da conta)
- Menu interativo no terminal

---

## 🧠 Conceitos praticados

- Programação Orientada a Objetos (Classes, atributos, métodos)
- Encapsulamento (ex: saldo privado)
- Validação de entradas (CPF apenas números, valores inválidos, etc.)
- Organização por arquivos (`App.java`, `Usuarios.java`)
- Fluxo de execução com menu (switch/case)

---

## 🛠️ Tecnologias

- Java (Console)
- VS Code
- Git/GitHub

---

## ▶️ Como executar

### Opção 1 — VS Code
1. Abra a pasta do projeto no VS Code
2. Abra o arquivo `src/App.java`
3. Clique em **Run** (ou execute pelo menu do Java)

### Opção 2 — Terminal
> (Ajuste o caminho se necessário)

```bash
# entrar na pasta do projeto
cd bank-system-java

# compilar
javac -d bin src/*.java

# executar
java -cp bin App
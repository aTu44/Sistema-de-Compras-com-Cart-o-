# 💳 Sistema de Compras com Cartão

Este projeto em **Java** simula um sistema de gestão de compras com cartão de crédito. Ele permite que usuários configurem um limite de crédito, realizem compras e acompanhem o saldo disponível em tempo real.

---

## 🚀 Funcionalidades

- Definir limite inicial do cartão
- Inserir compras com **descrição** e **valor**
- Verificar se a compra pode ser realizada com o saldo atual
- Armazenar e exibir a lista de compras concluídas
- Atualizar o saldo após cada compra
- Exibir saldo restante ao final

---

## 🏗️ Estrutura do código

- **Classe `Cartao`**  
  Gerencia o limite de crédito, saldo disponível e lista de compras aprovadas.

- **Classe `Compras`**  
  Representa uma compra individual, contendo a descrição e o valor.

---

## 💡 Como funciona

1. O usuário define o limite do cartão de crédito.
2. O programa solicita a descrição e o valor de cada compra.
3. Se houver saldo suficiente, a compra é aprovada e adicionada à lista.
4. Caso contrário, a compra é recusada.
5. O usuário pode continuar adicionando compras até decidir parar ou até o saldo não permitir mais novas compras.
6. Ao finalizar, o sistema exibe todas as compras aprovadas e o saldo restante.

---

## ⚙️ Requisitos

- **Java JDK 8** ou superior
- IDE Java (por exemplo: IntelliJ, Eclipse, NetBeans) ou terminal com compilador Java

---

## ▶️ Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/aTu44/Sistema-de-Compras-com-Cart-o-.git
   ```
2. Compile os arquivos Java:
   ```bash
   javac Cartao.java Compras.java Main.java
   ```
3. Execute o programa:
   ```bash
   java Main
   ```

---

## 💬 Observações

- O sistema foi desenvolvido como um exercício de prática em Programação Orientada a Objetos (POO) em Java.
- O código é simples e didático, pensado para iniciantes consolidarem conceitos como **classes**, **objetos**, **atributos** e **métodos**.

---


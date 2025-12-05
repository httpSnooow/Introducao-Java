# ☕ Java: Da Lógica à Aplicação Desktop

> Um repositório documental da minha jornada de estudos em Java, evoluindo dos conceitos fundamentais de lógica e POO até a construção de uma aplicação desktop funcional com persistência de dados.

<div align="center">

  ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
  ![Swing](https://img.shields.io/badge/Java_Swing-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
  ![IO](https://img.shields.io/badge/Java%20serialização-brown?style=for-the-badge&logo=files&logoColor=white)

</div>

---

## 🏆 Destaque: Agenda de Contatos (CRUD)

O projeto principal deste repositório é uma aplicação desktop completa para gerenciamento de contatos. Ela consolida todo o aprendizado em **Interface Gráfica** e **Persistência de Arquivos**.

### 📸 Funcionalidades
A aplicação implementa um ciclo completo de **CRUD** (Create, Read, Update, Delete) com as seguintes capacidades:

| Operação | Descrição |
| :--- | :--- |
| 🆕 **Incluir** | Adiciona novos contatos à lista através de formulários validados. |
| 🔍 **Consultar** | Sistema de busca dinâmica por nome ou código do contato. |
| ✏️ **Alterar** | Permite a edição de dados de contatos já cadastrados. |
| ❌ **Excluir** | Remove contatos da agenda e atualiza a visualização imediatamente. |

### 🛠️ Engenharia do Projeto
* **Visualização Dinâmica:** Utilização de `JTable` para renderizar os dados, atualizando a interface automaticamente após cada operação.
* **Persistência (Serialização):** Diferente de bancos de dados tradicionais, este projeto aplica conceitos de **Java I/O**. Utilizamos `ObjectOutputStream` para serializar os objetos e salvar em um arquivo binário (`agenda.dat`), garantindo que os dados não se percam ao fechar o programa.

---

## 📚 A Jornada de Aprendizado

Além do projeto final, este repositório contém diversos exercícios práticos focados em dominar a sintaxe e os paradigmas do Java.

### 1. Programação Orientada a Objetos (POO)
Modelagem de classes para resolver problemas do mundo real e cálculos matemáticos.

<details>
<summary><b>🔻 Clique para expandir os tópicos de POO</b></summary>

| Domínio | Exercício | Conceitos Aplicados |
| :--- | :--- | :--- |
| **Finanças** | `ContaPoupanca` | Encapsulamento, métodos `sacar()` e `depositar()`. |
| **Saúde** | `Paciente` | Lógica de cálculo de IMC e classificação de risco. |
| **RH** | `Funcionario` | Regras de negócio para cálculo de salário líquido e impostos. |
| **Geometria** | `Triangulo`, `Esfera` | Fórmula de Heron, herança e cálculos de volume/área. |

</details>

### 2. Estruturas de Dados & Coleções
Exercícios focados em performance e organização de dados em memória.

* **HashSet:** Implementação de coleções que garantem a **unicidade** (ex: geração de 50 números aleatórios sem repetição).
* **Arrays:** Manipulação clássica de vetores de booleanos e tipos primitivos.

### 3. Manipulação de Strings
Algoritmos de processamento de texto e validação.
* Validação de tamanho e formato.
* Extração (`substring`) e Substituição (`replace`).
* Verificação de prefixos e sufixos (`startsWith`).


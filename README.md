# 🚀 Code Craft Mentor Dev – Módulo 1

## 📘 Fundamentos do Java

### 🎯 Objetivo
Apresentar os **conceitos essenciais da linguagem Java** que todo desenvolvedor precisa saber antes de avançar para arquitetura, boas práticas ou frameworks.

---

## Conteúdo abordado:

- Estrutura básica de um programa Java
- Tipos de variáveis e objetos
- Condicionais (if/else)
- Laços de repetição (for/while)
- Classes com atributos e métodos
- Construtores e encapsulamento
- Organização do projeto
- Injeção de dependência (sem e com Spring)

---

## 📂 Estrutura do Projeto

```
src/
 └── main/
     └── java/
         └── com/
             └── code
                 └── craft
                     └── mentor/
                         ├── domain
                         │   ├── model               ← Entidades de domínio (ex: Cliente, Pedido)
                         │   └── usecase             ← Interfaces (ports) dos casos de uso
                         ├── application
                         │   └── service             ← Implementação dos casos de uso (application service)
                         ├── interfaceadapter       
                         │   ├── controller          ← APIs REST (camada de entrada)
                         │   └── dto                 ← Objetos de entrada/saída (Request/Response)
                         ├── infrastructure
                         │   ├── repository          ← Acesso a dados (ex: JPA, memória, etc)
                         │   └── config              ← Configurações Spring (beans, properties)
                         └── Application.java        ← Ponto de entrada da aplicação (Spring Boot)
```

---

## 🛠️ Como usar

1. Clone ou baixe este repositório.
2. Importe como projeto Maven/Gradle ou como projeto Java simples na sua IDE.
3. Explore os exemplos e implemente os exercícios sugeridos.

---

## ✅ Exercícios propostos

- Criar uma classe `Pessoa` com nome, idade e um método para exibir os dados.
- Criar um `PedidoService` que recebe um `PedidoRepository` via construtor.
- Criar exemplos de uso de condicionais e loops para simular lógicas simples (ex: calculadora, verificador de maioridade).

---

📚 **Bons estudos!**

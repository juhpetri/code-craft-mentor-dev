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

1. Faça um fork este repositório.
   1. Faça o fork do repositório
   2. Vá até o repositório original no GitHub.
   3. No canto superior direito, clique no botão "Fork".
   4. O GitHub criará uma cópia desse repositório na sua conta. 
2. Clone o repositório forkeado
   1. git clone https://github.com/seu-usuario/nome-do-repositorio.git
3. Abra o projeto no seu IDE favorito (ex: IntelliJ, Eclipse).
3. Implemente os exercícios sugeridos disponibilizado na call.

---

📚 **Bons estudos!**

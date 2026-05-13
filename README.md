# 🧬 Sistema Escolar - Praticando Herança (Java POO)

Este repositório apresenta a implementação de um sistema escolar para demonstrar o conceito de **Herança**, um dos pilares fundamentais da Programação Orientada a Objetos que permite a reutilização de código através de uma hierarquia de classes.

## 🎯 Conceito Aplicado

O objetivo deste exercício foi criar uma **Classe Progenitora** (`Pessoa`) e derivar dela classes filhas mais específicas, utilizando a palavra-chave `extends`.

### Estrutura da Hierarquia:

* **Pessoa (Superclasse)**: Define os atributos básicos compartilhados por todos (Nome, Idade, Sexo).
* **Aluno (Subclasse)**: Herda de Pessoa e adiciona atributos de Matrícula e Curso.
* **Professor (Subclasse)**: Herda de Pessoa e adiciona Especialidade e Salário.
* **Funcionario (Subclasse)**: Herda de Pessoa e adiciona Setor e Status de Trabalho.

## 🛠️ Vantagens Implementadas

* **Redução de Redundância**: Atributos e métodos comuns são escritos apenas uma vez na superclasse.
* **Facilidade de Manutenção**: Alterações em `Pessoa` refletem automaticamente em todas as subclasses.
* **Extensibilidade**: É simples adicionar novos tipos de pessoas ao sistema sem afetar o código existente.

## 📂 Arquivos do Projeto

* `Pessoa.java`: Superclasse com atributos e métodos comuns.
* `Aluno.java`, `Professor.java`, `Funcionario.java`: Subclasses especializadas.
* `Principal.java`: Classe de teste para instanciar os objetos e demonstrar o acesso aos métodos herdados.

---

*Projeto desenvolvido por Roberto Carlos como parte do portfólio de estudos em Java e Ciência da Computação.*

---





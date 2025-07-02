# 📦 Documentação de Testes - Projeto E-Commerce (Jira + Zephyr)

Este repositório contém toda a documentação solicitada para o desafio de projeto com foco em **Qualidade de Software**, utilizando **Jira** e **Zephyr Scale**.

O projeto foi desenvolvido com base em um sistema de **E-Commerce**, aplicando boas práticas de QA como planejamento de testes, criação de User Stories, mapeamento de bugs e execução dos testes. 

---

## 📁 Estrutura do Repositório

```
├── Bug/
│   └── [#ECV01-5] - Bug.pdf
│
├── Relatórios de Testes/
│   ├── Relatório de rastreabilidade.pdf
│   ├── Resultados de execução de teste (detalhamento).pdf
│   └── Resultados de executação de teste (resumo).pdf
│
├── User Stories/
│   ├── [#ECV01-1].pdf
│   └── [#ECV01-3].pdf
│
├── Mind Map/
    ├── Adicionar Produto ao Carrinho.jpeg
    └── Adicionar_Produto_ao_Carrinho.xmind
```

---

## 📑 Conteúdo

### ✅ Plano de Fluxo de Trabalho + Ciclo de Vida do Bug
- Documento explicando como funciona o fluxo de trabalho do time de desenvolvimento e o ciclo de vida de um **bug**, desde sua identificação até a resolução.
- 📄 Acesse aqui a Issue do tipo `bug`: [`[#ECV01-5] - Bug.pdf`](https://github.com/Lucas-RM/qa-docs-ecommerce-jira/blob/main/Bug/%5B%23ECV01-5%5D%20-%20Bug.pdf)

---

### ✅ User Stories
User Stories elaboradas para o projeto com foco em funcionalidades críticas do e-commerce.

- [`[#ECV01-1] - Adicionar Produto ao Carrinho`](https://github.com/Lucas-RM/qa-docs-ecommerce-jira/blob/main/User%20Stories/%5B%23ECV01-1%5D.pdf) 
- [`[#ECV01-3] - Validação de Estoque e Limite`](https://github.com/Lucas-RM/qa-docs-ecommerce-jira/blob/main/User%20Stories/%5B%23ECV01-3%5D.pdf)

---

### ✅ Mind Map (Mapa Mental)
Mapa mental representando a User Story **"Adicionar Produto ao Carrinho"**, com fluxos principais e alternativos:

![Visualização](https://github.com/Lucas-RM/qa-docs-ecommerce-jira/blob/main/Mind%20Map/Adicionar%20Produto%20ao%20Carrinho.jpeg)

📌 Arquivo original no formato `.xmind`: [Download](https://github.com/Lucas-RM/qa-docs-ecommerce-jira/blob/main/Mind%20Map/Adicionar_Produto_ao_Carrinho.xmind)

---

### ✅ Casos de Teste `XMl`
- **`Step-by-Step`**:
  - Fluxo de adicionar produto ao carrinho. Clique [aqui](https://github.com/Lucas-RM/qa-docs-ecommerce-jira/blob/main/Casos%20de%20Teste/ECV01-T2.xml) para acessar
  - Validação de limite de quantidade permitida Clique [aqui](https://github.com/Lucas-RM/qa-docs-ecommerce-jira/blob/main/Casos%20de%20Teste/ECV01-T3.xml) para acessar

- **`BDD (Gherkin)`**:
  - Cenário de sucesso na adição de produto Clique [aqui](https://github.com/Lucas-RM/qa-docs-ecommerce-jira/blob/main/Casos%20de%20Teste/ECV01-T4.xml) para acessar
  - Cenário de erro: produto sem estoque Clique [aqui](https://github.com/Lucas-RM/qa-docs-ecommerce-jira/blob/main/Casos%20de%20Teste/ECV01-T5.xml) para acessar

Clique [aqui](https://github.com/Lucas-RM/qa-docs-ecommerce-jira/blob/main/Casos%20de%20Teste/todos-os-casos-de-teste.xml) para acessar o `XML` de todos os casos de teste em conjunto.

📄 Relatórios em `pdf`:
- Clique para acessar: [`Relatório de rastreabilidade`](https://github.com/Lucas-RM/qa-docs-ecommerce-jira/blob/main/Relat%C3%B3rios%20dos%20Testes/Relat%C3%B3rio%20de%20rastreabilidade.pdf)
- Clique para acessar: [`Resultados de executação de teste (resumo)`](https://github.com/Lucas-RM/qa-docs-ecommerce-jira/blob/main/Relat%C3%B3rios%20dos%20Testes/Resultados%20de%20executa%C3%A7%C3%A3o%20de%20teste%20(resumo).pdf)
- Clique para acessar: [`Resultados de execução de teste (detalhamento)`](https://github.com/Lucas-RM/qa-docs-ecommerce-jira/blob/main/Relat%C3%B3rios%20dos%20Testes/Resultados%20de%20execu%C3%A7%C3%A3o%20de%20teste%20(detalhamento).pdf)

---

## 🚀 Tecnologias Utilizadas

- Jira Software
- Zephyr Scale (Essential)
- XMind (Mind Mapping)
- GitHub (Documentação)
- PDF e imagens (evidência de teste)

---

## 🧠 Autor

**Lucas Marcondes**  
Estudante de Ciência da Computação | QA & Desenvolvimento de Software  

---

> Projeto desenvolvido para fins de aprendizado e consolidação de práticas de qualidade de software no contexto de times ágeis.

🏋️ ZenFitStore - Banco de Dados NoSQL

Projeto de modelagem e implementação de um **banco de dados NoSQL utilizando MongoDB** para um e-commerce fictício de produtos fitness chamado **ZenFitStore**.

O objetivo do projeto é simular a estrutura de dados de uma loja virtual que comercializa **roupas de academia, suplementos, acessórios e equipamentos de treino**, permitindo o gerenciamento de clientes, produtos e pedidos.

---

📂 Estrutura do Banco de Dados

O banco de dados ZenFitStore é composto pelas seguintes coleções:

👤 Cliente
Armazena as informações dos clientes cadastrados na plataforma.

Campos principais:
- Nome
- CPF
- Email
- Telefone
- Endereço
- Senha

---

🛍️ Produto
Contém os produtos disponíveis na loja.

Campos principais:
- Nome
- Tipo
- Descrição
- Preço
- Estoque

Exemplos de produtos:
- Whey Protein
- Creatina
- Roupas fitness
- Equipamentos de treino
- Acessórios esportivos

---

📦 Pedidos
Armazena os pedidos realizados pelos clientes.

Campos principais:
- ID do cliente
- Lista de produtos
- Quantidade
- Valor total
- Status do pedido
- Data

Status possíveis:
- Processado
- Em processamento
- Recusado

---

🏷️ Categorias
Define as categorias dos produtos da loja.

Exemplos:
- Equipamentos
- Acessórios
- Roupas de academia
- Suplementos

---

🏢 Marca
Armazena as marcas dos produtos disponíveis.

Exemplos:
- Nike
- Adidas
- Growth
- Probiótica
- Black Skull
- Integralmédica

---

⚙️ Tecnologias Utilizadas

- **MongoDB**
- **NoSQL**
- **Mongo Shell**

---

🎯 Objetivo do Projeto

Este projeto foi desenvolvido para praticar conceitos importantes de **Banco de Dados NoSQL**, incluindo:

- Modelagem de dados em MongoDB
- Estruturação de documentos
- Relacionamento entre coleções
- Inserção de dados utilizando `insertMany()`
- Simulação de um sistema de e-commerce

---

🚀 Como Utilizar

1. Abra o **MongoDB Shell**
2. Execute o script do projeto
3. O banco de dados **ZenFitStore** será criado automaticamente com as coleções e dados de exemplo.

---

📚 Projeto Acadêmico

Projeto desenvolvido para fins **educacionais**, com o objetivo de praticar **modelagem de banco de dados e manipulação de dados em MongoDB**.

---

👨‍💻 Autores

**Allison Santos**

Estudante e entusiasta da área de **Data Analytics e Tecnologia**, interessado em análise de dados, bancos de dados e desenvolvimento de soluções baseadas em dados.

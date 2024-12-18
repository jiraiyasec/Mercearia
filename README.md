# Sistema de Mercearia (MVC - Orientado a Objetos)

Este é um sistema simples de mercearia, desenvolvido utilizando o padrão **MVC (Model-View-Controller)** e **orientação a objetos**. O objetivo do sistema é gerenciar informações de **clientes**, **produtos**, **estoque**, **fornecedores** e **vendas** em um ambiente de uma mercearia.

## Funcionalidades

- Cadastro de Clientes: Permite cadastrar novos clientes com suas informações pessoais.
- Cadastro de Produtos: Permite cadastrar e atualizar produtos disponíveis na mercearia.
- Gerenciamento de Estoque: Monitora o estoque de produtos, permitindo atualizações de quantidade.
- Controle de Vendas: Permite registrar as vendas realizadas na mercearia e calcular os totais.
- Cadastro de Fornecedores: Permite cadastrar fornecedores que fornecem os produtos da mercearia.

## Estrutura do Projeto

O projeto segue o padrão MVC, que separa a lógica do sistema em três componentes principais:

- Model: Representa os dados do sistema (clientes, produtos, estoque, etc.).
- View: Responsável pela interface com o usuário (telas de cadastro, visualização de dados).
- Controller: Faz a intermediação entre o Model e a View, controlando as interações do usuário.

### Estrutura de Pastas

```bash
├── Controller.py     # Controladores que gerenciam as interações
├── DAO.py            # Acesso aos dados (Banco de Dados)
├── Models.py         # Definição dos Modelos de dados (Produto, Cliente, etc.)
├── View.py           # Interface com o usuário (gerenciamento das entradas e saídas)
├── categoria.txt     # Arquivo de categorias
├── clientes.txt      # Dados dos clientes
├── estoque.txt       # Informações sobre o estoque
├── fornecedores.txt  # Fornecedores cadastrados
├── funcionarios.txt  # Informações sobre os funcionários
├── venda.txt         # Vendas realizadas
└── README.md         # Documentação do projeto

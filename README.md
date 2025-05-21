# TrabalhoESOF2
# Amigurumi Art

## Domínio do Projeto
O projeto consiste no desenvolvimento de uma plataforma digital de e-commerce especializada na venda de amigurumis, peças artesanais feitas em crochê ou tricô que representam personagens fofos, animais ou objetos estilizados. A plataforma tem como objetivo conectar artesãos a clientes interessados em produtos únicos e personalizados, oferecendo uma experiência de compra simples, segura e atrativa.

## Especificação dos Requisitos
Funcionais:
- Cadastro e login de usuários (clientes e administradores).
- Catálogo de produtos com imagens, descrições, preços e categorias.
- Sistema de busca e filtros por categoria, estilo, tamanho e disponibilidade.
- Carrinho de compras
- Painel administrativo para gerenciamento de estoque, pedidos e cadastro de novos produtos.

 Não Funcionais:
- Interface responsiva (acessível em dispositivos móveis e desktops).
- Alta usabilidade e navegação intuitiva.
- Banco de dados escalável.

## Modelos de Processos
1. Cadastro do Cliente
* O cliente acessa a página inicial.
* Clica em "Entrar / Registrar".
* Preenche formulário com nome, e-mail, senha e endereço.

2. Compra de Produto
* Cliente navega pelo catálogo.
* Seleciona o produto e adiciona ao carrinho.
* Visualiza o carrinho e prossegue para o checkout.
* Finaliza compra.

3. Gerenciamento de Produtos (Administrador)
* Administrador faz login no painel.
* Acessa a área de gerenciamento de produtos.
* Realiza cadastro, edição ou exclusão de itens no catálogo.
* Atualiza informações como preço, estoque e disponibilidade.

## Escopo do Projeto
+ Desenvolvimento do front-end responsivo com interface amigável.
+ Back-end com autenticação, gerenciamento de produtos e controle de pedidos.
+ Documentação técnica e instruções de uso.
+ Integração com redes sociais além da exibição de links.
+ Sistema de avaliação e comentários dos produtos.

## Tecnologias que serão Utilizadas 
- Front-end: HTML5, CSS3, JavaScript, React.js
- Back-end: Node.js
- Banco de Dados: MYSQL

# Metodo XP (Extreme Programming)
## Sprint 1 – Estrutura Inicial + Autenticação de Usuário (1 semana)
Objetivos:
Configuração do ambiente (projeto front e back).
Conexão Node.js ↔ MySQL.
Cadastro e login de clientes e administradores.
Validação de dados e autenticação (JWT ou sessions).

## Sprint 2 – Catálogo de Produtos + Busca e Filtros (1 semana)
Objetivos:
Estrutura e modelagem da tabela de produtos.
Exibição dos produtos com imagens e detalhes.
Implementação de busca por nome.
Filtros por categoria, estilo, tamanho e disponibilidade.

## Sprint 3 – Carrinho de Compras + Checkout
Objetivos:
Adição, edição e remoção de itens do carrinho.
Visualização e simulação de finalização da compra.
Armazenamento do carrinho (local/session).
Integração básica com backend para pedidos.

## Sprint 4 – Painel Administrativo + Avaliações + Finalização (1 semana)
Objetivos:
CRUD de produtos (admin).
Visualização e gerenciamento de pedidos.
Sistema de comentários e avaliações.
Testes, correções de bugs e documentação técnica.


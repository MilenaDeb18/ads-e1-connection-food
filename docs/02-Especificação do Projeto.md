# Especificações do Projeto

## Perfis de Usuário

|Perfil 01: Gerente de vendas    |
|------|-----------------------------------------|----|
|Descrição: | Responsável pela supervisão das operações diárias, gestão de equipes, controle de estoque e garantia de que os processos internos funcionem de forma eficiente.
|Necessidades: | Gestão de pedidos, Facilidade no acompanhamento de pagamentos e Análise de vendas    | 

|Perfil 02: Cliente   |
|------|-----------------------------------------|----|
|Descrição: | Pessoa que busca adquirir os produtos ofertados pelo estabelecimento.  
|Necessidades: | Rapidez no processo do pedido, Visualização do catálogo com os produtos disponíveis, Segurança nas transações, Opções de Pagamento Diversificadas e Acompanhamento da entrega do produto     | 

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `QUEM`| QUERO/DESEJO ... `O QUE` |PARA ... `PORQUE`                 |
|--------------------|------------------------------------|----------------------------------------|
|Gerente  | Agilizar o processo de vendas             | Aumentar as vendas            |
|Gerente       | Automatizar o processo de pedidos                 | Cortar custos |
|Gerente       | Receber o produto comprado e endereço de entrega de maneira clara                | Facilitar o repasse da informação ao responsável pela entrega |
|Cliente      | Fazer pedido online e recebê-los no endereço de preferência                  | Ter mais praticidade no dia a dia  |
|Cliente      | Opções de pagamento diversificadas               | Conseguir pagar da maneira que posso ou desejo e finalizar a compra de forma mais rápida  |
|Cliente      | Visualizar um cardápio organizado por categorias com produtos disponíveis                  | Facilitar a busca de um produto  |
|Cliente      | Clareza na descrição dos produtos                   | Auxiliar na escolha do produto   |
|Cliente      | Visualizar o horário de funcionamento                  | Saber que horas posso solicitar o recebimento de um pedido   |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deve exibir uma lista de produtos disponíveis para compra | ALTA | 
|RF-002| O sistema deve permitir a busca e filtragem de produtos por categoria, preço e nome    | MÉDIA |
|RF-003| O sistema deve calcular automaticamente o total do pedido com base nos produtos selecionados pelo cliente   | ALTA |
|RF-004| O sistema deve permitir que o cliente finalize o pedido, fornecendo detalhes como endereço de entrega e forma de pagamento  | ALTA | 
|RF-005| O sistema deve permitir que o usuário escolha entre diferentes formas de pagamento (cartão de crédito, débito e pix.).   | ALTA |
|RF-006| O sistema deve permitir a gestão de pedidos   | ALTA |
|RF-007| O sistema deve permitir a gestão do catálogo com os produtos disponíveis    | ALTA |
|RF-008| O sistema deve permitir que o usuário acompanhe o status do seu pedido (em preparo, a caminho, entregue).   | ALTA | 
|RF-009| O sistema deve permitir a atualização do status de entrega do pedido    | ALTA |
|RF-010| O sistema deve permitir possuir dados de contato para suporte caso o cliente precise resolver problemas com o pedido.    | MÉDIA |
|RF-011| O sistema deve exibir o horário de operação da confeitaria ao solicitar um pedido    | MÉDIA |
**Prioridade: Alta / Média / Baixa.  

### Requisitos não Funcionais

|ID     | Descrição  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deverá estar disponível 24hrs por dia  | MÉDIA | 
|RNF-002| A aplicação deverá ser responsiva, priorizando a performance em dispositivos móveis |  MÉDIA | 
|RNF-003| A aplicação deve ser capaz de ser executada em diferentes sistemas operacionais (Windows, Linux, macOS) e navegadores (Chrome, Firefox, Safari, Edge).   | MÉDIA | 
|RNF-004| Os textos da aplicação deverão estar no idioma português  |  ALTA | 
**Prioridade: Alta / Média / Baixa.



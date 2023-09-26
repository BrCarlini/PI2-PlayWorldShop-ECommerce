# PI2-PlayWorldShop-ECommerce
E-commerce (PDV) para Loja de Brinquedos - Projeto Integrador II

O projeto consiste em um sistema composto por dois principais cadastros: cliente e produto, além de uma funcionalidade de venda de produtos e um relatório de vendas. 
O cadastro de clientes permite a inserção, exclusão, alteração e consulta de clientes, utilizando nome ou CPF como critérios de busca. 
É necessário preencher dados como nome, CPF, endereço, telefone, e-mail, sexo, estado civil e data de nascimento, com validações de tipo, tamanho e obrigatoriedade.
Não é permitido cadastrar dois clientes com o mesmo CPF.

O cadastro de produtos também inclui operações de inserção, exclusão, alteração e consulta, com funcionalidade adicional de controle de estoque. 
Vendas diminuem o estoque e não é possível vender produtos sem estoque. Os campos necessários variam conforme o tema escolhido, com validações similares ao cadastro de clientes.

A venda de produtos é a atividade central do sistema, envolvendo o registro de saída de produtos do estoque para um cliente em um determinado momento. 
Durante o processo de venda, o usuário escolhe produtos, quantidades e o cliente, sendo exibido o valor final da venda para confirmação. 
São realizadas validações de obrigatoriedade, tipo, validade e tamanho.

O relatório de vendas permite visualizar resumos das vendas em um período de tempo (até um mês), incluindo valor total das vendas, data e cliente. 
Além disso, é possível ver os detalhes de cada venda, incluindo produtos e quantidad

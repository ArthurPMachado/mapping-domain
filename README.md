## Entidades
* Gerente de Estoque
* Gerente de Vendas
* Fornecedor

## Use Cases

* Criar produto
  * Id único
  * Adicionar informações extras, como tamanho e cor 
* Buscar produto
  * Usar queries para deixar a busca mais precisa 
* Definir quantidades mínimas de estoque
* Enviar alerta de falta de produto
* Enviar alerta caso o produto fique abaixo do valor mínimo de estoque
* Os alertas devem ser enviados por e-mail e por uma notificação no sistema de gerenciamento de estoque
* Buscar histórico de vendas
  * Retornar quantos produtos foram vendidos dado um período
  * Retornar o lucro gerado por produto
  * Retornar a perfomance de vendas dos produtos
* Buscar histórico de estoque
* Criar ordem de compra com base no valor minimo de estoque e se a performance de venda for alta
* Listar ordens de compra
* Listar prazo de entrega de novas remessas

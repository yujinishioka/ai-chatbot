## Conta IBM Cloud

problema do cartão de credito

___
* Catalog
    * Pesquisa: Watson Assistant
        * Criar: Lite

___
* Menu de Navegação
    * Lista de Recursos
        * Serviços Software
            * Watson Assistant

___
* Launch Watson Assistant:

___
* Perfil
    * Switch to Classic Experience

___
* Create Assistant
    * Nome: Vendas_ecommerce
    * Descrição: Assistente para site de e-commerce para auxiliar os clientes com as suas dúvidas mais frequentes

___
* Add Dialog Skill
    * Nome: Ajuda ao cliente
    * Descrição: Ajuda ao cliente com os problemas mais recorrentes do site
    * Língua: Português
    * Create Skill

___
* Skills
    * Ajuda ao Cliente
        * Dialog
            * Bem-vindo
                * Olá, Tudo bem?

___
* Intents
    * Create Intents
        * Nome: #reserva_produtos
        * Descrição: Ajudar os clientes a compreender a forma de funcionamento da reserva dos produtos
        * Create Intent
        * Adicionar exemplos:
            * Adicionei um produto ao meu carrinho de compras e gostaria de saber se ele irá ficar reservado?
            * Ao colocar um produto no carrinho de compras, ele fica reservado?
            * Ao adicionar o produto na sacola de compras, por quanto tempo ele ficara reservado?
            * Posso reservar produtos colocando no carrinho de compras?
            * Por quanto tempo meu produto ficará reservado no carrinho de compras?
            * Coloquei produtos no carrinho de compras, eles ficarão reservados?
            * Tenho uma reserva de produto no carrinho, ele ficara reservado?

___
* Skills
    * Ajuda ao Cliente
        * Dialog
            * Add Node
                * Recognize: #reserva_produtos
                * Resposta: Não, o produto só fica reservado quando a compra for finalizada

___
## Atividade:

1. criar intenção de entrega de produto
___
## Tips:

* Download das skills para backup
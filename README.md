# desafio2
 
HACKER - DESAFIO EM GRUPO 1
Hey Hackers!
Estamos aqui para apresentar a vocês o primeiro desafio deste programa. E nosso objetivo é que vocês pratiquem (agora em equipes) todas as competências que adquiriram ao longo deste mês.

Serão ao todo, 2 entregas, que poderão ser feitas de forma sequencial. Ao final de cada entrega, sua equipe será avaliada a partir de um checklist previamente definido (que você encontra logo a seguir).

Contexto: Continuamos no nosso contexto de sermos parte de uma equipe de desenvolvimento de websites e fomos contratados para a criação de um site de catálogo de produtos. Agora precisamos definir algumas regras de negócio para nosso Comércio Eletrônico e para isso precisamos definir algumas funcionalidades que podemos trabalhar usando Lógica de Programação e Javascript.

Neste caso, vamos tratar de uma loja (fictícia) de artigos eletrônicos e de informática, tudo bem?

E por conta disso, temos uma lista de produtos já declarada num arquivo Javascript que vocês terão acesso. Cada produto tem a seguinte estrutura:

  {

        "codProduto": 25754,

        "descricao": "ADAPTADOR BLUETOOH USB RECEPTOR DE AUDIO P2",

        "preco": 5.0,

        "qtdEstoque": 10,

        "disponivel": "sim",

        "emDestaque": "sim",

        "departamento": {

            "idDepto": 1,

            "nomeDepto": "Adaptadores"

        }

    }

 

Pois bem, com esta estrutura, agora organizando os produtos em uma grande lista, podemos (e é este o objetivo) criar várias funcionalidades para as regras de negócio do nosso ECommerce. Então vamos lá.

Itens a serem resolvidos

Quantidade total de itens em estoque (somatória das quantidades de todos os produtos)

Quantidade total de itens em destaque (somatória das quantidades dos itens marcados como "emDestaque : sim")

Quantidade total de itens disponíveis (similar ao anterior)

Quantidade de itens disponíveis e em destaque

Valor total do inventário da empresa (somatória dos valores individuais multiplicado pela quantidade em estoque - considere apenas os produtos “EM ESTOQUE”)

Produto mais caro da loja (bem como seu departamento - considere apenas o preço dele)

Produto mais barato da loja (bem como seu departamento - considere apenas o preço dele)

Produto de estoque mais valioso (considere o preço multiplicado pela quantidade e também apenas EM ESTOQUE)

Produto em estoque menos valioso (considere o preço multiplicado pela quantidade e também apenas EM ESTOQUE)

Valor do ticket médio dos produtos da empresa (basicamente o valor total do inventário dividido pelo número de itens - considere TODOS os produtos, porém considere apenas 1 exemplar por produto)

Somatória de itens por departamento (você deverá retornar um objeto contendo o nome do departamento e o total de itens nele - Novamente considere os produtos “EM ESTOQUE” - e é apenas a somatória da quantidade de itens)

Valor total do inventário por departamento (similar ao item anterior - considere TODOS os produtos)

Ticket médio por departamento (similar ao item anterior, porém retornando uma lista de objetos que contenha o nome do departamento e o seu ticket médio). Este é um exercícios difícil, porém é 

Departamento mais valioso (qual o departamento que tem a maior somatória dos valores dos itens - Considere todos os departamentos)

Departamento menos valioso (similar ao anterior)
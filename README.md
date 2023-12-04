<h1>API REST e RESTful</h1> 

## A API REST 
(Representational State Transfer) é um conjunto de regras que guiam a comunicação entre serviços web usando HTTP. Ela possibilita a troca eficaz de informações entre sistemas distintos, baseando-se na identificação de recursos por URIs. Para operar nesse modelo, são empregados métodos como GET, POST, PUT e DELETE para manipular esses recursos. Uma API REST é flexível, escalável e adere ao princípio de statelessness, ou seja, não armazena informações sobre o cliente entre interações.

## Princípios da abordagem RESTful:

+ Comunicação via HTTP: Utiliza o protocolo HTTP para interações entre serviços web de diferentes sistemas.
+ Recursos e URIs: Baseia-se na identificação única de recursos por URIs para facilitar o acesso e a manipulação dos dados.
+ Métodos HTTP: GET (obter), POST (criar), PUT (atualizar), DELETE (excluir) são usados para operações nos recursos.
+ Escalabilidade e Flexibilidade: Projetada para ser adaptável e permitir desenvolvimento ágil e escalável de serviços.
+ Statelessness: Não mantém informações sobre o estado do cliente, simplificando as interações.
+ Padrão de Design: Adere a um conjunto de regras para manter a uniformidade na comunicação entre sistemas.
+ RESTful refere-se à capacidade de uma API ou serviço web seguir os princípios do REST. Uma API RESTful adere estritamente aos conceitos definidos pelo REST, implementando métodos HTTP e outras práticas para criar uma arquitetura conforme esses princípios.

## Diferenças entre REST e RESTFul:

REST: É um estilo arquitetural que define regras para criação de serviços web escaláveis, flexíveis e interoperáveis.
RESTful: É a implementação concreta desses princípios em uma API ou serviço web específico.
HTTP verbs:
+ GET: Recupera dados de um recurso.
+ POST: Envia dados para criar ou atualizar um recurso.
+ PUT: Substitui completamente um recurso existente.
+ DELETE: Remove um recurso.
+ PATCH: Aplica modificações parciais em um recurso.
+ HEAD: Obtém apenas os cabeçalhos da resposta, sem o corpo da mensagem.
+ OPTIONS: Descobre quais métodos são permitidos em um recurso.

## HTTP Status Code:

Os códigos de status HTTP indicam o resultado da requisição:

+ 1xx: Informativo - Requisição recebida e processo em andamento.
+ 2xx: Sucesso - Requisição recebida, entendida e aceita.
+ 3xx: Redirecionamento - Mais ações necessárias para completar a requisição.
+ 4xx: Erro do Cliente - Erro na requisição pelo cliente.
+ 5xx: Erro do Servidor - Erro no processamento da requisição pelo servidor.



### Filipe Alexandre Bulhões Gomes Pontes - 01435394



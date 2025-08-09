# Oráculo-Financeiro-N8N

Pré-Requisitos:
 - Credenciais do Brapi e Gmail

Como utilizar:
  - Cadastrar as credenciais necessárias
  - Colocar os ativos que você quer monitorar no primeiro nó Code
  - Colocar o seu email no nó Gmail

O Workflow faz o seguinte:
 - Ele pega de um array o nome das ações que você quer ter o relatório
 - Para cada um dos itens do array ele usa o nó "HTTP Request" e vai no site brapi para coletar as informações
 - Depois disso, vem o nó "Edit Fields" para separar apenas os dados necessários
 - Mais um nó code para tratar as informações e transformar num texto
 - Finaliza com o nó Gmail que envia o relatório diário

Aprendi nesse projeto como usar de forma melhor o nó Code e também HTTP Request.
Além disso, também aprendi a formatar o texto que é enviado utilizando as tags HTML.

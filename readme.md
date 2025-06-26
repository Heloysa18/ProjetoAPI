<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Projeto API - Consulta de Produtos</title>
</head>
<body>
  <h1>Projeto API - Consulta de Produtos</h1>
  <p>
    Esta API RESTful foi desenvolvida para permitir o gerenciamento completo de produtos em um catálogo. 
    Ela permite a criação, leitura, atualização e exclusão (CRUD) de produtos. Ideal para aplicações de e-commerce, estoque ou catálogos de serviços.
  </p>

  <h2>Funcionalidades</h2>
  <ul>
    <li>Listar todos os produtos</li>
    <li>Consultar produto por ID</li>
    <li>Adicionar novo produto</li>
    <li>Atualizar informações de um produto existente</li>
    <li>Excluir um produto do catálogo</li>
  </ul>

  <h2>Endpoints da API</h2>
  <ul>
    <li><code>GET /produtos</code> - Retorna todos os produtos</li>
    <li><code>GET /produtos/{id}</code> - Retorna um produto específico</li>
    <li><code>POST /produtos</code> - Adiciona um novo produto</li>
    <li><code>PUT /produtos/{id}</code> - Atualiza um produto existente</li>
    <li><code>DELETE /produtos/{id}</code> - Remove um produto</li>
  </ul>

  <h2>Exemplo de JSON</h2>
  <h3>Requisição POST</h3>
  <pre>
POST /produtos
Content-Type: application/json

{
  "nome": "Cadeira Gamer",
  "preco": 799.90,
  "quantidade": 5
}
  </pre>

  <h3>Resposta JSON</h3>
  <pre>
{
  "id": 1,
  "nome": "Cadeira Gamer",
  "preco": 799.90,
  "quantidade": 5,
  "dataCadastro": "2025-06-26T12:34:56Z"
}
  </pre>

  <h2>Tecnologias Utilizadas</h2>
  <ul>
    <li>Linguagem: <strong>Python</strong> ou <strong>Node.js</strong> (substitua pela real)</li>
    <li>Framework: <strong>FastAPI</strong>, <strong>Express.js</strong> ou outro</li>
    <li>Banco de Dados: <strong>SQLite</strong>, <strong>PostgreSQL</strong> ou <strong>MongoDB</strong></li>
    <li>Testes com <strong>Postman</strong> ou <strong>Insomnia</strong></li>
  </ul>

  <h2>Como Testar a API</h2>
  <ol>
    <li>Clone este repositório: <code>git clone https://github.com/seu-usuario/ProjetoAPI</code></li>
    <li>Instale as dependências do projeto</li>
    <li>Execute a aplicação localmente (ex: <code>npm start</code> ou <code>uvicorn main:app</code>)</li>
    <li>Use o Postman ou cURL para testar os endpoints</li>
  </ol>

  <h2>Licença</h2>
  <p>Este projeto está licenciado sob a <strong>MIT License</strong> – veja o arquivo LICENSE para mais detalhes.</p>

  <h2>Autor</h2>
  <p>
    Desenvolvido por [Seu Nome].<br>
    Contato: [seu-email@exemplo.com] | GitHub: <a href="https://github.com/seu-usuario" target="_blank">seu-usuario</a>
  </p>
</body>
</html>

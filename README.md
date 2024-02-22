<h1>RESTful API de Usuários</h1>

<h3>API desenvolvida em Node.js</h3>

<h3>Instalação</h3>
<p>npm install</p>

<h3>Excutando servidor</h3>
<p>npm start</p>

<h3>Rotas</h3>

<h5>Obter todos os usuários:</h5>
<p>GET /users<p>    
<h5>Exemplo de resultado:</h5>

<p>{</p>
<p>    "users":[]</p>
<p>}</p>
    
<h5>Cadastrar um novo usuário:</h5>
<p>POST /users</p>
<h5>Exemplo de resultado:</h5>

<p>{</p>
<p>    "_id":"hjkhfui324",</p>
<p>    "name":"Canon Oliveira"</p>
<p>}</p>

<h5>Obter dados de um usuário:</h5>
<p>GET /users/:id</p>
<h5>Exemplo de resultado:</h5>

<p>{</p>
<p>    "_id":"hjkhfui324",</p>
<p>    "name":"João Rangel"</p>
<p>}</p>

<h5>Editar um usuário:</h5>
<p>PUT /users/:id</p>
<h5>Exemplo de resultado:</h5>

<p>{</p>
<p>    "_id":"hjkhfui324"</p>
<p>}</p>

<h5>Excluir um usuário:</h5>
<p>DELETE /users/:id</p>
<h5>Exemplo de resultado:</h5>

<p>{</p>
<p>    "_id":"hjkhfui324"</p>
<p>}</p>

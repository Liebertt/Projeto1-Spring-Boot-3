# Aplicação VollMed
<p>Esta aplicação serve para cadastrar médicos e pacientes, nela temos basicamente um CRUD</p>
<br>
<br>
<b>Instrutor do curso: </b>
<p>Rodrigo da Silva Ferreira Caneppele</p>
<br>
<b>Stacks utilizadas </b>
<br>
<br>
<b>Front-end:</b> <br>
O front-end será simulado usando o Insomnia
<br>
<br>
<b>Back-end:</b> <br>
Para o back-end usaremos o Spring Boot 3
<br>
<br>
<b>Assuntos que serão abordados no curso: </b>

<ul>
  <li>Crie do zero uma API Rest em Java com Spring Boot</li>
  <li>Desenvolva CRUDs utilizando o banco de dados MySQL</li>
  <li>Utilize o Flyway como ferramenta de Migrations da API</li>
  <li>Realize validações utilizando o Bean Validation</li>
  <li>Realize paginação dos dados da API</li>
</ul>

<br>
<b>Aulas: </b>
<ul>
  <li><b><i>Criação do Projeto</i></b></li>
  <ul>
  <li>Criar um projeto Spring Boot utilizando o site do Spring Initializr;</li>
  <li>Importar o projeto no IntelliJ e executar uma aplicação Spring Boot pela classe contendo o método main;</li>
  <li>Criar uma classe Controller e mapear uma URL nela utilizando as anotações <code>@RestController</code> e <code>@RequestMapping</code>;</li>
  <li>Realizar uma requisição de teste no browser acessando a URL mapeada no Controller.</li>
  </ul>
  <br>
  <li><b><i>Requisições POST</i></b></li>
  <ul>
  <li>Mapear requisições POST em uma classe Controller;</li>
  <li>Enviar requisições POST para a API utilizando o Insomnia;</li>
  <li>Enviar dados para API no formato JSON;</li>
  <li>Utilizar a anotação @RequestBody para receber os dados do corpo da requisição em um parâmetro no Controller;</li>
  <li>Utilizar o padrão <b><i>DTO (Data Transfer Object)</i></b>, via Java Records, para representar os dados recebidos em uma requisição POST.</li>
  </ul>
  <br>
  <li><b><i>Spring Data JPA</i></b></li>
  <ul>
  <li>Adicionar novas dependências no projeto;</li>
  <li>Mapear uma entidade JPA e criar uma interface Repository para ela;</li>
  <li>Utilizar o Flyway como ferramenta de Migrations do projeto;</li>
  <li>Realizar validações com Bean Validation utilizando algumas de suas anotações, como a <code>@NotBlank</code>.</li>
  </ul>
  <br>
  <li><b><i>Requisições GET</i></b></li>
  <ul>
  <li>Utilizar a anotação <code>@GetMapping</code> para mapear métodos em Controllers que produzem dados;</li>
  <li>Utilizar a interface Pageable do Spring para realizar consultas com paginação;</li>
  <li>Controlar a paginação e a ordenação dos dados devolvidos pela API com os parâmetros <code>page</code>, <code>size</code> e <code>sort</code>;</li>
  <li>Configurar o projeto para que os comandos SQL sejam exibidos no console.</li>
  </ul>
  <br>
  <li><b><i>Requisições PUT e DELETE</i></b></li>
  <ul>
  <li>Mapear requisições PUT com a anotação <code>@PutMapping</code>;</li>
  <li>Escrever um código para atualizar informações de um registro no banco de dados;</li>
  <li>Mapear requisições DELETE com a anotação <code>@DeleteMapping</code>;</li>
  <li>Mapear parâmetros dinâmicos em URL com a anotação <code>@PathVariable</code>code>;</li>
  <li>Implementar o conceito de exclusão lógica com o uso de um atributo booleano.</li>
  </ul>
</ul>


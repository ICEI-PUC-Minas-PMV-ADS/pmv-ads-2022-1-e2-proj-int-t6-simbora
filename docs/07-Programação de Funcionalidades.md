# Programação de Funcionalidades

A implementação do sistema foi descrita considerando os requisitos funcionais e/ou não funcionais. Para isso, é mostrada abaixo uma tabela com os requisitos atendidos e os seus respectivos artefatos criados (código fonte), além das estruturas de dados utilizadas e as instruções para acesso e verificação da implementação.

Para cada requisito funcional, pode ser entregue um artefato desse tipo.

| ID  | Requisito  | Artefato |
|----|-----------------------------------------|----|
| RF-001 | A aplicação deve permitir que o usuário se cadastre como Promoter ou como Publico. | login.cshtml | 
| RF-002 A aplicação deve permitir que somente o usuário logado, como promoter ou cliente, possa ter acesso a página de Eventos e Comentários. | Index.cshtml na pasta Eventos e também na pasta Comentários|
| RF-003 | A aplicação deve permitir que somente o promoter logado possa cadastrar um novo Evento, e editar um Evento já cadastrado. | Create.cshtml na Pasta Eventos |
| RF-004 | A aplicação deve disponibilizar um campo para comentários e avaliações por nota (0-10) de cada evento para os clientes. | Create.cshtml na pasta Comentarios|

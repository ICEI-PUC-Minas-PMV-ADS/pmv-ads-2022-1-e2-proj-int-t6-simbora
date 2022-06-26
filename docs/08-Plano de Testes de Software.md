# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Os testes funcionais a serem realizados no aplicativo são descritos a seguir. 



|Caso de Teste       |CT-01 – Cadastro de Usuário                                                                          |
|--------------------|----------------------------------------------------------------------|
|**Requisitos Associados** | RF-001 - A aplicação deve permitir o cadastro de usuário do tipo Promoter ou Cliente, 
|**Objetivo do Teste** | Permitir que o usuário realize o seu cadastro, inserindo os seus dados como: nome, cpf, telefone, e-mail, escolha seu perfil de usuário (cliente ou promoter) e crie uma senha  |
|**Passos** | 1) Acessar o Navegador  2) Informar o endereço do Site http://simbora-001-site1.ftempurl.com/  3) Abrir pagina Inicial 4) Clicar em Usuário 5) Preencher os campos solicitados com os dados: nome, cpf, e-mail, telefone, perfil de usuário e senha 6) após preencher todas as estas informações clicat em Salvar. |
|**Critérios de Êxito** | O usuário será direcionado para a página Index onde se encontra a Lista de Usuários Cadastrados e mostrará o seu nome e dados nesta lista como usuário cadastrado. |

| Caso de Teste               | CT-02 –  Realizar o login e Visualizar eventos cadastrados                              |
|-----------------------------|-----------------------------------------------------------------------------------|
|**Requisitos associados**      | RF-002]  - A aplicação deve permitir que somente o usuário cadastrado previamente possa realizar o seu login e logout.|
| **Objetivo do teste**           | Permitir que todos os usuários realizem o seu login e logout no sistema. | 
| **Passos**                      | 	1) Acessar o Navegador 2) Informar o endereço do Site web http://simbora-001-site1.ftempurl.com/ 3) Entrar na página Inicial 4) Clicar e Login  5) Preencher os campos CPF e senha e clicar em Entrar 4) Em seguida irá aparecer no canto superior direito do site uma mensagem tipo: "Olá, usuário" mostrando que o usuário está logado 5) Para visulaizar os Eventos cadastrados o usário logado clica em Eventos 6) Usuaário será direcionado para a página Index com a lista de Eventos cadastrados 7) Para realizar o Logout o usuário clica em Sair. |
| **Critérios de êxito**          | O objetivo se apresentou com êxito e o Usuário visualizará no canto superior direito da página Web seu nome na seguinte mensagem: "Olá, nome do usuário". E o usário apenas logado conseguiu ter acesso a lista de Eventos cadastrados. |
 
| Caso de Teste               | CT-03 –  Cadastro de Evento                              |
|-----------------------------|-----------------------------------------------------------------------------------|
|**Requisitos associados**      | RF-003]  - A aplicação deve permitir que somente o usuário do tipo Promoter possa cadastrar um evento inserindo informações como: nome do evento, local, data, horário, e informações adicionais; e que possa também editar, deletar e ver os detalhes deste evento.|
| **Objetivo do teste**           | Permitir que todos os usuários apenas do tipo Promoter cadastrem, editem, delete e tenham acesso aos detahes de um Evento. | 
| **Passos**                      | 	1) Acessar o Navegador 2) Informar o endereço do Site web  http://simbora-001-site1.ftempurl.com/ 3) Entrar na página Inicial 4) Selecionar o link Eventos  5) Acessar o link New Create, em seguida preencher os campos pedidos e clicar no botão Salvar 6) Promoter será direcionado para a Lista de Eventos Cadastrados 7) Nesta Lista o Promoter pode clicar em Edit, Details e Delete para editar, deletar e ver os detalhes do evento cadastrado, respectivamente. |
| **Critérios de êxito**          | O objetivo se apresentou com êxito.
  
| Caso de Teste               | CT-04 –  Cadastro de Comentário                              |
|-----------------------------|-----------------------------------------------------------------------------------|
|**Requisitos associados**      | RF-004]  -A aplicação deve permitir que somente o usuário logado, como promoter ou cliente, possa cadastrar um Comentário sobre determinado evento, inserindo informações como: nome do evento, nota (0-10), e comentário; e possa visualizar um comentário cadastrado.|
| **Objetivo do teste**           | Permitir que todos os usuários (cliente ou promoter) escrevam comentários sobre os eventos. | 
| **Passos**                      | 	1) Acessar o Navegador 2) Informar o endereço do Site web http://simbora-001-site1.ftempurl.com/ 3) Entrar na página Inicial 4) Selecionar o link Comentários  5) Acessar o link New Create, em seguida preencher os campos pedidos e clicar no botão Salvar. |
| **Critérios de êxito**          | O objetivo se apresentou com êxito. O comentário cadastrado pode ser visualizado na lista Index da seção Comentários juntamente com todos os outros comentários cadastrados.

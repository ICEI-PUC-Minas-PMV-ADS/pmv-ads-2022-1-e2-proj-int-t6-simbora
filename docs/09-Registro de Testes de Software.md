# Registro de Testes de Software

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>, <a href="8-Plano de Testes de Software.md"> Plano de Testes de Software</a>

Relatório com as evidências dos testes de software realizados no sistema pela equipe, baseado em um plano de testes pré-definido.

## CT-01 - Cadastro do usuário

https://user-images.githubusercontent.com/91221827/175820319-0b422fc8-f94e-45c4-8c69-c63964ee676f.mp4

## CT-02 - Login do usuário

https://user-images.githubusercontent.com/91221827/175820361-aafc1ae8-1eb2-43e5-87a3-8a8b18ca445f.mp4

## CT-03 - Cadastro de Evento

https://user-images.githubusercontent.com/91221827/175820394-bf96b25d-e353-4221-b63a-ec3754d5a7ab.mp4

## CT-04 - Cadastro de Comentário sobre um evento

https://user-images.githubusercontent.com/91221827/175820431-832605b6-178c-4621-b1ad-bda8e068ab95.mp4

## Avaliação

A solução gerada apresenta pontos fortes e fracos. Por exemplo, os pontos fortes do site Simbora são: a possibilidade de apenas usuários do tipo Promoter realizarem o cadastro de eventos quando logados no sistema, eles também tem acesso ao cadastro de comentários sobre algum evento que tenha assistido e seu comentário fica disponível para todos os usários logados. Desse modo, o promoter tem acesso a estes dois recursos do site que são cadastro de eventos e comentar sobre algum evento. Outro ponto forte da solução é que o sistema não possibilita que o usuário cliente cadastre um evento, istó ajuda a restringir esta ação apenas para usuários do tipo Promoter,mas o cliente pode cadastrar um comentário sobre determinado evento. Vale frisar que no cadastro de comentários os usuário tem a possibilidade de dar uma nota para o evento e também os mesmos dispõem de um campo para edição livre de texto com comentários sobre o evento. Outro ponto forte é que os usuários não tem acesso a senha e CPF de outros usuários, representando mais sigilo para as informações. 
Entretanto, a solução apresenta pontos fracos que precisam ser melhorados futuramente, como por exemplo: o usuário (promoter ou clinete) infelizmente pode deletar, e editar o cadastro de outro usuário, assim como tem esta liberdade para também deletar e editar comentários e eventos já cadastrados por qualquer usuário. Essas falhas serão futuramente corrigidas pela equipe através da alteração dos códigos de Back-end.
Através desse teste de Software foi possivel tornar o login do usuário mais prático com apenas a inserção de CPF e senha, e caso estes dados estejam incorretos, o usário é informado com um mensagem avisando que CPF e/ou senha foram digitados incorretamente; além disso, este teste também possibilitou que o usuário cliente não tenha acesso ao cadastro de evento e seja avisado sobre tal proibição através de uma mensagem de texto que se refere a não autorização de cadastro de evento.

> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)

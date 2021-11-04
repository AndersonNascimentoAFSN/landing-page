# landing-page

# Desafio 1 O cliente Só Sabão precisa captar os e-mails de seus clientes para contatos e estratégias de mailing e para isso, precisamos de uma landing page.

# O que vocês farão? 
Uma landing page desenvolvida em HTML e JavaScript Vanilla descrevendo a empresa e anunciando uma promoção que para participar basta cadastrar o nome e e-mail nos respectivos campos.

Os e-mails serão armazenados em um banco banco de dados. Utilizaremos uma api em express e o sistema para gerência-lo será o mongoDB.

# Qual o processo?

Criaremos dois repositórios no gitHub um para o front-end e outro para o back-end. Após isso, elaboraremos uma lista de requisitos tanto para o front-end quanto para o back-end.

# Como farão?
##Front-End:

Primeiramente desenvolveremos a landing page em HTML com as informações pertinentes a empresa, e o formulário para captação dos dados do cliente (nome e e-mail). Após isso, faremos a estilização da página utilizando css. E por fim toda a lógica com JavaScript para capturar os dados do cliente.

##Back-End:

Faremos um back-end utilizando express e mongoDB cujo objetivo será armazenar os nome e e-mails dos clientes.

# Como os dados serão armazenados?
Os dados serão armazenados em uma API utilizando o framework express, e como sistema de gerenciamento de banco de dados o mongoDB.

# Detalhe o raciocínio, coloque todas as informações que achar pertinente.

A landing page deverá ser bem chamativa para fazer com que o cliente tenha vontade de preencher as informações. 

Será necessário captar o nome e e-mail do cliente na página através dos respectivos inputs. Os inputs deverão ter eventos de onChange para capturar essas informações e salvá-la. Esses inputs deverão está em um formulário, bem como deve haver um botão que ao ser pressionado enviará os dados dos inputs para a API, através do método POST.

Chegando no back-end deve haver um endpoint para pegar esses dados enviados pelo front-end e armazená-los no banco de dados do mongoDB.


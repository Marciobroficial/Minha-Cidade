# Minha-Cidade
## Projeto de Software.

Sobre o sistema
Dado inicio no projeto em Ago 07, 2021

De acordo com a aula e escolha do professora nossa equipe será responsável em desenvolver um sistema que leve as reclamações da população até aos administradores de um município, podendo ser por envio de imagens para que seja averiguada a reclamação, ou via texto, recomendação, sujestão como se fosse uma rede social municipal onde os munícipes consigam realizar seus posts, interagir neles e obter respostas direta da administração. 

### App Minha cidade

Sistema acadêmico da aula Eletiva de desenvolvimento Web da Fatec Presidente Prudente.

Professor: Ana Carolina.

Alunos:

Márcio Alessandro dos Santos // https://github.com/Marciobroficial

Emerson Abreu Neves // https://github.com/MersoAbreu

Thiago Araujo Ribeiro

Guilherme

========================================================================================
### Projeto Minha Cidade


O projeto minha cidade é uma plataforma de estilo rede social, que permitira a iteração entre os administradores de uma cidade e seus municipes. 

O projeto tem como viabilidade melhorar a conexão entre a população, podendo atribuir melhoras a serem feitas no municipio, elogios por algum trabalho relaizado, ideias, e manter a população ativa e participativa nos processos e no trabalho da administração.

 

Funcionalidades:

O sistema terá varias funcionalidades, será de modelo WEB e Mobile, ele terá as seguintes funcionalidades.

 

Tela de login
A tela de login tera dois campos de inputs, sendo:

1º Input campo usuario ou e-mail;

2º Input campo senha;

Esses campos de input serão obrigatórios para o usuário ter acesso ao sistema, no momento de seu acesso ao sistema será validado os dados inseridos neste campo que fará o redirecionamento para a pagina inicial do sistema, para que ele seja redirecionado a tela terá um botão ainda na pagina de login:

3º Botão entrar:

Este botão irá disparar a validação para acesso a tela inicial, se o usuário estiver cadastrado dentro do banco de dados com seu nome de usuário ou e-mail e senha corretas, ele irá seguir ao acesso senão sua entrada será negada.

 

Tela de cadastro
O sistema terá na tela de login um link para se caso o usuário não tenha cadastro no sistema poder se cadastrar, este link redirecionará o usuário para a tela de cadastro onde terá os seguintes campos para preenchmento e validação de usuário:

1º Input e-mail:

Neste input será informado um e-mail do usuário para acesso ao sistema o e-mail será validado para verificar se existe ou não, só terá aceso ao sistema usuário com o e-mail valido.

2º Input nome ou nome de usuário:

O input nome será para que o usuário insira seu nome completo ou seu nome de usuário que será apresentado.

3º Input data de nascimento:

O input data de nascimento será realizado com dia, mês e ano de nascimento do usuário.

4ºInput Genero:

O input genero será para que o usuário informe seu genero.

5º Input Senha:

Neste input o usuário deverá inserir uma senha no qual usará posteriomente para acesso ao sistema.

 

##  Tela Esqueci minha senha
 
O sistema tambem contará ainda na tela de login um outro link que terá o nome de “Esqueci minha senha”, este link irá redirecionar o usuário para outra página que terá as seguintes funcionalidades.

Nesta tela apresentará o campo para que vc insirá seu e-mail, e será enviado um e-mail com um link para acesso ao mudar senha.

Neste link abrirá uma pagina para que vc possa alterar a senha, solicitando que vc informe seu e-mail, a nova senha e a repetição desta nova senha.

Após realizar este procedimento o banco de dados será atualizado com esta nova senha e você poderá acessar ao sistema normalmente com sua nova senha. 

 

##  Tela inicial / Home

Na tela home teremos um menu superior:

Menu superior:

No menu superio haverá um campo de pesquisa, para pesquisar pessoas ou feed de noticias gerados.

Haverá tambem as informações do usuário que podem ser editadas de acordo com o que o usuário deseja.

Um botão de Logout, para que se acaso o usuário deseje encerrar sua sessão. 

 

Abaixo do menu haverá um campo para inserir um novo feed:

##  Publicar:

Este campo publicar irá apresentar um modal para que seja inserido uma nova publicação, esta publicação seguirar para o feed de noticias. O usuário tambem poderá realizar o envio de imagens para a publicação.

Irá ter o botão publicar onde haverá uma validação que esta publicação deverá conter um conteúdo para que não haja publicações vazias no feed de noticias.

## Feed de publicações:

O feed de publicações apresentará as publicações em ordem de horário de publicação a publicação mais recente sempre será apresentada primeiro, e dentro de cada prublicação poderá realizar as seguintes ações:

 

## Comentar:

Outros usuáros poderam comentar dentro da publicação, deixando suas duvidas, palpites, elogios.

 

Sempre quando os administradores perante a publicações realizarem um procedimento terá presente para o administrado e somente para ele um botão check informando que aquela solicitação, ou reclamação, palpite, ideia foi atendido, e a cor da publicação será alterada contendo informações do momento que foi atendido, 

dentro destes feeds a administração poderá informar aos municipes sobre informações da area da súde, agricultura, e demais departamentos existentes dentro do regime para que os municipes fiquem atentos ao que ocorre no municipio, como datas de vacinas, visitas de dengue, IPTU, e etc..


##   Resolução de problema recorrente

Quando o problema do usuario não conseguir comentar uma publicação:

#### Steps

1 - Reiniciar servidor da aplicação

2 - Verificar se os dados estão corretos

3 - verificar logs do usuario


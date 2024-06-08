 # :large_blue_circle: ATIVIDADE-UX-DEVOPS :large_blue_circle:

Atividade 2º Bimestre 3º Semestre S.I. UX/DEVOPS

   # 🔵 Apresentação

 Olá, esse repositório é um trabalho de faculdade, nele esta proposto criar uma interface de login, com recuperação de senha, tela de cadastro e uma tela principal. Desenvolvemos o projeto de baixa fidelidade no MIRO, clique [aqui](https://miro.com/welcomeonboard/TTQ5cmFrS0hOV2RkVk5IZUhVQlVxemxvR0ljV0wwQmVZTUV5MTdZdnk2VWZhaHFJbkI0dmtSNHg5d2NqcUM0VHwzNDU4NzY0NTg4ODY5OTkyODgzfDI=?share_link_id=768665701708) para conseguir ver o projeto no miro.
   No Miro desenvolvemos o projeto de como tem que ser feita a disposição das telas, fizemos o projeto pensando na responsividade e com opções para acessibilidade, esse trabalho esta sendo desenvolvido na matéria de UX da faculdade, então **não foi pensado necessariamente na funcionalidade do código**, e sim na disposição dos elementos em tela, cores, botões, possiveis funcionalidades a serem implementadas e a progreção do usuário dentro do sistema.

   ## 🔷 Regras de negócio.

   ![Imagem do projeto no MIRO](https://raw.githubusercontent.com/danielsz3/ATIVIDADE-UX-DEVOPS/46c5ae0f28803490ff69cbddc5481cddf9dfa352/img/Imagens%20interface%20de%20baixa%20fidelidade.png)

   De forma ilustrativa temos aqui a disposição das telas para um celular, as regras de negócio aplicadas para essas telas se replicam nas telas de **Desktop** e **Tablet**, dito isso vamos ao que importa.

   ### :small_blue_diamond: Tela de Login.
   Na tela de login é possivel ver que fora os campos, que são requisitos para o login, existe as opções:
   
   👉 **"Esqueceu sua senha?"**, leva o usuário para uma tela específica de redefinição da senha.
   
   👉 **"Primeiro acesso"**, leva o usuário para a tela de cadastro.
   
   Essas opções são pensadas tanto para um usuário que ja tem conta quanto para um novo usuário. O campo da senha existe a opção de exibir a senha do usuário, pensando em uma forma de feedback pro usuário.

   ### :small_blue_diamond: Tela de Cadastro.

   
   Na tela de cadastro os dados requeridos ao usuário são:

   
   👉 **NOME COMPLETO**, um campo para inserção de caractere, não deve permitir a entrada de caracteres especiais **(@!#$%*)**, ou numero **(1,2,3,4,5,6,7,8,9,0)**
   
   👉 **EMAIL**, um campo para inserção de caractere, deve permitir obrigatóriamente um **@** e um **.com**.
   
   👉 **NOME DO USUÁRIO**, um campo para inserção de caractere, aonde o usuário pode escolher o nome que ficará visivel no menu do sistema.
   
   👉 **SENHA**, um campo para inserção de qualquer tipo de caractere, obedecendo as seguintes regras: Ter mais de 8 caracteres, numeros, letras minusculas, maiusculas e um caractere especial **(@!#$%*)**
   
   👉 **CONFIRMAÇÃO DE SENHA** um campo para inserção de caractere que deve ser idêntica ao campo de senha.

   
    O nome completo e o nome do usuário tem uma diferença, o nome do usuário será mostrado na home do site, e o nome completo sera salvo como requisito de cadastro.

   ### :small_blue_diamond: Tela de Recuperar Senha.
   A recuperação de senha é feita através de um email enviado ao usuário que, nesse email esta contido um link que redireciona a uma tela especifica de recuperar senha, essa tela esta disposta no [miro](https://miro.com/welcomeonboard/TTQ5cmFrS0hOV2RkVk5IZUhVQlVxemxvR0ljV0wwQmVZTUV5MTdZdnk2VWZhaHFJbkI0dmtSNHg5d2NqcUM0VHwzNDU4NzY0NTg4ODY5OTkyODgzfDI=?share_link_id=768665701708), esse link só sera enviado a um cliente que ja esta salvo nos cadastros.
 
   ### :small_blue_diamond: Tela para inserir nova Senha.
   Nessa tela temos, que só é possivel acessar através do link enviado ao email do usuário, podemos inserir a nova senha dentro do campo nova senha, nesse campo tamém existe a opção de mostrar a senha ou esconder ela, e claro para confirmar a senha é preciso que os dois campos estejam iguais.

   ### :small_blue_diamond: Tela Principal.
   A tela principal é aonde o usuário ira poder executar a maior parte das funções do programa, nela foi separado um campo para anuncios, esse campo ele muda de tamanho conforme a responsividade do aplicativo que estiver sendo usado, exemplo: no celular o campo do anuncio é bem menor, logicamente por conta do espaço reduzido na tela, ja no desktop ou tablet temos mais espaço para se trabalhar. Também existe a opção de barra de pesquisa, que o usuário poderá pesquisar dentro do sistema alguma informação que deseja, ou um produto.
   
   #### :small_blue_diamond: Funcionalidades da Tela principal.
   As algumas das funcionalidades é o carrosel, nele é possivel colocar banners informativos sobre o ramo de negócio da empresa ou até mesmo colocar produtos em destaque caso seja uma plataforma de vendas, também temos o menu de usuário, o menu de usuário é possivel ver a imagem de perfil com o nome do usuário, além de ter a opção de alterar senha, logicamente ao clicar na senha é possivel acessar aquela pagina especifica de alteração que só é possivel acessar pelo email, fora essas opções existe também a opção para sair do perfil do usuário.

   #### :small_blue_diamond: Guia de navegação na Tela principal.
   Uma das funcionalidades que aparecem no celular e no tablet é uma engrenagem que fica no canto superior direito do ambiente, essa engrenagem armazena as opções do menu de navegação, esse menu contem **"ACESSIBILIDADE"**, **"Contato"** e **"Sobre"**, nessa barra de navegação o usuário ira poder escolher quais dessas opções deseja acessar.

   ### :small_blue_diamond: Tela de Acessibilidade.
   A acessibilidade é uma funcionalidade muito importante, principalmente quando se trata de incluir usuários e clientes com necessidades especiais no mundo da tecnologia, foi pensando nisso que colocamos essa opção ao usuário, nessa opção sera possivel o usuário escolher o tamanho da letra que deseja que seja usuado no site, para mais facil leitura. Também existe a opção de ajustar o contraste da tela, dessa forma fica mais facil ver determinadas imagens caso necessário. Também existe o modo escuro e recursos assistidos, que aplicam um a voz de uma inteligência artificial para ler as opções que estão aparecendo na tela, essa é uma funcionalidade muito importante para usuários com dificuldade visual ou motora. 
  



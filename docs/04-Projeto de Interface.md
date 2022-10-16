
# Projeto de Interface

Nossa prioridade para a criação da interface do sistema é a de acessibilidade e usabilidade. Assim sendo, o projeto visa um visual limpo e de fácil acesso, juntamente da aplicação de responsividade, para funcionar em dispositivos móveis e desktops.

## User Flow

O diagrama a seguir através da Figura 5, apresenta o fluxo de interação do usuário através das páginas do site. Detalhamos as telas na seção Wireframe a seguir.
Acesso para o Wireframe interativo: [Wireframe interativo](https://marvelapp.com/prototype/iib9edh/screen/89031240).

 O fluxo de telas está direcionado por setas:
 
Seta 1: Ao clicar no ícone de Notificação, abrirá uma tela sobreposta com as notificações existentes para o usuário.

Seta 2: Ao clicar no ícone de Perfil, abrirá uma tela sobreposta com a opção de fazer cadastro ou logar, após preenchido corretamente, o usuário estará logado.

Seta 3: Ao clicar em Atividades, abrirá a página Atividades do site.

Seta 4: Ao clicar em alguma atividade na página Atividades, o usuário será encaminhado para o site externo referente a atividade escolhida pelo usuário.

Seta 5: Ao clicar em Ong Voluntária, o usuário será direcionado para a página Ong Voluntária, permitindo que o usuário crie o perfil da sua ONG / Voluntariado.

Seta 6: Ao clicar em Finalizar, será pedido ao usuário que se cadastre, após o login, o usuário será direcionado a página inicial. 

Seta 7: Após clicar em Seja Voluntário, o usuário será direcionado para a página de Seja Voluntário, dessa forma, tendo acesso aos perfis das ONG´s e Voluntariados.



![VictorFluxoUsuario](https://user-images.githubusercontent.com/71721477/196014933-2746fff0-e419-4e00-8e29-a01580483218.png)

Figura 5 - Fluxo de telas

## Wireframes

Conforme fluxo de telas do projeto, apresentado no item anterior, as telas do sistema são apresentadas em detalhes nos itens que se seguem. As telas do sistema apresentam uma estrutura comum que é apresentada na Figura 6. Nesta estrutura, existem 2 blocos, descritos a seguir. São eles:
* Cabeçalho - Local onde são dispostos elementos fixos de identidade    (logo), redes sociais, notificações e perfil do usuário. O cabeçalho terá a propriedade de acompanhar o scroll do site.
* Conteúdo - Apresenta o conteúdo da tela em questão.

![estruturaPadrao](https://user-images.githubusercontent.com/99758232/195962353-d545f5a0-826b-4942-8874-a48cb554c273.jpeg)

Figura 6 - Estrutura padrão do Site


*Tela - Home-Page*

A tela de home-page tem como destaque a imagem do Projeto Voluntário e um texto introdutório.
Logo abaixo, temos 3 blocos de cadastro para 3 elementos distintos. São eles:
* Bloco ONG voluntário: Cadastro de ONGs/locais que estão disponibilizando o espaço para a realização de voluntariado;
* Bloco Seja Voluntário: É o espaço para as pessoas que estão interessadas em se voluntariar, fazerem o cadastro.
*  Bloco Atividade: Portal de acesso para atividades gratuitas ofertadas na região.
Outro componente da tela de home-page é o Quem somos, que tem como objetivo apresentar, de forma breve, o intuito do projeto . Ao lado, colocaremos imagens das ações sendo realizadas.
Por último, temos um bloco de Tire suas dúvidas, onde disponibilizaremos um campo de mensagem para os usuários e/ou interessados entrarem em contato direto com a equipe desenvolvedora do projeto, seja por dúvidas, elogios, patrocínio etc.

![telaHomePage](https://user-images.githubusercontent.com/71721477/196015607-057433c6-c7da-4743-ae4f-7a480105272c.png)

Figura 7 - Home-Page

*Tela - Notificação*

Tem a finalidade de notificar os usuários quando uma solicitação for respondida, novas vagas adicionadas que são de acordo com o perfil daquele usuário etc.

![LucasFsR](https://user-images.githubusercontent.com/99758232/195962354-00337bcd-8ba3-4c04-964f-bb5ff8fa2305.jpeg)

Figura 8 - Notificação

*Tela - Login*

É a tela de cadastro do usuário, onde ele poderá fazer login utilizando a conta do Facebook, google ou criar uma conta.

![LucasFsR](https://user-images.githubusercontent.com/71721477/196015085-ac12c5c2-afea-450e-b0a7-f5ff656c29b7.png)

Figura 9 - Tela de Login

*Tela - Atividade*

É o espaço que o usuário utilizará para buscar as atividades que mais "combinam" com ele e/ou que ele gostaria de exercer ao utilizar o Projeto Voluntário.
Como destaque, teremos 5 blocos com áreas gerais e, logo abaixo, um botão de filtro detalhado, ou seja, atividades mais específicas sobre aquele assunto. Por exemplo:
* Filtros mais acessados: Saúde
* Filtro detalhado: Saúde feminina
Utilizaremos um hiperlink que irá direcionar para um site externo (site parceiro), que está disponibilizando aquela vaga de interesse do usuário.

![LucasFsR](https://user-images.githubusercontent.com/99758232/195962356-7f94368d-29e7-497d-93fa-7140f5789fa2.jpeg)

Figura 10 - Atividade

*Tela - Filtro de busca*

É o local que o usuário utilizará para procurar vagas disponíveis (O usuário terá a opção de utilizar o filtro por estado ou analisar as vagas em gerais). Essa busca poderá ser feita de 3 formas:

* As vagas que estão em destaque (mais acessadas e/ou relevantes);
* Vagas recém adicionadas;
* Todas as vagas de todas as áreas e habilidades.

![voluntario](https://user-images.githubusercontent.com/71721477/196015298-442a71fe-0315-469d-b9e5-191568edbead.png)

Figura 11 - Voluntario

*Tela - Cadastro da ONG*

Será o local de cadastro da ONG que irá disponibilizar o espaço para captar voluntários. É a tela que conterá informações como: nome do local e logo/imagem, breve texto sobre o perfil do voluntariado, os requisitos  para aquela vaga e um mapa com a localização da vaga para facilitar a rota para o usuário. 

![intituicao](https://user-images.githubusercontent.com/71721477/196015339-6f64c3ee-f071-4688-a97f-5fa718d61702.png)

Figura 12 - ONG/Voluntariado

*Tela - Cadastro realizado com sucesso*

Após clicar em Finalizar, caso o usuário não tenha se cadastrado, terá que efetuar o Login. Caso ja esteja logado, aparecerá um Pop-Up sinalizando que o perfil da vaga foi criado. 










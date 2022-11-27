# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Alguns dos requisitos para realização dos testes de software são:
- Site publicado na Internet 
- Navegador da Internet - Chrome, Firefox, Edge, Opera GX e derivados
- Conectividade de Internet para acesso às plataformas (APIS)

 
## Ferramentas de Testes
Utilizamos como ferramenta o programa Visual Studio Code e o navegador EDGE.

Todos os membros tiveram participação ativa nos testes, tanto via encontro online, quanto por reunião por meio de chat online. Abaixo detalhamos com descrição todos os testes funcionais que foram realizados.

| Caso de Teste | CT-01-Visualizar página principal |
| ------------- | ------------- |
| Requisitos Associados  |  RF-01- O cabeçalho será fixo, acompanhando o usuário por toda home page ao usar a barra de rolagem. Nele irá conter aba de login, notificação e botão home, além do logo e as redes sociais do projeto. ; RF-02 - Deverá conter na página principal 3 cards que permita a inscrição de ONGs e voluntários para a realização e disponibilização de atividades;   RF-03 - O site deve apresentar uma imagem (thumbnail) e uma descrição correspondente ao assunto apresentado;  RF-04 - Ao ampliar ou reduzir os valores do zoom o site deverá manter sua responsividade;  RF-05 Espaço disponível para o usuário entrar em contato e/ou tirar dúvidas relacionadas ao projeto, os campos obrigatórios de preenchimento serão: nome, e-mail e mensagem; RF-06 - O rodapé fixo estará presente em todas as abas do site, contendo um campo de inscrição de e-mail para recebimento de newsletter e o logo daPuc Minas.|
| Objetivo do Teste  | Verificar se todas as abas e ícones estão direcionando para as páginas corretas.|
| Passos | 1) Acessar o Navegador; 2) Informar o endereço do Site; 3) Visualizar a página principal |
| Critérios de Êxito | ● O usuário, ao clicar no card que mais se identifica, será direcionado para a aba específica que quer se inscrever. ● Todos os ícones e abas devem estar direcionando para os locais corretos.   ● No espaço para contato e/ou dúvidas, caso o campo obrigatório não seja preenchido, aparecerá um tooltip com a notificação: Preencha este campo.      ● No campo de inscrição de e-mail para recebimento de newsletter, se não for preenchido, aparecerá um tooltip com a mensagem: Preencha este campo.   ● Ao clicar no logo da Puc Minas, o usuário será direcionado para um link externo. (https://icei.pucminas.br) |



| Caso de Teste | CT-02-Abrir a aba de login |
| --- | --- |
| Requisitos Associados | RF-07 - A aba de login deve permitir ao usuário a inserção dos dados (e-mail e senha) para acessar seu perfil no site. |
| Objetivo do Teste | Verificar se o login será realizado corretamente, obedecendo às regras pré-definidas. |
| Passos | 1) Acessar o Navegador; 2) Informar o endereço do Site; 3) Visualizar a página principal; 4) Clicar na aba de login |
| Critérios de Êxito | ● E-mail: conter um domínio após o uso do @; ● Senha: conter pelo menos 1 letra maiúscula,1 letra minúscula, 1 número, 1 caracter especial (@!#$%&) e mínimo de 8 dígitos; ● Ao não obedecer as regras de preenchimento de campo, será gerado um tooltip com a notificação: “Preencha este campo.". |

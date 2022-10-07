# Especificações do Projeto

As especificações do projeto se definem em localizar a problemática que possui impactos na sociedade, como afeta  e formas de amenizar esses agravantes levantados através do estabelecimento de objetivos e metas. Além disso, a realização de uma pesquisa com possíveis usuários através de entrevistas pessoais e formulários online nos permite criar perfis ideais para a utilização de ferramentas que podem impactar na divulgação desses serviços e também no número de pessoas dentro de movimentos comunitários.

## Personas

As personas levantadas durante o processo de entendimento do problema são apresentadas na Figuras que se seguem.

![LucasFsR](https://user-images.githubusercontent.com/99758232/194666192-585a0b45-c8c7-4f3f-bb55-0c4d837d60ed.jpeg)

![LucasFsR](https://user-images.githubusercontent.com/99758232/194666843-b2a1f55d-c352-4e2c-b589-3d1e3a554411.jpeg)

![LucasFsR](https://user-images.githubusercontent.com/99758232/194666863-1af5a0a7-a8ed-4ffd-b0ed-be92358c2765.jpeg)


## Histórias de Usuários

A partir da compreensão do dia a dia das personas identificadas para o projeto, foram registradas as seguintes histórias de usuários:

|Eu como...     | ...quero/desejo...  | ...para... |
|-------|-------------------------|----|
|Luciana Santos| prestar apoio médico a pessoas de baixa renda | incentivá-las a cuidar da saúde. |
|Pedro Guimarães| promover serviço de amparo a moradores de rua | oferecer mais qualidade de vida àquelas que estão vivendo em situação de vulnerabilidade.  |
|Pedro Guimarães| fornecer cobertores, roupas como casaco, calças etc, sapatos, “barracas” | para uma proteção maior principalmente em dias mais frios. |
|Pedro Guimarães| fazer ações de distribuição de "marmitas" | para ajudar na alimentação de pessoas em situações mais precárias. |
|Mariana Ribeiro| continuar me voluntariando  | ajudar animais que foram abandonados e/ou estão sendo mal cuidados. |
|Mariana Ribeiro| encontrar mais voluntários  | juntos, ajudar um número maior de animais necessitados. |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deve fornecer a funcionalidade de cadastro e login para que os potenciais voluntários e ONGs possam se registrar e ter acesso à plataforma.  | ALTA | 
|RF-002| O sistema deve exigir no cadastro de pessoa física (voluntário) informações pessoais como: nome completo, data de nascimento, foto, endereço, e-mail, telefone, CPF e RG para facilitar a avaliação de perfil e contato com o potencial voluntário por parte das ONGs.   | ALTA |
|RF-003| O sistema deve exigir no cadastro de pessoa jurídica (ONG) informações como: endereço, e-mail, telefone, CNPJ e breve biografia da instituição para facilitar a validação da ONG e inclusão da mesma no mapa interativo do site por parte dos administradores da plataforma.   | ALTA |
|RF-004| O sistema deve disponibilizar um mapa dentro da plataforma que contenha todas as ONGs disponíveis nas redondezas para que o voluntário possa escolher o que lhe for mais conveniente.   | MÉDIA |
|RF-005| O sistema deve disponibilizar uma ferramenta de buscas por frases e palavras-chave, a ferramenta deve ter filtros de busca para que o usuário possa encontrar o que desejar dentro da plataforma com maior facilidade.| MÉDIA |
|RF-006| O sistema deve conter um fórum de perguntas e respostas, semelhante ao famoso “Yahoo Respostas”, para a interação entre todos os usuários da plataforma.| BAIXA |



### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deverá ser uma aplicação web (website). | ALTA | 
|RNF-002| O sistema deverá utilizar um framework front-end para a responsividade do site (adequação à todas plataformas).| MÉDIA | 
|RNF-003| O sistema deverá utilizar como fonte o “font-family: arial, helvetica neue, helvetica, sans-serif” para compatibilidade máxima com a maioria dos navegadores disponíveis na web. | MÉDIA | 
|RNF-004| O sistema deve processar requisições do usuário em no máximo 5 segundos. | BAIXA | 
|RNF-004| O sistema deverá disponibilizar a opção de tema claro ou escuro para que o usuário possa selecionar o que preferir. | BAIXA | 



## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O sistema não terá a opção de selecionar outros idiomas. Todo o website será em Português-BR. |
|02| No momento não será desenvolvido uma estrutura backend para o website. |

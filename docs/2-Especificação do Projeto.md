# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

 Nosso problema em questão trabalha o estimulo cognitivo principalmente das crianças, como suas: habilidades motoras, coordenção, força muscular.
O primeiro projeto é um carrinho projetado especialmente para crianças deficientes pode ajuda-las a se sentirem mais confiantes e independentes,
estimulando na sua autoestima. 
 Nosso segundo projeto, que se trata de luzes que respondem ao toque, pode influenciar no aprendizado da criança, podendo ser utilizado para ensinar 
habilidades basicas como contar, conhecer novas cores, promover interação social e desenvolvimento de linguagem.
.
## Personas


|**Roberto Carlos**|           |                             | 
|-------------------|-----------|-----------------------------|
<img src="https://github.com/ICEI-PUC-Minas-PPC-CC/ppc-cc-2023-1-ment2-noite-aplicacao-interativa/blob/main/Roberto%20Carlos.png" width="200" height="200"/>|**Idade:** 12 anos. **Naturalidade:** Poços de caldas - Minas Gerais. **Ocupação:** Estudante.       |**Atribuições:** Estuda em uma escola regular e participa de grupos de apoio para crianças com deficiência.

|**Hobbies, história:** Roberto nasceu com uma deficiencia nas pernas, que o impede de andar e faz necessario o uso de cadeira de rodas. Nas suas horas vagas, adora ver filmes de aventura e gosta de jogar jogos de videogame, pricipalmente RPG e jogos de mundo aberto.

|**Maria Antonieta**|           |                             | 
|-------------------|-----------|-----------------------------|
<img src="https://github.com/ICEI-PUC-Minas-PPC-CC/ppc-cc-2023-1-ment2-noite-aplicacao-interativa/blob/main/Maria%20Antonieta.png" width="200" height="200"/>|**Idade:** 16 anos. **Naturalidade:** Poços de caldas - Minas Gerais. **Ocupação:** Estudante.       |**Atribuições:** Estuda em uma escola especializada e participar de grupos de apoio para crianças com deficiência.

|**Hobbies, história:** Maria com deficiencia mental, gosta muito de assistir a televisão e brincar no celular e apesar dos desafios, Maria é uma garota muito alegre e simpática, que adora passar tempo com sua família e amigos. Maria frequenta uma escola especializada e tinha uma equipe de apoio que a ajuda com suas atividades diárias. Ela gostava de desenhar e pintar, e muitas vezes surpreende seus professores com suas habilidades artísticas.

Nosso projeto, ou no caso, nossa solução, pode ajudar essas personas da seguintes formas: 

Estimulação sensorial, incentivo à mobilidade, aumento da autoestima, aprendizado e diversão. No caso da persona com deficiencia nas pernas, o nosso projeto  que se refere ao carrinho, sera acessivel, pois o controle sera um pedal funcional pela mão.

## Histórias de Usuários

Com base na análise das personas, foram identificadas as seguintes histórias de usuários:

Exemplo:

|EU COMO... `Roberto Carlos`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Camila Fiães | Otimizar meu tempo e esforço | Conciliar os diferentes papéis que exerço. |
|Camila Fiães | Ter acesso rápido e completo às informações sobre a doença de seu filho | Passar os detalhes para os médicos. |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução ou para execução da sua prática extensionista/curso. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação e também para identificar as dores que sua prática extensionista irá minimizar/sanar. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Obs.1: Caso seu grupo não vá desenvolver uma solução de software, as seções "requisitos funcionais", "requisitos não funcionais" e "restrições" DEVERÃO ser REMOVIDAS.
## Obs.2: Caso seu grupo não vá desenvolver algum atividade que demande, uma pesquisa de campo através de questinários, a seção "artefatos para levantamento de dados" DEVERÁ ser REMOVIDA.

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deverá permitir o gerenciamento dos pacientes | ALTA | 
|RF-002| O sistema deverá exibir todo histórico de atendimento do paciente   | ALTA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo | MÉDIA | 
|RNF-002| o sistema deve processar requisições do usuário em, no máximo, 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

### Artefatos para levantamento de dados

Nesta seção, caso seu grupo vá realizar algum tipo de levantamento de dados/entrevistas, descreva o(s) artefato(s) produzidos para tal. Também deverá ser descrita qual estratégia será utilizada para este levantamento. Por exemplo: como os questionários serão aplicados? (_in loco_, via disponibilização pela _web_ etc), qual material/estratégia de divulgação será utilizado? 

Não se preocupe em descrever os resultados agora, eles deverão ser descritos apenas na seção "Detalhamento preliminar" (Etapa 03).

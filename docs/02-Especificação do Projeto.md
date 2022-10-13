# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros.

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:


## Histórias de Usuários

A partir da compreensão do dia a dia das personas identificadas para o projeto, foram registradas as seguintes histórias de usuários.

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Jehan               | Encontra meu pet em um raio de 5 km           | Não esquecer de fazê-las               |
|Amanda Alves        | Visualizar notícias mais alinhadas com minha área de atuação| Permitir que possam administrar contas |
|Cleber Fernades     | Monitorar meu pet                 | Saber onde ela está 24hs por dia para que não o perca |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O site deve pedir o cadastro do usuário para poder publicar informações sobre o seu pet perdido ou sobre um pet encontrado | ALTA | 
|RF-002| O site deve permitir que o usuário publique uma notícia sobre o seu pet perdido | ALTA |
|RF-003| O site deve permitir que o usuário publique informações sobre um pet que foi encontrado | ALTA |
|RF-004| O site deve incorporar um sistema de troca de mensagens entre os usuários | ALTA |
|RF-005| O site deve solicitar acesso a localização do usuário para fornecer informações sobre notícias próximas do usuário | MÉDIA |
|RF-006| O site deve enviar email atualizando o usuário sobre suas postagens | MÉDIA |
|RF-007| O site deve permitir o compartilhamento de notícias visualizadas em plataformas de redes sociais | MÉDIA |
|RF-008| O site deve permitir salvar postagens preferidas | BAIXA |
|RF-009| O site deve permitir verificar as postagens salvas como preferidas | BAIXA |
|RF-0010| O site deve permitir que usuários possam comentar postagens | BAIXA |
|RF-0011| O site deve exibir os comentários registrados juntamente com a postagem exibida | BAIXA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deverá ser responsivo permitindo a visualização em um celular de forma adequada |  BAIXA | 
|RNF-002| O site deve respeitar a LGPD |  ALTA | 
|RNF-003| O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge) |  BAIXA | 


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

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

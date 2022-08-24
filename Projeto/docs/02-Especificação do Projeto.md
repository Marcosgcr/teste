# Especificações do Projeto

A definição exata do problema e os pontos mais relevantes a serem tratados neste projeto foi consolidada com a participação dos usuários em um trabalho de imersão feita pelos membros da equipe a partir da observação dos usuários em seu local natural e por meio de entrevistas. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários. 

## Personas

Ana Clara Pereira tem 35 anos e possui um carro 100% elétrico. Por causa da limitação de locais para recarregar o carro, ela gosta de parar em um estacionamento onde é oferecido um sistema de recarga para que, em dias que precisa de usar mais o carro, ela não fique sem bateria para chegar em casa.

Augusto Silva tem 42 anos e é vendedor. Como ele que visitar clientes constantemente, gosta de saber onde tem estacionamentos próximos dos clientes e reservar a sua vaga para não atrasar nos seus encontros.

Carlos Alves tem 29 anos e se desloca de carro ao trabalho todos os dias. Gosta da segurança e praticidade de um estacionamento privativo, mas deseja economizar na mensalidade/anuidade ao pagar o estacionamento. Para isto, ele prefere estacionar em um local em que haja um convênio com a empresa em que trabalha.

Diego Costa possui 45 anos e desloca todos os dias do seu trabalho para buscar seu filho na escola. Para não deixar seu carro em fila dupla ele deseja verificar antes de sair do seu trabalho as vagas próximas da escola reservando assim a vaga.

Luisa Ruiz tem 21 anos e está buscando seu tio que fez uma operação na perda. Já que seu tio possui limitação ao se locomover, ela então necessita de um local o mais próximo do hospital para facilitar ao busca-lo.

Pedro Pascoal tem 34 anos, é deficiente físico e usa seu direito de vagas preferenciais. Prefere se locomover a locais que possuem vagas preferenciais disponíveis, assim é importante a descrição de vagas preferenciais.

Rita Luz é uma idosa de 61 anos e se locomove com seu carro para os locais que dirige sozinha. É importante usar uma vaga preferencial para facilitar a lomocomoção debilitada da mesma.

Michael Oliveira tem 31 anos e é um fanático por seu carro. Valoriza bastante o seu automóvel e por isso acha importante aréas cobertas para proteger seu carro do sol. Não se importa em pagar um estacionamento privativo, desde que haja cobertura para seu carro.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
| Ana Clara Pereira  |	Estacionamento com recarga para carro eletrico |	Para que ela não fique sem bateria para continuar o seu afazeres diários |
| Augusto Silva | Estacionamento próximo a seus clientes | Para não perder tempo procurando vaga |
| Carlos Alves  | Estacionamento conveniada com sua empresa | Para economizar na hora de estacionar o carro nas visitas |
| Diego Costa   | Estacionar o carro próximo a escola | Aguardar o fim do período da aula do filho para busca-lo estando próximo da escola |
| Luiza Ruiz    | Estacionar o carro próximo ao hospital| Buscar um familiar no hospital tendo o maior conforto possível numa vaga mais próxima ao hospital |
| Pedro Pascoal | Classificação de vagas para deficiente físico | Possui deficiência física, assim busca vagas preferencias para melhor se locomover |
| Rita Luz | Classificação de vagas para idosos | Deseja usufruir seu direito como idosoa para usar vaga preferencial |
| Michael Oliveira | Classificação de vagas cobertas | Fanático pelo bem estar físico do seu carro e deseja uma vaga coberta |

## Requisitos

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir.

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues.

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
| RF-001 | O site deve apresentar a funcionalidade de buscador (search) | ALTA | 
| RF-002 | O site deve apresentar categorias de vagas para facilitar a busca dos usuários | MÉDIA |
| RF-003 | O site deve apresentar as informações do estabelecimento (serviços extras que é oferecido) |ALTA |
| RF-004 | $$ O site deve apresentar mecanismos para avaliação dos estabelecimentos através de comentário e notas | MÉDIA |
| RF-005 | $$ O site deve recomendar estabelecimentos de acordo com o perfil de cada usuário | MÉDIA |
| RF-006 | $$ O site deve possuir um filtro para refinar a busca do usuário | ALTA |
| RF-007 | $$ O site deve ter seus vídeos com legendas, tela com sinais de linguagem e/ou áudio descrição | BAIXA |
| RF-008 | $$ O site deve possuir uma área de login para que o usuário possa fazer determinadas ações no site | ALTA |
| RF-009 | $$ O site deve possuir uma área de login para as empresas poderem administrar as suas informações | ALTA |
| RF-010 | $$ O site deve possuir uma área para cadastrar novos usuários, prestadores e empresas | ALTA |
| RF-011 | $$ O site deve possuir uma área para cadastrar e editar as especificações do seu estabelecimento | ALTA |
| RF-012 | $$ O site deve possuir dentro da área de login da empresa um resumo de feedback dos usuários | MÉDIA |
| RF-013 | $$ O site deve possuir um canal de comunicação direto com os criadores dentro da área de login de usuários e empresas | BAIXA |
| RF-014 | $$ O site deve ter dentro da área de login de usuários uma sessão de locais favoritados | MÉDIA |
| RF-015 | $$ O site deve possuir uma categoria “Sobre Nós” | BAIXA |
| RF-016 | $$ O site deve apresentar informações sobre acessibilidade como leis, importância, etc... | MÉDIA |
| RF-017 | $$ O site deve apresentar um ranking com os estabelecimentos mais bem avaliados | MÉDIA |
| RF-018 | $$ O site deve apresentar distinção de vagas preferenciais para grávidas | ALTA |
| RF-019 | $$ O site deve apresentar distinção de vagas preferenciais para idosos | ALTA |
| RF-020 | $$ O site deve apresentar distinção de vagas preferenciais para deficiente físicos | ALTA |
| RF-021 | $$ O site deve apresentar distinção de vagas cobertas | ALTA |
| RF-022 | $$ O site deve apresentar distinção de vagas que suportam carregamento de carros elétricos | ALTA |

### Requisitos não Funcionais

A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender.

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| $$ O site deve ser responsivo | ALTA | 
|RNF-002| $$ O site deve ser compatível com os principais navegadores | ALTA | 
|RNF-003| $$ O site deve ter acessibilidade digital, seguindo as regras da WCAG 2.1 conforme normas da W3C | MÉDIA |

## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir. 

|ID   | Restrição                                             |
|-----|-------------------------------------------------------|
|RE-01| $$ O projeto deverá ser entregue no final do semestre, não podendo extrapolar a data de 31/07/2022 |
|RE-02| $$ O site deve se restringir às tecnologias básicas da Web no Frontend |
|RE-03| $$ A equipe não pode subcontratar uma empresa para ajudar a desenvolver o design do site |
|RE-04| $$ A equipe não pode subcontratar uma empresa para a criação do conteúdo do site |
|RE-05| $$ O site só poderá ser lançado se os requisitos de funcionalidade e acessibilidade quando forem atendidas|


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)

# 1. Explique os papéis e as cerimônias principais do framework Scrum.
  O framework Scrum é uma abordagem ágil para o desenvolvimento e gestão de projetos, estruturada em ciclos curtos de trabalho e 
 fundamentada na colaboração e transparência. 
 Seus componentes principais dividem-se em papéis específicos e cerimônias (eventos) obrigatórios.
## Papéis Principais no Scrum
  A equipe Scrum é composta por três papéis fundamentais que trabalham de forma integrada:

- Product Owner (Proprietário do Produto): É o responsável por maximizar o valor do produto.
  Ele atua como o ponto central de contato entre os interessados (stakeholders) e a equipe,
  gerenciando e priorizando o Product Backlog (a lista de funcionalidades)
  É quem define os objetivos de cada ciclo de trabalho

- Scrum Master: Atua como um facilitador e coach da equipe, garantindo que as práticas e valores do Scrum sejam compreendidos
  e aplicados.
  Sua função inclui a remoção de impedimentos que atrapalhem o progresso dos desenvolvedores e a facilitação das cerimônias

- Developers (Equipe de Desenvolvimento): É um grupo auto-organizado e autogerido de profissionais (geralmente entre 3 a 9 pessoas)
  que decide como realizar o trabalho técnico para atingir os objetivos da Sprint.
  Eles são responsáveis por garantir a qualidade e entregar um incremento funcional ao final de cada ciclo

## Cerimônias (Eventos) do Scrum
Os eventos do Scrum são projetados para criar rotina e minimizar a necessidade de reuniões não definidas no framework:

### Sprint: 
É o coração do Scrum. Corresponde a um ciclo de desenvolvimento com duração fixa (geralmente de 2 semanas a 1 mês), 
onde um incremento de software é produzido.
### Sprint Planning (Planejamento da Sprint): 
Reunião realizada no início de cada ciclo para definir o objetivo da Sprint, selecionar quais itens do backlog serão trabalhados
e planejar como o trabalho será executado.
### Daily Scrum (Reunião Diária): 
Um evento de 15 minutos para que a equipe de desenvolvimento inspecione o progresso em relação à meta da Sprint. 
Nela, discute-se o que foi feito, o que será feito a seguir e se existem barreiras ou impedimentos.
### Sprint Review (Revisão da Sprint): 
Ocorre ao final da Sprint para que a equipe demonstre os resultados ao Product Owner. 
Serve para validar os itens entregues e verificar se o objetivo inicial foi atingido.
### Sprint Retrospective (Retrospectiva da Sprint): 
É o momento final do ciclo, focado na inspeção e adaptação do processo da própria equipe, visando melhorias para a próxima Sprint.


# 2. Explique o que é user story e seu papel na engenharia de software
  Uma User Story (História de Usuário) é uma descrição resumida de uma necessidade do usuário, escrita sob o seu ponto de vista.
Na engenharia de software moderna, especialmente em métodos ágeis como o Scrum, elas substituem os extensos documentos de requisitos 
tradicionais por uma forma mais leve e pragmática de documentação.
Abaixo estão os detalhes sobre sua estrutura e o papel que desempenha:

## 1. A Estrutura dos "Três C's"
Uma User Story não é apenas uma frase; ela é composta por três aspectos fundamentais:
### Cartão (Card): 
É o lembrete físico ou digital da necessidade do usuário. 
Geralmente segue o formato padrão: "Como [quem], desejo [o quê] para [por que/valor de negócio]".
### Conversa (Conversation): 
É a parte mais importante. 
Como o cartão é propositalmente resumido, os detalhes são refinados através de discussões verbais frequentes entre o Product Owner e a 
equipe de desenvolvimento.
### Confirmação (Confirmation): 
São os critérios de aceitação. 
Eles definem as condições específicas que a funcionalidade deve atender para ser considerada "pronta" e aceita pelo cliente.

## 2. O Papel na Engenharia de Software
As User Stories desempenham várias funções cruciais no ciclo de vida de desenvolvimento:

- Gestão do Backlog: Cada User Story representa um item individual no Product Backlog.
O Product Owner as prioriza conforme o valor que agregam ao negócio.

- Planejamento de Sprints: Durante o planejamento, as histórias são estimadas pelos desenvolvedores
(muitas vezes usando técnicas como o Planning Poker) e decompostas em tarefas técnicas menores para serem executadas durante a Sprint.

- Fomento à Comunicação: Elas funcionam como uma "promessa de uma conversa futura", garantindo que desenvolvedores e clientes interajam constantemente para evitar
interpretações erradas de requisitos.

- Design Incremental: Ao focar em pequenas funcionalidades por vez, as histórias permitem que o design do sistema evolua gradualmente,
em vez de exigir um projeto completo e rígido antes do início da codificação.

## 3. Características de uma Boa User Story (INVEST)
Para ser eficaz, uma história deve seguir o acrônimo INVEST:

**Independente** (pode ser implementada em qualquer ordem).
**Negociável** (detalhes são discutidos, não ditados).
**Valiosa** (deve trazer benefício claro ao negócio).
**Estimável** (os desenvolvedores devem conseguir prever o esforço).
**Small/Pequena** (deve caber dentro de uma única iteração ou Sprint).
**Testável** (deve possuir critérios de aceitação objetivos).

Em resumo, o papel da User Story é servir como uma ponte de comunicação entre o problema de negócio e a solução técnica, 
garantindo que o que está sendo construído realmente resolva as necessidades dos usuários.

# 3. O que é kaban, e como ele é utilizado no desenvolvimento de softwares?
O Kanban é um método ágil cujo nome de origem japonesa significa "cartão visual" ou "cartão de sinalização", 
tendo suas raízes no sistema de produção just-in-time da Toyota na década de 50. 
No contexto do desenvolvimento de software, ele foi introduzido por David Anderson na Microsoft em 2004, 
sendo utilizado para promover um ritmo sustentável de trabalho, eliminar desperdícios e entregar valor com frequência através 
de melhorias contínuas.
Abaixo estão os detalhes de como ele é utilizado no desenvolvimento de sistemas:
## 1. O Quadro Kanban e o Sistema Pull
A utilização do Kanban centra-se no Quadro Kanban (Kanban Board), que funciona como um índice visual do fluxo de trabalho.

### Colunas de Processo: 
O quadro é dividido em colunas que representam os passos necessários para transformar uma necessidade em funcionalidade 
(ex: Backlog, Especificação, Implementação, Revisão e Concluído).

### Sistema Pull (Puxado): 
Diferente de modelos tradicionais, o Kanban é um sistema pull, onde os membros da equipe "puxam" as tarefas para a próxima etapa apenas 
quando possuem capacidade, evitando o empilhamento de trabalho.

### Visualização: 
O método prioriza a transparência, permitindo que qualquer membro identifique rapidamente gargalos ou interrupções no fluxo.

## 2. Limites WIP (Work in Progress)
O uso de Limites WIP é o recurso fundamental para garantir a qualidade e a saúde da equipe.
Estes limites definem o número máximo de itens que podem estar em uma determinada etapa simultaneamente.
O objetivo é impedir a sobrecarga, forçando o time a concluir as tarefas atuais antes de iniciar novas, 
o que reduz o tempo de entrega e melhora o foco.

## 3. A Lei de Little e Métricas
Para gerenciar o sistema de forma quantitativa, o Kanban utiliza a Lei de Little para calcular os limites WIP ideais.
A fórmula estabelece que WIP = Throughput (Vazão) × Lead Time (Tempo Médio).
Isso permite que os times estimem quanto trabalho podem suportar baseando-se na sua velocidade histórica e no tempo que cada tarefa 
leva para ser concluída.

## 4. Flexibilidade e Papéis
Diferente do framework Scrum, o Kanban é considerado um método mais leve e flexível:

**Sem Papéis Fixos**: Não exige a existência de figuras como Scrum Master ou Product Owner; 
os papéis são definidos conforme a necessidade da organização.

**Sem Iterações Rígidas**: Não utiliza ciclos de tempo fixos (Sprints); 
o fluxo é contínuo e as entregas podem ocorrer a qualquer momento em que uma tarefa seja concluída.

**Eventos Opcionais**: Reuniões diárias ou retrospectivas podem ser realizadas, mas não são prescrições obrigatórias do método.

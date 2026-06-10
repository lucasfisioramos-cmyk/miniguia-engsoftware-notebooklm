O notebooklm conta com cards no campo estudio, com tarefas pré programadas, capazes de gerar audio: um podcast explorando o assunto, 
apresentação de slides com imagens criadas por IA, resumo em video, mapa mental, relatorio, cartoes didaticos (anki), 
teste interativo com perguntas e respostas, infografico, e tabela de dados. 

Cada card ja possui um prompt pronto. no entanto é possivel personalizar o comando tambem. 

Alguns exemplos criados neste notebook:
- Apresentação com IA
[The_Software_Blueprint.pdf](https://github.com/user-attachments/files/28808943/The_Software_Blueprint.pdf)

- Relatorio para estudos:
      Briefing: Fundamentos e Desafios da Engenharia de Software
      
      Este documento sintetiza os princípios fundamentais, a natureza técnica e os desafios críticos do desenvolvimento de software,
      com base nas perspectivas da Engenharia de Software clássica e moderna.
      
      Sumário Executivo
      
      O software é definido não apenas como código, mas como um ecossistema que engloba instruções, dados e documentação,
      funcionando como a base estratégica das organizações contemporâneas. O desenvolvimento de software enfrenta desafios
      persistentes relacionados a custos elevados, atrasos cronológicos e falhas na detecção de erros.
      A análise revela que a origem da maioria dos problemas reside na negligência da fase de levantamento de requisitos
      e na adesão a "mitos" de gestão e execução.
      A Engenharia de Requisitos emerge como a etapa mais crítica, distinguindo o que o sistema faz (Requisitos Funcionais)
      de como ele deve se comportar sob restrições (Requisitos Não-Funcionais). O sucesso de um projeto depende da transição
      de descrições genéricas para especificações técnicas e métricas quantificáveis.

        1. Definição e Natureza do Software
      
      O software transcende a simples execução de código. Ele é compreendido como um conjunto de instruções que produzem funções
      e desempenho desejados, integrando:
      
      * Arquivos de configuração e estruturas de dados.
      * Documentação do sistema (para desenvolvedores) e do usuário.
      
      Características Distintivas
      
      Diferente de produtos manufaturados, o software possui uma natureza puramente lógica e intelectual:
      
      * Engenharia vs. Manufatura: O software é projetado ou desenvolvido; ele não é fabricado no sentido clássico.
      * Deterioração vs. Desgaste: O software não sofre desgaste físico com o tempo, mas se deteriora devido a alterações mal
      planejadas e à falta de manutenção adequada.
      * Papel Estratégico: Atua como o elemento diferencial para produtos e serviços, sendo a base de sustentação das organizações modernas.
      
      Classificação de Produtos
      
      1. Produtos Genéricos: Desenvolvidos para o mercado amplo (ex: Processadores de texto, SGBDs).
      2. Produtos Sob Encomenda (Personalizados): Desenvolvidos para atender necessidades específicas de um cliente
      (ex: Sistemas acadêmicos, ERPs como o SAP).
      
      2. A Crise no Processo de Desenvolvimento
      
      O setor de software lida com questionamentos recorrentes sobre a eficiência da produção. As principais preocupações incluem:
      
      * Incerteza Cronológica: Dificuldade em concluir projetos nos prazos previstos.
      * Custos Elevados: Gastos de produção frequentemente acima do orçado.
      * Invisibilidade do Progresso: Complexidade em medir o avanço real durante o desenvolvimento.
      * Persistência de Erros: Impossibilidade de detectar todas as falhas antes da entrega ao cliente.
      
      Origem dos Problemas
      
      A falha em projetos de software geralmente decorre de:
      * Subestimação do tempo necessário para entender o problema e levantar requisitos.
      * Estimativas de custo e duração irreais.
      * Ausência de métodos e técnicas estruturadas de trabalho.
      
      3. Mitos e Realidades do Desenvolvimento
      
      A indústria é cercada por percepções equivocadas que comprometem a qualidade final do produto.
      Estes mitos dividem-se em três categorias principais:
      
      Mitos de Gerenciamento
      
      Mito	Realidade
      Manuais de padrões garantem o sucesso.	A equipe deve aplicar efetivamente os conhecimentos; manuais devem refletir práticas
      modernas.
      Hardware de ponta garante qualidade.
      Ferramentas CASE (Engenharia de Software Auxiliada por Computador) são mais cruciais que o hardware.
      Aumentar a equipe resolve atrasos.	Adicionar pessoas a um projeto atrasado pode torná-lo ainda mais lento devido ao
      tempo de treinamento.
      
      Mitos do Cliente
      
      * Descrições Breves Bastam: O cliente deve definir precisamente funções, desempenho, interfaces e restrições.
      Requisitos vagos levam ao fracasso.
      * Flexibilidade Sem Custos: Embora o software seja flexível, alterações de requisitos geram custos.
      O impacto financeiro das mudanças cresce exponencialmente conforme o projeto evolui.
      
      Mitos do Profissional
      
      * O Trabalho Termina na Entrega: Entre 50% e 70% do esforço de software ocorre após a entrega ao cliente
      (manutenção e evolução).
      * Qualidade só é Medida com o Software Rodando: A garantia de qualidade deve ocorrer em todas as etapas,
      através de revisões de documentos de projeto.
      * O Único Produto Entregável é o Programa: Um projeto de qualidade exige um conjunto robusto de documentos,
      além do código funcional.
      
      4. Engenharia de Requisitos
      
      Definir precisamente o que construir é apontado como a tarefa mais difícil na construção de sistemas.
      A Engenharia de Requisitos organiza-se em duas frentes principais:
      
      Requisitos Funcionais (RF)
      Definem o que o sistema deve fazer (suas funcionalidades).
            * Exemplo em Home-Banking: Informar saldo, realizar transferências, pagar boletos.
      
      Requisitos Não-Funcionais (RNF)
      Definem restrições e a qualidade do serviço prestado. Devem ser especificados de forma quantitativa para evitar ambiguidades.
            * Exemplo: Disponibilidade do sistema, tempo de resposta, níveis de segurança.
      
      Exemplos de Métricas para Requisitos Não-Funcionais:
      * Disponibilidade: Em vez de "alta disponibilidade", definir "99,99% de disponibilidade".
      * Desempenho: Em vez de "sistema rápido", definir "99% das transações devem responder em até 1 segundo".
      
      Técnicas de Especificação e Validação
      A Engenharia de Software Moderna utiliza diversas abordagens para validar requisitos:
      
      * Histórias de Usuários: Instrumento principal em Métodos Ágeis.
      * Casos de Uso: Documentação tradicional e detalhada.
      * Produto Mínimo Viável (MVP): Usado para prospectar e validar requisitos no mercado.
      * Testes A/B: Técnica moderna para definir requisitos com base no comportamento real do usuário.
      
      5. Conclusão da Análise
      
      A documentação enfatiza que a Engenharia de Software não é apenas um exercício técnico de programação,
      mas um processo rigoroso de comunicação, modelagem e gestão de expectativas.
      A falha na comunicação entre as partes (cliente, analista, programador e consultor)
      frequentemente resulta na entrega de produtos que não resolvem o problema real do usuário, gerando retrabalho e
      desperdício de recursos.
      O uso de métricas quantitativas e a revisão contínua em cada etapa do ciclo de vida são fundamentais para mitigar os riscos
      inerentes à natureza abstrata do software.

  <img width="2517" height="3537" alt="NotebookLM Mind Map" src="https://github.com/user-attachments/assets/9de042f5-e55c-4e41-8f65-d4426a47fd80" />


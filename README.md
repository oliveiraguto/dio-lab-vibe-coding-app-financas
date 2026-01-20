# 💸 Um app simples de Finanças Pessoais usando Vibe Coding

Usando a IA como meu fiel escudeiro, faço minha primeira "programação" usando os conceitos gerais de Vibe Coding.

Brevemente, o Vibe Coding é uma forma de você poder programar sem necessariamente saber usar códigos (exe Python, JavaScript), mas sim usando a Linguagem Natural. Essa mesma que você está lendo neste exato momento.

A partir dela, podemos fazer o nosso PRD (Product Requirement Document), que em outras palavras para melhor entendermos, se define como um documento que descreve de forma muito objetiva, os requesitos primordiais de um produto. Dessa forma, objetiva e clara, conseguimos ajustar e manter em um norte equipes de diversas áreas, seja do físico ao programacional, e termos uma visão do produto, como funcionará, critérios, restrições. problemas que possam surgir, e cronograma. 

É de suma importância termos em mente conceitos básicos de objetividade e clareza nestes projetos, e é aí que a IA entra e nos auxilia para garantir que o PRD nos sirva como guia para reduzir possíveis erros (que irão surgir), evitar retrabalhos e nos garantir que todos tenham a mesma direção.

 Segue o prompt refinado do PRD que pude desenvolver junto ao Copilot Web (Smart):

````markdown 
# PRD – Aplicativo de Organização de Finanças Pessoais (com Design Universal)

## Contexto
O aplicativo tem como objetivo simplificar o controle financeiro pessoal por meio de uma interface conversacional (chat e voz).  
A proposta é substituir formulários e planilhas complexas por interações naturais, acessíveis e intuitivas.  
Princípio orientador: todo o design será baseado em Design Universal, garantindo que o máximo de pessoas, independentemente de idade, escolaridade ou condição física/cognitiva, possam usar o aplicativo com boa experiência.

## Problema
Usuários frequentemente abandonam aplicativos de finanças porque:
- Exigem muita entrada manual de dados.  
- Oferecem pouca personalização.  
- Não são inclusivos para diferentes perfis de usuários.  

O desafio é criar uma experiência fluida, baseada em conversas, que incentive o usuário a manter o hábito de organizar suas finanças, sem barreiras de acessibilidade.

## Público-Alvo
- Pessoas que desejam iniciar o controle financeiro de forma prática e sem complicações.  
- Indivíduos de qualquer idade ou nível de escolaridade, especialmente iniciantes.  
- Usuários com diferentes necessidades de acessibilidade (ex.: pessoas com baixa visão, dificuldades motoras ou cognitivas).

## Funcionalidades-Chave
1. Autenticação simples: Tela de login com opção de recuperação de senha, acessível e clara.  
2. Registro de gastos via chat/voz: Entrada em linguagem natural, com suporte a texto e áudio.  
3. Classificação automática: Transações categorizadas com data e hora do gasto.  
4. Metas financeiras: Definição e acompanhamento de objetivos (ex.: economizar R$200/mês).  
5. Agente Financeiro inclusivo: Recomendações automáticas de economia, com reforços positivos e linguagem acessível.  
6. Relatórios personalizados e acessíveis: Visualização clara dos gastos e metas, com opções de contraste, leitura em voz alta e simplificação visual.

## Entregável da IA
- Plano de MVP:  
  - Principais telas: Login, Chat, Relatórios, Metas.  
  - Recursos necessários: Processamento de linguagem natural, categorização automática, sistema de notificações, recursos de acessibilidade (voz, contraste, navegação simplificada).  
  - Validação inicial: Teste com grupo piloto diverso de usuários, incluindo pessoas com diferentes níveis de experiência digital e necessidades de acessibilidade.  
- Linguagem acessível e em português, para garantir inclusão e simplicidade.
````
Interações com o Lovable:

> Olá! Crie um app de finanças baseado no seguinte PRD (Product Requirements Document):

> Ao interagir com o chat, preciso que registre os gastos nos "Gastos do Mês", e os registrando também no histórico "Últimas Transações"

Resultado final no Lovable: https://conversa-financeira-amigavel.lovable.app

![Captura de tela 2026-01-20 131130](https://github.com/user-attachments/assets/0ace83c0-8b5a-4cae-95f1-16f834981da3)
![Captura de tela 2026-01-20 131225](https://github.com/user-attachments/assets/3604e69f-af96-4b12-af90-7b1ddefef4ff)

  
# Resumo das Funcionalidades do App "Conversa Financeira Amigável"

## Visão Geral
O aplicativo oferece um painel financeiro pessoal com foco em simplicidade e clareza. Ele permite ao usuário visualizar rapidamente seu saldo, receitas, gastos e categorias de despesas, promovendo uma gestão financeira acessível e amigável.

## Funcionalidades Principais

- **Resumo Financeiro**
  - Exibição do saldo total atual.
  - Visualização das receitas e gastos do mês.

- **Análise por Categoria**
  - Distribuição dos gastos por categoria (ex: Transporte, Alimentação).
  - Percentual de cada categoria em relação ao total de gastos.

- **Histórico de Transações**
  - Lista das últimas transações realizadas.
  - Detalhamento por categoria, data e valor.

- **Interface Amigável**
  - Saudação personalizada ao usuário.
  - Design limpo e intuitivo com foco na experiência.

## Requisitos Funcionais (do PRD aplicados)
1. O sistema deve exibir métricas financeiras em tempo real.
2. Deve permitir navegação simples entre seções do dashboard.
3. Deve apresentar os dados de forma clara e responsiva.
4. Deve permitir expansão futura (ex: novas categorias, gráficos).

## Requisitos Não Funcionais
- **Performance**: carregamento rápido das informações.
- **Usabilidade**: interface acessível e acolhedora.
- **Segurança**: proteção básica dos dados financeiros.
- **Escalabilidade**: estrutura preparada para novos recursos.

## Critérios de Sucesso
- Usuário entende sua situação financeira em menos de 3 cliques.
- Feedback positivo sobre clareza e simplicidade.
- Compatibilidade com dispositivos móveis.

## Observações
- O app ainda não apresenta receitas registradas no mês, o que pode indicar uma área a ser desenvolvida.



- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
Um bom refinamento no uso do Copilot, ir lapidando e o aperfeiçoando foi algo que funcionou bem. Pensando em ajustes possíveis, ilimitação de funções e edições, tentei pensar na maioria dos prós e contras em que eu poderia encontrar dentro do que posso entregar de maneira certiva por agora.

  - O que não funcionou como o esperado?
Usando o Lovable, ele limita o número de ações usando a versão gratuita do site, e com isso, algumas funções do app não ficaram totalmente funcionais quanto eu gostaria.

  - O que aprendeu sobre conversar com IAs?
Aprendi e aprendo que uma interação bem acertiva com as IAs otimiza e facilita nosso dia a dia, a dando informações sólidas através de um início meio e fim.

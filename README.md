# dio-treinamento-projeto1
**Projeto de Estudo para Bootcamp DIO: Notebook LM**

**Contexto e Objetivos**
Objetivo: Explicar de forma simples e objetiva para empresários de PME's, o que é a LGDP (Lei Geral de Proteção de Dados Pessoais) - Lei 13.709 de 14 de agosto de 2018. A explicação tem a finalidade de esclarecer aos empresários de pequenas e médias empresas o que é a LGPD e quais são os impactos e ações necessárias para que as PME's se adequem à esta lei.

**Curadoria de Fontes:**
https://www2.camara.leg.br/legin/fed/lei/2018/lei-13709-14-agosto-2018-787077-publicacaooriginal-156212-pl.html

https://www.youtube.com/watch?v=eHSO_ae8QXo&t=46s

https://sebrae.com.br/subsites/lgpd

**Engenharia de Prompts e "Cicatrizes":**
Prompt: 
Gere uma apresentação em slides Powerpoint para ser utilizada como base para explicar, de forma simples e objetiva, a empresários de PME's, o que é a LGDP (Lei Geral de Proteção de Dados Pessoais / Lei 13.709 de 14 de agosto de 2018). A explicação tem a finalidade de esclarecer aos empresários de pequenas e médias empresas varejistas o que é a LGPD e quais são os impactos em seus negócios e ações necessárias para que fiquem adequadas à esta lei.
Após a geração da apresentação, gere também:
- um resumo estruturado sobre o conteúdo da apresentação
- um glossário com os principais conceitos aprendidos.
- dois prompts que possam ser reutilizáveis para revisão sobre o tema.

**Miniguia de Estudo (Entrega Final):**
Apresente o resultado final consolidado, que deve conter:

**Resumo Estruturado da Apresentação**
Fundamentos da LGPD: A Lei Geral de Proteção de Dados (Lei 13.709/2018) foca na privacidade, segurança e autodeterminação informativa dos cidadãos.

 - Ela se aplica a qualquer operação de tratamento de dados realizada no Brasil para fins econômicos, abrangendo desde grandes instituições até pequenos negócios varejistas.
 - Agentes e Responsabilidades: Titular: A pessoa física dona dos dados (clientes e funcionários).
 - Controlador: O empresário ou a empresa que decide como os dados serão
   usados.
 - Operador: Quem executa o tratamento em nome da empresa (ex: sistemas de PDV ou contabilidade).
 - Encarregado (DPO): O elo de comunicação entre a empresa, os clientes   e a ANPD.
 - Direitos dos Clientes: O varejista deve estar pronto para atender pedidos de confirmação de existência de dados, acesso, correção, anonimização ou exclusão de informações.
 - Fiscalização e Penalidades: A ANPD é o órgão responsável por zelar  pela lei.
 - O descumprimento pode gerar de advertências a multas de até 2% do   faturamento (limitadas a R$ 50 milhões por infração), além do bloqueio ou eliminação dos dados, o que pode paralisar as vendas.
 - Ações Práticas para PMEs: A adequação exige a revisão de processos internos, adoção de medidas de segurança da informação (TI) e transparência total sobre o uso dos dados.
 - O Sebrae e a ANPD possuem parcerias para facilitar essa jornada para as micro e pequenas empresas.

**Glossário de Conceitos Chave**

-   **ANPD (Autoridade Nacional de Proteção de Dados):** Órgão da administração pública responsável por fiscalizar e implementar a LGPD.
-   **Dado Pessoal:** Qualquer informação que identifique ou possa identificar uma pessoa viva.
-   **Dado Pessoal Sensível:** Dados sobre origem racial, convicção religiosa, saúde, vida sexual ou biometria.
-   **Encarregado (DPO):** Pessoa indicada pelo controlador para atuar como canal de comunicação com os titulares e a autoridade nacional.
-   **Legítimo Interesse:** Uma das hipóteses que permite o tratamento de dados para apoiar e promover as atividades da empresa, desde que respeitados os direitos do titular.
-   **Tratamento:** Toda e qualquer operação com dados, como coleta, armazenamento, compartilhamento ou eliminação.
 
**Prompts Reutilizáveis para Revisão**

**Prompt 1: Revisão de Coleta no Ponto de Venda (PDV)**
Este prompt serve para auditar se a coleta de dados físicos ou digitais no caixa da loja respeita os princípios fundamentais da lei.
Configuração do Prompt: 
"Atue como um consultor especializado em conformidade para o varejo. Analise a seguinte prática de coleta de dados no caixa de uma loja: [Descreva aqui a prática, ex: 'Solicitamos o CPF, e-mail e data de nascimento em troca de um cupom de 10% de desconto'].
Com base nos princípios da LGPD, avalie:
Finalidade e Adequação: O propósito da coleta é legítimo e informado claramente ao cliente?
.Necessidade (Minimização): Os dados solicitados são o mínimo necessário para essa finalidade ou há excesso?
.Transparência: Como a loja garante que o titular receba informações claras e acessíveis sobre quem é o Controlador e como os dados serão usados?
.Segurança: Quais medidas técnicas básicas devem proteger esses dados de acessos não autorizados no sistema de PDV?
.Sugira ajustes para que o processo seja menos arriscado juridicamente."

**Prompt 2: Simulação de Solicitação de Direitos do Titular**
Este prompt ajuda a treinar o Encarregado (DPO) ou a equipe de atendimento para lidar com as requisições dos clientes, conforme previsto no Art. 18 da lei.
Configuração do Prompt: "Simule um cenário onde um cliente (titular) entra em contato com uma PME varejista exercendo seus direitos sob o Art. 18 da LGPD. O cliente solicita:
Confirmação de existência de tratamento e acesso aos seus dados
.
Revogação do consentimento para comunicações de marketing
.
Eliminação de seus dados pessoais da base de clientes
.
Como o Encarregado (DPO) da empresa deve proceder para:
Fornecer uma resposta simplificada imediata ou uma declaração completa em até 15 dias?
.
Garantir que a eliminação ocorra sem custos para o titular?
.
Notificar eventuais Operadores (como sistemas de CRM ou contabilidade) para que também excluam os dados?
.
Redija um modelo de resposta padrão, profissional e transparente, que a loja possa utilizar para este atendimento."


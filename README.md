# 💸 App de Guia Financeiro com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

'''
# PRD — App Conversacional de Organização Financeira

## Visão Geral
Aplicativo de finanças pessoais baseado em conversas, permitindo registrar e acompanhar gastos e ganhos em linguagem natural, sem formulários ou planilhas.

## Problema
Aplicativos financeiros tradicionais exigem preenchimento manual e conhecimento prévio, o que gera confusão, erros frequentes e abandono por usuários iniciantes.

## Solução
Assistente financeiro conversacional que permite registrar despesas e receitas via chat, explicar gastos e oferecer recomendações simples.
A conversação e o NLP serão realizados pela IA Gemini 2.5 Flash.

## Público-Alvo
- Iniciantes em organização financeira  
- Jovens e adultos com renda fixa ou variável  
- Usuários que preferem interações simples  
- Pessoas que evitam planilhas e formulários  

## Objetivos
- Reduzir o esforço no controle financeiro  
- Facilitar a compreensão dos gastos  
- Incentivar hábitos financeiros saudáveis  
- Eliminar complexidade técnica  

## Princípios de Design
- Linguagem simples e educativa  
- Interface clara e intuitiva  
- Boa legibilidade  
- Nenhum conhecimento financeiro prévio exigido  

## Sincronização de Estado
O chat é o controlador do aplicativo.
Toda interação atualiza um estado financeiro central, refletido automaticamente em relatórios e metas.

## MVP

### Funcionalidades
- Chat conversacional  
- Metas financeiras simples  
- Relatórios visuais básicos  

### Recursos Técnicos
- Gemini 2.5 Flash (conversação e NLP)  
- Categorização automática de gastos  
- Recomendações financeiras básicas  

### Comandos via Chat
- Registrar gastos e ganhos  
- Editar ou excluir registros  
- Consultar saldo e relatórios  
- Reiniciar controle financeiro  
- Criar e acompanhar metas  

## Experiência Conversacional
O assistente responde de forma natural, educativa e contextualizada, confirmando ações e explicando impactos financeiros.

## Validação
- Testes com usuários iniciantes  
- Uso contínuo por pelo menos 7 dias  
- Coleta de feedback sobre clareza e facilidade de uso 
'''




Interações com o lovoble:

> Crie um app de finanças pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

> estou sentido falta do microfone no chat e está faltando também atualizar as metas

> a IA do app é meio temosa pois peço pra apagar algo como uma reserva e ela diz que apagou só que na verdade ela ainda não apagou acredito que por problemas tecnicos ela só apago se for tudo  e, quero que apague somente as  metas. Poderia analisar prf

Resultado final no lovable: https://cash-chat.lovable.app

<img width="1776" height="861" alt="image" src="https://github.com/user-attachments/assets/c852cfae-4dcf-4a17-8fb8-5c6ac7b900e2" />


Funcionalidades do App de Organização Financeira

# Assistente Financeiro

## Visão Geral
Aplicação de controle financeiro pessoal baseada em chat, permitindo registrar movimentações financeiras, acompanhar saldo, definir metas e visualizar relatórios de forma simples e centralizada.

## Funcionalidades

### Registro de Entradas
- Cadastro de receitas (ex.: salário).
- Atualização automática do saldo.
- Confirmação imediata no chat.

### Registro de Saídas
- Cadastro de despesas e gastos.
- Desconto automático no saldo.
- Controle básico de consumo.

### Reset Financeiro
- Zera saldo, transações, metas e reservas.
- Permite reiniciar o planejamento financeiro do zero.

### Chat Interativo
- Interface conversacional para ações financeiras.
- Respostas automáticas claras e objetivas.
- Simplifica o uso do sistema.

### Metas Financeiras
- Criação e acompanhamento de objetivos financeiros.
- Visualização do progresso das metas.

### Relatórios
- Histórico de entradas e saídas.
- Análise do comportamento financeiro ao longo do tempo.

### Navegação
- Menu inferior com acesso rápido a:
  - Chat
  - Metas
  - Relatórios
- Interface simples e intuitiva.

  
## Reflexão
  ### O que funcionou bem?
  o chat inicialmente apresentou alguns bugs mais depois ele funcionou bem
  
  ### O que não funcionou como o esperado?  
  As minhas metas pois, elas apresentaram algumas dificuldades na hora de passar e atulizar valores
  
  ### O que aprendeu sobre conversar com IAs?
  Que elas tem um padrão de funcionamento indefinido pois, variam conforme a configução de funcionamento criada 

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.

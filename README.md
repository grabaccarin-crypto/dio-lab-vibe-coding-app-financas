# 💸 App de de Finanças Pessoais

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

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);
- PRD refinado no Copilot
  
```txt  
# PRD – Aplicativo de Organização de Finanças Pessoais Conversacional

## 1. Objetivo do Produto
Facilitar o controle financeiro pessoal para iniciantes por meio de uma interface conversacional simples e intuitiva, eliminando a necessidade de planilhas complexas e entradas manuais extensas.

---

## 2. Problema a Resolver
- Usuários desistem de controlar gastos porque os apps atuais são burocráticos e pouco personalizados.
- Falta de orientação prática para quem está começando a organizar suas finanças.

---

## 3. Público-Alvo
- Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação.
- Principalmente iniciantes que nunca usaram apps financeiros ou desistiram por complexidade.

---

## 4. Escopo do MVP
### Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.
2. Classificação automática das transações por categoria.
3. Definição e acompanhamento de metas financeiras.
4. Dicas de economia fornecidas pelo “Agente Financeiro”.
5. Relatórios simples e personalizados (gráficos e insights).

---

## 5. Fluxo Principal
1. **Onboarding**
   - Pergunta inicial: “Qual seu objetivo financeiro principal?”
   - Opção para definir meta inicial (ex.: economizar R$500/mês).

2. **Tela de Conversa**
   - Usuário registra gastos com frases naturais: “Gastei R$50 no mercado.”
   - App responde: “Anotado! Categoria: Alimentação. Quer definir um limite para isso?”

3. **Tela de Metas**
   - Exibe metas definidas e progresso visual.

4. **Tela de Relatórios**
   - Gráficos simples (pizza ou barras) mostrando gastos por categoria.
   - Insights automáticos: “Você gastou 20% a mais em transporte este mês.”

---

## 6. Exemplos de Interações
### Onboarding
- **App:** “Olá! Bem-vindo ao seu assistente financeiro. Qual seu objetivo principal?”
- **Usuário:** “Quero economizar para uma viagem.”
- **App:** “Ótimo! Vamos começar definindo uma meta mensal. Quanto você gostaria de economizar?”

### Registro de Gastos
- **Usuário:** “Gastei R$80 no supermercado.”
- **App:** “Anotado! Categoria: Alimentação. Quer definir um limite para essa categoria?”

### Consulta de Saldo
- **Usuário:** “Quanto já gastei este mês?”
- **App:** “Você gastou R$1.200 até agora. Alimentação é sua maior categoria com R$500.”

### Definição de Meta
- **Usuário:** “Quero economizar R$300 este mês.”
- **App:** “Meta definida! Vou te avisar quando estiver perto de atingir.”

### Dicas de Economia
- **App:** “Percebi que seus gastos com transporte aumentaram 20% este mês. Que tal usar transporte público duas vezes por semana para economizar?”

---

## 7. Requisitos Funcionais
- NLP para interpretar mensagens (ex.: Dialogflow, Rasa ou LLM).
- Classificação automática baseada em palavras-chave e histórico.
- Banco de dados para armazenar gastos, metas e histórico (ex.: Firebase).
- Interface conversacional com botões rápidos para ações sugeridas.

---

## 8. Critérios de Aceitação
- Usuário consegue registrar um gasto em menos de 10 segundos via chat.
- Relatório mensal mostra pelo menos 3 categorias de gastos.
- Meta definida aparece com barra de progresso atualizada.

---

## 9. Validação Inicial
- Teste com 10-20 usuários reais.
- Perguntas-chave:
  - Foi fácil registrar gastos?
  - As dicas foram úteis?
  - Você se sentiu motivado a continuar usando?
- Métrica de sucesso: Usuário registra 5 transações na primeira semana.

---

## 10. Roadmap Futuro
- Integração com contas bancárias.
- Alertas inteligentes (ex.: “Você está perto do limite de alimentação”).
- Sugestões personalizadas baseadas em comportamento.

---

## 11. Tom e Linguagem
- Conversa educativa, amigável e sem jargões técnicos.
- Exemplo:
  - Usuário: “Gastei R$100 no restaurante.”
  - App: “Anotado! Isso entra na categoria Alimentação. Quer definir um limite para restaurantes este mês?”
 ```
Interações com o Lovable:

> tive apenas direito a uma interação: Utilizando o PRD anexo, crie um aplicativo para controle de finanças pessoais

> tentei uma segunda interação solicitando para criaçção de um botão oara vizualizar os registros diários, mas não foi possível

- Prints ou pequenos vídeos das interações com a IA;
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/4cd9ddbe-eac4-4789-a205-37f8ee034e9b" />

- Um resumo do que o seu **App de Finanças Pessoais** faz;
Descrição:
Aplicativo para organização de finanças pessoais com interface de conversa simples e intuitiva. Permite registrar gastos via chat, definir metas e visualizar relatórios sem burocracia.

Objetivo:
Facilitar o controle financeiro para iniciantes, eliminando planilhas complexas e oferecendo dicas personalizadas.

Principais Funcionalidades:
- Registro de gastos em linguagem natural.
- Classificação automática por categoria.
- Definição e acompanhamento de metas.
- Dicas de economia do Agente Financeiro.
- Relatórios simples com gráficos.

Instruções Iniciais:
1. Defina seu objetivo financeiro no onboarding.
2. Registre seus gastos via chat.
3. Acompanhe metas e relatórios.

Tecnologias sugeridas:
- NLP (Dialogflow, Rasa ou LLM).
- Banco de dados (Firebase ou similar).
- Interface conversacional.
  
- Uma breve **reflexão sobre o processo**:
 ### O que funcionou bem?
  - A facilidade na criação do aplicativo em si utilizando apenas linguagem natural   
 ### O que não funcionou como o esperado?
  - falta de atenção aos detalhes na descrição do produto e a limitação da ferramenta acabou gerando um produto sem alguma funcionalidades  
 ### O que aprendeu sobre conversar com IAs?
  - todo o processo do curso tem me ajudado a melhorar o meu desempenho na criação dos prompts para as minhas tarefas diárias no trabalho, a utilização frequente gera insights e mesmo com as limitações determinadas pela empresa tenho conseguido utilizar o Copilot para auxiliar nas minhas atividades.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.

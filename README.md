# 💸 App de Organização de Finanças Pessoais com Vibe Coding

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

- Seu **prompt final** (PRD):

```txt
  Crie um aplicativo web moderno de Finanças Pessoais com Inteligência Artificial chamado "FinanceAI". O app deve ser responsivo (mobile-first), com uma interface limpa, intuitiva e elegante (usando tema escuro/claro opcional, mas com visual estilo fintech moderna, tipo Nubank ou Revolut, usando cores como verde esmeralda e tons escuros).

O aplicativo deve conter as seguintes telas e funcionalidades interativas:

1. Dashboard Principal (Visão Geral):
- Cards no topo mostrando: Saldo Total, Receitas do Mês, Despesas do Mês e Economia/Investimentos.
- Gráfico interativo simulando a evolução mensal do saldo ou gastos por categoria.
- Atalhos rápidos para "Adicionar Transação" e "Falar com a IA".

2. Gestão de Transações:
- Uma lista de transações recentes (com ícones para categorias como Alimentação, Transporte, Lazer, Salário, Moradia).
- Um modal/formulário funcional para adicionar nova receita ou despesa (informando valor, descrição, data e categoria).

3. Assistente Financeiro com IA (Chat Inteligente):
- Uma aba ou modal dedicada onde o usuário pode conversar com uma IA simulada sobre suas finanças.
- A IA deve dar dicas de economia com base nos gastos fictícios da tela, responder perguntas como "Onde gastei mais este mês?" e sugerir metas de economia.

4. Metas Financeiras:
- Seção para visualizar metas de economia (ex: "Viagem de Férias", "Reserva de Emergência") com barras de progresso visuais e botão para adicionar fundos.

Requisitos técnicos e de UX:
- Utilize componentes modernos de UI (estilo Tailwind CSS / Shadcn UI).
- Navegação fluida entre as abas (Dashboard, Transações, Assistente IA, Metas).
- O app deve vir preenchido com dados mockados (exemplos realistas de gastos e receitas) para que a interface não nasça vazia e o usuário consiga interagir imediatamente.
```
- Prints ou pequenos vídeos das interações com a IA:
  <img width="1896" height="900" alt="image" src="https://github.com/user-attachments/assets/a4e86f30-459b-4830-9d5d-01876e236e44" />
 
- Um resumo do que o seu **App de Finanças Pessoais** faz:
  App focado em controle geral de finanças de uma pessoa, mostrando diversos dashboards para controle e otimização. Mais, auxílio de ia para manejo de dados e exibição.
  
- Uma breve **reflexão sobre o processo**:
**O que funcionou bem?**
Aceleração da Prototipagem Visual: A IA traduziu com precisão as diretrizes de UX/UI solicitadas no PRD. A combinação de tema escuro com verde-esmeralda, aliada aos componentes de estilo moderno (Tailwind/Shadcn), gerou uma interface com aspecto profissional de fintech já no primeiro ciclo.

Preenchimento Inicial com Dados Mockados: Solicitar dados fictícios realistas logo no prompt de inicialização evitou o problema da "tela em branco", permitindo validar imediatamente a legibilidade dos gráficos, o comportamento dos cards de métricas e a disposição da lista de transações.

Layout Responsivo (Mobile-First): A estrutura de navegação entre as abas e o comportamento fluido dos modais funcionaram de forma consistente tanto em telas menores quanto no desktop, dispensando ajustes manuais exaustivos de CSS.

**O que não funcionou como o esperado?**
Sincronização de Estado Reativo: Ao cadastrar uma nova despesa ou adicionar fundos a uma meta via modal, a atualização automática e dinâmica dos cards de Saldo Total exigiu refinamento. A IA inicialmente tratava alguns componentes de forma isolada, demandando prompts de ajuste para conectar o estado global da aplicação.

Profundidade das Respostas do Chat: Como o assistente simulado operava sem um backend integrado diretamente à API de uma LLM em tempo real, as primeiras interações geravam respostas genéricas. Foi necessário iterar comandos para que a simulação lesse o array de dados mockados e respondesse com números específicos dos gastos exibidos na tela.

**O que aprendi sobre conversar com IAs?**
Especificidade é mais eficiente que adjetivos: Em vez de pedir apenas um "app bonito e moderno", definir parâmetros técnicos concretos (estilo de componentes, paleta de cores esmeralda/dark, mobile-first e divisões de tela) reduz ruídos e elimina retrabalho de design.

O papel do desenvolvedor evoluiu para Product Manager/Tech Lead: No modelo de Vibe Coding, o foco principal deixa de ser a digitação manual de código repetitivo (boilerplate) e passa a ser a clareza na especificação funcional (PRD), a decomposição de problemas em etapas lógicas e a validação crítica do que foi gerado.

Iteração incremental supera prompts gigantescos: É mais seguro e previsível gerar a estrutura base do layout com dados estáticos primeiro e, em seguida, conduzir a IA através de instruções pontuais para refinar interatividades, cálculos e comportamentos de formulários.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.

# 💸 App de Organize suas Finanças por Aline Rodrigues com Vibe Coding

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
 PRD Refinado no Copilot web
 '''markdown
 # PRD – Aplicativo de Organização de Finanças Pessoais Conversacional

## Contexto
O aplicativo tem como objetivo simplificar o controle financeiro por meio de interações em linguagem natural.  
Em vez de formulários complexos ou planilhas, o usuário conversa com o app para registrar gastos, definir metas e receber recomendações personalizadas.

## Problema
- Alta fricção: apps atuais exigem muita entrada manual.  
- Baixa personalização: relatórios e dicas pouco adaptados ao perfil do usuário.  
- Desmotivação: iniciantes abandonam o controle financeiro por achar difícil ou burocrático.

## Público-Alvo
- Pessoas que nunca usaram ou desistiram de apps de finanças.  
- Usuários que buscam simplicidade e orientação prática.  
- Faixa inicial: jovens adultos e trabalhadores que querem começar a organizar seus gastos sem complicação.

## Funcionalidades-Chave
1. Registrar gastos via chat  
   - Exemplo: “Gastei R$ 50 no supermercado hoje.”  
   - O app interpreta valor, categoria e data automaticamente.  

2. Classificação automática de transações  
   - Inteligência para identificar categorias (alimentação, transporte, lazer).  
   - Possibilidade de corrigir via conversa.  

3. Metas financeiras  
   - Definição de objetivos simples: “Quero economizar R$ 200 este mês.”  
   - Acompanhamento com alertas e progresso visual.  

4. Agente Financeiro (IA)  
   - Recomendações de economia personalizadas.  
   - Mensagens educativas e motivacionais.  

5. Relatórios simples e personalizados  
   - Gráficos básicos (gastos por categoria, evolução mensal).  
   - Resumo em linguagem natural: “Você gastou 20% a mais em restaurantes este mês.”

## MVP – Plano de Entrega

### Principais Telas
- Tela de Conversa: interface central para registrar gastos e interagir com o agente.  
- Tela de Metas: definição e acompanhamento de objetivos.  
- Tela de Relatórios: visão geral dos gastos e insights.  
- Tela de Configurações: categorias, preferências e perfil do usuário.

### Recursos Necessários
- Processamento de linguagem natural (NLP) para interpretar mensagens.  
- Banco de dados simples para armazenar transações e metas.  
- Motor de categorização automática com possibilidade de correção.  
- Módulo de relatórios com gráficos básicos.  
- Agente Financeiro (IA) para dicas e recomendações.

## Validação Inicial
- Teste com grupo piloto de 10–20 usuários iniciantes.  
- Métricas principais:  
  - Facilidade de uso (tempo para registrar gasto).  
  - Engajamento (quantidade de interações semanais).  
  - Retenção (uso contínuo após 2 semanas).  
- Feedback qualitativo: entrevistas rápidas sobre clareza das dicas e relatórios.

## Tom e Linguagem
- Educativo, acessível e amigável.  
- Evitar jargões financeiros complexos.  
- Usar exemplos práticos e comparações simples.
  '''
  Interações com o Lovable:
  - crie um app de finanças pessoais com base no seguinte PRD (Documento de Requisitos de Produto # PRD – Aplicativo de Organização de Finanças Pessoais Conversacional
  - Eu gastei 20 reais na sorveteria
    Resultado Final no Lovable : https://id-preview--e2b5dd16-ae59-4fc2-9d85-9e695ec88b86.lovable.app/
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bf268086-5910-4eaa-96c6-50be02dc6234" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c9a20ecb-60c2-42af-a063-e4fcd1f5fe0c" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f32a6e82-94bf-47ce-abcb-95f130888ac5" />

Resumo sobre o APP:
-Assistente Financeiro Pessoal
Este é um aplicativo web interativo desenvolvido para ajudar usuários a gerenciar suas finanças de forma simples, intuitiva e eficiente. Com uma interface amigável e totalmente em português, o assistente oferece funcionalidades essenciais para o controle financeiro pessoal:

-Funcionalidades
Registro de gastos: Informe suas despesas diretamente no chat com linguagem natural.

Resumo do mês: Visualize seus gastos mensais com gráficos e comparativos.

Dicas de economia: Receba sugestões personalizadas para poupar dinheiro.

Metas financeiras: Crie e acompanhe objetivos como fundo de emergência ou viagem.

Relatórios detalhados: Veja a evolução dos seus gastos por categoria e por mês.

- Interface
Navegação por abas: Chat, Metas, Relatórios e Ajustes.

Visualizações gráficas: Barras de progresso, gráficos de pizza e linha para análise de desempenho.

Assistente ativo: Responde em tempo real e orienta o usuário com exemplos práticos.
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
    A ajuda do Copilot para refinar o prompet, para ser mais agil e acertivo.
  - O que não funcionou como o esperado?
    Houve um erro na hora da criação do app no Lovable , mas pedi pra ele corrigir e no fim deu certo, e achei o chat com respostas bem genéricas.
    
  - O que aprendeu sobre conversar com IAs?
 Aprendi que para uma melhor comunicação e resultado devo ser bem clara e detalhada sobre o que eu quero para a IA entregar o seu melhor e evitar erros e alucinações.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.

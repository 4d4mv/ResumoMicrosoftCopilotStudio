
## Copilots e GenAI no Microsoft 365
Aqui vai um resumo de como criar e personalizar Copilots no Microsoft Copilot Studio, incluindo ajustes na qualidade das respostas com Generative AI (GenAI) para a atividade da DIO. Este README sintetiza os principais conceitos vistos nos módulos para construir assistentes de IA no Microsoft 365, com exemplos práticos e criatividade.

### 📋 Índice

1. Criar um Copilot em branco
2. Customizar um tópico
3. Personalizar uma mensagem de erro de tópico
4. Aumentar e diminuir a qualidade da resposta com GenAI
5. Conclusão

## 🚀 Criar um Copilot em branco
Criar um Copilot do zero no Copilot Studio é como montar um robô de Lego, peça por peça, com total liberdade para definir cada interação. Esse método é ideal para projetos que exigem personalização completa.

### Passos

- Acesse o Copilot Studio: No Microsoft 365 (requer licença, como Business Premium), vá ao Copilot Studio e selecione “Criar um novo Copilot” > “Em branco”.
- Defina fluxos de conversa: Crie gatilhos (frases do usuário) e respostas correspondentes.
- Integre dados e IA: Conecte a fontes como SharePoint ou adicione modelos de linguagem natural.
- Teste e publique: Valide os fluxos e publique em canais como Microsoft Teams.

### Exemplo

- Objetivo: Criar um Copilot que informa o horário de uma loja.
- Gatilho: “Qual é o horário da loja?”
- Resposta: “Aberto de segunda a sexta, 9h-18h, e sábado, 10h-14h!”
- Fluxo adicional: Se o usuário perguntar “E no domingo?”, o Copilot responde: “Fechamos aos domingos, mas compre online 24/7!”
- Como fazer: No Copilot Studio, adicione o gatilho e mapeie as respostas com ramificações.

### Benefício
Permite assistentes sob medida, como bots para processos internos específicos.

## 🛠️ Customizar um tópico
Um tópico é um fluxo de conversa que responde a uma intenção específica do usuário. Customizá-lo é como ensinar truques a um papagaio, definindo o que ele “ouve” e “fala” para atender às suas necessidades.

### Passos

- Acesse tópicos: No Copilot Studio, vá à seção Tópicos e selecione ou crie um novo.
- Edite gatilhos: Adicione frases que iniciam o tópico (ex.: “rastrear pedido”).
- Configure fluxos: Defina perguntas, respostas ou ações, como buscar dados em bases externas.
- Adicione lógica: Use condições (ex.: “se cliente, mostre X”) para respostas contextuais.
- Teste: Simule interações para garantir precisão.

### Exemplo

- Objetivo: Tópico para rastrear pedidos.
- Gatilho: “Onde está meu pedido?” ou “Rastrear minha compra”.
- Fluxo:
    - Copilot pergunta: “Qual é o número do pedido?”
    - Usuário responde: “12345”.
    - Copilot: “Seu pedido #12345 chegará em 2 dias!” (busca em SharePoint).


- Como fazer: Configure gatilhos e conecte a uma base de dados no Copilot Studio.

### Benefício
Ideal para criar respostas personalizadas, como suporte ao cliente ou automação.

## ⚠️ Personalizar uma mensagem de erro de tópico
Quando o Copilot não entende o usuário, ele exibe uma mensagem de erro padrão. Personalizá-la é como dar um tom humano ao seu assistente, mantendo o usuário engajado mesmo em falhas.

### Passos

- Acesse configurações: No Copilot Studio, vá a Configurações > Mensagens de erro ou edite o Tópico de fallback.
- Edite a mensagem: Substitua o padrão por algo amigável e alinhado ao seu tom.
- Adicione ações: Inclua sugestões ou redirecionamentos (ex.: para um atendente humano).
- Teste: Verifique com entradas inválidas.

### Exemplo

- Objetivo: Mensagem de erro para um Copilot de suporte técnico.
- Mensagem padrão: “Desculpe, não entendi.”
- Mensagem personalizada: “Ops, me perdi! 😅 Tente dizer ‘problema com impressora’ ou ‘falar com alguém’.”
- Ação: Oferece botões como “Ver FAQs” ou “Contato humano”.
- Como fazer: Edite o tópico de fallback e adicione botões interativos.

### Benefício
Torna erros mais amigáveis, mantendo o usuário no fluxo da conversa.

## 🌟 Aumentar e diminuir a qualidade da resposta com GenAI
Ajustar a qualidade das respostas com Generative AI (GenAI) é como girar o botão de um liquidificador de IA – mais potência para respostas ricas, menos para respostas simples. O Copilot Studio usa modelos de linguagem avançados para isso.

### Passos

- Aumentar qualidade:
    - Use prompts detalhados (ex.: “Explique com exemplos”).
    - Conecte a bases ricas (SharePoint, Dynamics 365).
    - Ative GenAI avançada para respostas contextuais.


- Diminuir qualidade:
    - Simplifique prompts (ex.: “Responda em uma frase”).
    - Limite dados externos.
    - Desative GenAI para respostas fixas.


- Teste e ajuste: Monitore respostas no Copilot Studio.

### Exemplo

- Objetivo: Ajustar respostas sobre políticas de férias.
- Aumentar qualidade:
    - Prompt: “Explique a política de férias com detalhes e exemplos.”
    - Resposta: “Você tem 30 dias anuais. Ex.: com 2 anos de empresa, tire 15 dias consecutivos. Solicite no portal de RH; aprovação em 48h.”
    - Como fazer: Conecte a SharePoint e ative GenAI.


- Diminuir qualidade:
    - Prompt: “Responda se há férias.”
    - Resposta: “Sim, 30 dias por ano.”
    - Como fazer: Desative GenAI e use resposta fixa.

### Benefício
Adapte respostas para suporte complexo (alta qualidade) ou interações rápidas (baixa qualidade).

## 🎯 Conclusão
Este guia explora como criar e personalizar Copilots no Microsoft 365, transformando-os em aliados versáteis:

- Copilot em branco: Construa assistentes do zero, como um bot de horários de loja.
- Customizar tópicos: Adapte fluxos, como rastreamento de pedidos.
- Mensagens de erro: Torne erros amigáveis com sugestões úteis.
- GenAI: Ajuste respostas entre detalhadas e simples, conforme a necessidade.

Com o Copilot Studio, você tem um canivete suíço de IA, pronto para automatizar e personalizar tarefas no Microsoft 365. Explore, teste e crie seus próprios assistentes!



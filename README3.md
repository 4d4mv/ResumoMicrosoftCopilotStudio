## Projeto de Prática: Explorando Azure Speech Studio e Language Studio
### Olá, Mundo! 👋
Bem-vindo ao meu repositório de prática com as ferramentas Azure Speech Studio e Language Studio da Microsoft Azure! Este projeto nasceu de um desafio para me aprofundar no mundo da inteligência artificial (IA) voltada para voz e linguagem natural. Meu objetivo aqui foi aprender na prática, testar funcionalidades e anotar tudo o que descobri, criando um material que possa me ajudar (e quem sabe a você também!) em estudos futuros ou projetos mais complexos. Vamos explorar juntos o que eu fiz e como cheguei lá!

### Sobre o Projeto
Este repositório documenta minha jornada ao usar o Azure Speech Studio (para trabalhar com fala) e o Language Studio (para análise de linguagem natural). O foco foi desenvolver habilidades práticas, como criar soluções simples de IA. Eu montei um exemplo básico: um sistema que transcreve áudio, analisa o sentimento do texto e extrai frases-chave. Tudo isso foi feito como um iniciante, então sinta-se à vontade para acompanhar meu processo passo a passo!

### Ferramentas Utilizadas
- Azure Speech Studio: Para transcrever áudio em texto e gerar fala.
- Language Studio: Para analisar sentimento e extrair frases-chave de textos.
- Azure Portal: Para configurar os serviços e gerenciar recursos.
- Um microfone e um texto simples: Meu setup básico para gravar e testar!

### Passo a Passo do Projeto
#### 1. Configurando o Ambiente no Azure

- Criação de Recursos: No Azure Portal, criei um recurso de "Speech Service" e outro de "Language Service". Usei uma assinatura gratuita para testar (ótima para iniciantes!).
- Obtenção de Chaves e Endpoints: Peguei a chave de API e o endpoint de cada serviço nas configurações. Isso foi essencial para conectar as ferramentas aos meus testes.

#### 2. Usando o Azure Speech Studio

- Transcrição de Áudio: Gravei um áudio simples dizendo: "Estou feliz por aprender IA hoje!" no meu microfone. No Speech Studio, usei a funcionalidade de Speech-to-Text para transcrever isso em texto. Resultado: "Estou feliz por aprender IA hoje!" (funcionou direitinho na primeira tentativa!).
- Geração de Fala: Testei o Text-to-Speech inserindo o texto transcrito. Escolhi uma voz em português (ex.: "Fernanda") e gerei um áudio que repetiu minha frase.

#### 3. Usando o Language Studio

- Análise de Sentimento: Copiei o texto transcrito ("Estou feliz por aprender IA hoje!") e usei o recurso de Análise de Sentimento no Language Studio. O resultado foi "Sentimento: Positivo" com uma pontuação alta (algo como 0.95), o que fez sentido com minha alegria ao aprender!
- Extração de Frases-Chave: No mesmo texto, usei Extração de Frases-Chave e obtive: ["feliz", "aprender", "IA"]. Isso me mostrou os tópicos principais da frase, uma ferramenta super útil para entender o foco de uma conversa.

### Insights e Aprendizados

- Facilidade de Uso: Ambas as ferramentas têm interfaces intuitivas, perfeitas para quem está começando como eu.
- Limitações: O reconhecimento de fala pode falhar com áudios muito ruidosos, e a análise de sentimento funciona melhor com textos mais longos.
- Próximos Passos: Quero integrar isso a um bot no Copilot Studio e testar com conversas reais.

### Agradecimentos
Agradeço à comunidade Azure, aos tutoriais da Microsoft e à tutora Valéria Baptista, da DIO por me guiar nessa jornada. Se você tem dicas ou quer colaborar, é só abrir uma issue ou me chamar!
Até mais ✌

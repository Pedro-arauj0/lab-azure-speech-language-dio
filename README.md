# Laboratório – Azure Speech Studio e Language Studio

Repositório criado para o desafio da DIO, com o objetivo de praticar os serviços de Fala e Linguagem do Azure, realizando transcrição de áudio e análise de sentimentos em textos.

## Objetivo

- Explorar o Azure Speech Studio para converter fala em texto.
- Utilizar o Azure Language Studio para analisar sentimentos e opiniões em textos em português.
- Documentar o processo e os resultados em um repositório público no GitHub.

## Pré-requisitos

- Conta Microsoft com acesso ao portal do Azure.
- Recurso do tipo Azure AI Speech criado no portal do Azure.
- Recurso do tipo Azure AI Language (Language Service) criado no portal do Azure.
- Conta no GitHub para versionar e compartilhar este repositório.

## Atividades realizadas

### 1. Transcrição de áudio com Speech Studio

1. Acessei o portal do Azure e criei um recurso de Speech.
2. Abri o Speech Studio e selecionei o recurso criado.
3. Utilizei a funcionalidade de fala para texto (speech to text) enviando um arquivo de áudio/voz de teste.
4. Avaliei o texto transcrito, observando acertos e possíveis erros de reconhecimento.

### 2. Análise de sentimentos com Language Studio

1. Acessei o portal do Azure e criei um recurso de Language Service.
2. Abri o Language Studio e selecionei o recurso criado.
3. Na seção “Sentiment and opinion mining”, inseri três textos em português representando cenários positivo, negativo e neutro.
4. Executei a análise e observei o sentimento geral e as pontuações retornadas para cada frase.

Textos utilizados nos testes:

- Texto positivo:  
  “Estou muito satisfeito com o atendimento, fui respondido rapidamente e o produto superou minhas expectativas.”

- Texto negativo:  
  “Fiquei decepcionado com o serviço, o suporte demorou e o problema não foi resolvido.”

- Texto neutro:  
  “O pacote foi entregue ontem às 15h, conforme o prazo informado no site.”

## Resultados e aprendizados

- O serviço de Speech conseguiu transcrever o áudio de forma satisfatória, mostrando na prática como funciona a conversão de fala em texto.
- A análise de sentimentos do Language Studio identificou corretamente a intenção de cada frase: positiva, negativa e neutra, com pontuações coerentes com o contexto.
- A experiência ajudou a entender como os serviços de Fala e Linguagem do Azure podem ser usados em aplicações reais, como atendimento ao cliente, análise de feedbacks e automação de processos.

## Tecnologias utilizadas

- Microsoft Azure
  - Azure Speech Studio
  - Azure Language Studio (Language Service)
- Git e GitHub
- [Opcional] C#/.NET para integração futura com os serviços de IA

## Como repetir os testes (resumo)

1. Criar ou reutilizar recursos de Speech e Language no portal do Azure.
2. Acessar o Speech Studio para testar a transcrição de áudio.
3. Acessar o Language Studio, abrir “Sentiment and opinion mining”, colar textos em português e executar a análise de sentimentos.

---

Projeto desenvolvido como parte do desafio de IA com Azure na DIO.

# Laboratório – Azure Speech Studio e Language Studio

Repositório criado para o desafio da DIO, com o objetivo de praticar os serviços de Fala e Linguagem do Azure, realizando transcrição de áudio e análise de sentimentos em textos.

## Objetivo

- Explorar o Azure Speech Studio para converter fala em texto.
- Utilizar o Azure Language Studio para analisar sentimentos e opiniões em textos em português.
- Documentar o processo, resultados e aprendizados em um repositório público no GitHub.

## Pré-requisitos

- Conta Microsoft com acesso ao portal do Azure.
- Recurso do tipo Azure AI Speech criado no portal do Azure.
- Recurso do tipo Azure AI Language (Language Service) criado no portal do Azure.
- Conta no GitHub para versionar e compartilhar este repositório.

## Atividades realizadas

### 1. Transcrição de áudio com Azure Speech Studio

1. Acessei o portal do Azure, criei um recurso de Speech e associei ao meu usuário.
2. Abri o Speech Studio no navegador e selecionei o recurso criado.
3. Usei a funcionalidade de conversão de fala em texto (speech to text), gravando/enviando um áudio de teste em português.
4. Após executar o teste, o serviço transcreveu automaticamente o conteúdo falado para texto, permitindo avaliar a qualidade do reconhecimento.

### 2. Análise de sentimentos com Azure Language Studio

1. Acessei o portal do Azure, criei um recurso de Language Service e o vinculei ao Language Studio.
2. No Language Studio, utilizei a funcionalidade “Sentiment and opinion mining” para analisar textos em português.
3. Para os testes, utilizei três frases representando sentimentos diferentes:

   - Texto positivo:  
     “Estou muito satisfeito com o atendimento, fui respondido rapidamente e o produto superou minhas expectativas.”

   - Texto negativo:  
     “Fiquei decepcionado com o serviço, o suporte demorou e o problema não foi resolvido.”

   - Texto neutro:  
     “O pacote foi entregue ontem às 15h, conforme o prazo informado no site.”

4. Executei a análise e observei o sentimento geral atribuído a cada frase (positivo, negativo ou neutro), além das pontuações de confiança retornadas pelo serviço.

## Resultados obtidos

### Resultados com o Azure Speech

Durante os testes de transcrição, o serviço de fala do Azure conseguiu transformar o áudio em texto com boa qualidade geral.  
Foram percebidos alguns pequenos erros na escrita, como trocas sutis de palavras ou detalhes de ortografia, mas nada que comprometesse o entendimento da mensagem.  
De forma geral, a experiência mostrou que o áudio é bem reconhecido e que o serviço atende ao objetivo do laboratório de demonstrar a conversão de fala em texto.

### Resultados com o Azure Language

Na análise de sentimentos, o Language Studio identificou corretamente a intenção das frases usadas nos testes:

- A frase positiva foi classificada como sentimento positivo, refletindo a satisfação com atendimento e produto.
- A frase negativa foi reconhecida como sentimento negativo, destacando a demora do suporte e o problema não resolvido.
- A frase neutra foi avaliada como neutra, por trazer apenas uma informação objetiva sobre entrega e horário.

Esses resultados mostram como o serviço consegue distinguir diferentes tipos de sentimentos em textos simples em português.

## Aprendizados

- O Azure Speech Studio facilita testar o reconhecimento de fala diretamente no navegador, permitindo validar rapidamente a qualidade da transcrição.
- O Azure Language Studio oferece uma interface intuitiva para análise de sentimentos, tornando simples testar frases positivas, negativas e neutras.
- A combinação desses dois serviços ajuda a construir soluções que integram voz e texto, úteis em cenários como atendimento ao cliente, análise de feedbacks e automação de processos.

## Tecnologias utilizadas

- Microsoft Azure
  - Azure Speech Studio (Speech Service)
  - Azure Language Studio (Language Service)
- Git e GitHub
- (Opcional) C#/.NET para futuras integrações com os serviços de IA

## Como reproduzir os testes

1. Criar recursos de Speech e Language no portal do Azure.
2. Acessar o Speech Studio, selecionar o recurso de Speech e realizar um teste de fala para texto com áudio em português.
3. Acessar o Language Studio, selecionar o recurso de Language e usar a funcionalidade “Sentiment and opinion mining” com textos positivos, negativos e neutros.
4. Registrar os resultados obtidos (prints, observações e análises) neste repositório.

---

Projeto desenvolvido como parte do desafio de projeto sobre ferramentas de Fala e Linguagem do Azure na DIO.

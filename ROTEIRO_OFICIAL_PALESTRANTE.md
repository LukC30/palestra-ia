# 🎙️ ROTEIRO OFICIAL DO PALESTRANTE: O CUSTO OCULTO DA IA
**Palestrante:** Lucas (LukC30)  
**Tema:** O Custo Oculto da IA: A Ilusão do Código Rápido e a Realidade da Engenharia  
**Público:** Ensino Médio / Técnico em Informática e Desenvolvimento  
**Duração:** 90 minutos (~70 min de fala + 20 min de debate/Q&A)  
**Estilo:** Pragmático, disruptivo, articulado, técnico e direto ao ponto.

---

## ⏱️ Mapa do Tempo
* **00:00 - 00:15** | Slides 01 a 04 | Boas-vindas, Trajetória, Burnout/TCC e o Canto da Sereia
* **00:15 - 00:35** | Slides 05 a 09 | A Ciência (Harvard/GitClear), O Quiz e a Hipocrisia dos Datacenters
* **00:35 - 00:55** | Slides 10 a 16 | O Impacto no Estudante, O Jogo das Palavras, Arquitetura e o Bug do Pix
* **00:55 - 01:10** | Slides 17 a 21 | Vibe Coding vs Engenharia, Segurança (Air Canada), Mercado e Livros
* **01:10 - 01:15** | Slides 22 a 24 | O que o Mercado Cobra, Conclusão (O Manifesto) e Contatos/QR Code
* **01:15 - 01:30** | Q&A e Debate Aberto

---

## 📜 Slide a Slide: O que Falar

### SLIDE 01 — Capa
* **Abertura:** *"Fala pessoal, tudo bem? Antes de começar, um alinhamento: eu não vim aqui hoje dar palestrinha corporativa cheia de jargão de LinkedIn, nem vim falar mal de IA feito velho reclamando de tecnologia. Eu uso IA todo dia. O que eu vim mostrar aqui hoje é o que acontece nos bastidores das grandes empresas de tecnologia quando a empolgação do prompt acaba e o sistema precisa parar em pé sem quebrar no mundo real."*

### SLIDE 02 — Minha Trajetória & Trincheiras
* **O que falar:** *(Aponte para as fotos)* *"Eu estive sentado nessa mesma cadeira onde vocês estão hoje. Tive as mesmas dúvidas, quebrei a cabeça com o primeiro 'Hello World', passei noites em grupo debugando código pra entregar projeto e senti o frio na barriga de colocar um sistema em produção pela primeira vez. Tudo o que vou falar hoje não veio de teoria de livro; veio da prática lidando com código de verdade."*

### SLIDE 03 — O Lado Oculto da TI: Burnout & Meu TCC
* **A Interação (Enquete):** *"Vou fazer um teste rápido de honestidade aqui: quem na sala já passou da meia-noite travado num código, com a cabeça fervendo e achando que computação não era pra você? Levantem a mão."* *(Espere levantarem).*
* **A fala:** *"Pois é. A internet vende que trabalhar com TI é só glamour, salário em dólar e cadeira gamer. Ninguém te avisa que essa é uma das indústrias com maior índice de ansiedade e esgotamento mental do planeta. Eu vivi isso tão de perto que o meu TCC foi literalmente um jogo sobre burnout. E quando a IA explodiu, prometeram que ela traria alívio. Na prática, gerou mais cobrança: gerentes exigindo entregas 3x mais rápidas e o medo constante de ficar obsoleto. Hoje vamos entender por que esse pânico não faz sentido se você dominar o que realmente importa."*

### SLIDE 04 — A Ilusão da "Programação em Inglês"
* **O que falar:** *(Mostre o tweet do Sam Altman)* *"Essa é a narrativa que domina as redes sociais. O Sam Altman da OpenAI e o Andrej Karpathy da Tesla tuitando que 'a programação tradicional morreu' e que 'o inglês é a nova linguagem mais quente'. Eles vendem a ilusão de que basta bater papo com a IA como se fosse um amigo de trampo e o software nasce pronto. Agora vamos ver o que a ciência e os dados dizem sobre essa promessa."*

### SLIDE 05 — O Estudo de Harvard: 445 Milhões de Eventos
* **O que falar:** *"Em 2026, pesquisadores de Harvard — Fiona Chen e James Stratton — publicaram um paper analisando 720 mil engenheiros de software em 655 empresas reais através da plataforma Jellyfish. Monitoraram tudo: GitHub, Jira e calendário. Sabe o que descobriram? A IA aumentou em 44% a quantidade de linhas de código digitadas. Mas o impacto na entrega final de software em produção foi praticamente NULO. Gerar código rápido não acelerou a entrega de software. A torneira abriu, mas o ralo entupiu."*

### SLIDE 06 — Onde a Conta Chega: +56% de Espera no Code Review
* **O que falar:** *"O paper de Harvard provou onde o gargalo foi parar: na revisão de código. O tempo que o código de IA fica mofando na fila de espera antes de um dev conseguir ler subiu quase 60%. Os pedidos de correção subiram 38%. Por quê? Porque se um júnior leva 2 minutos pra gerar 500 linhas de código no ChatGPT e abrir um Pull Request, o sênior leva 3 horas pra ler linha por linha pra ter certeza de que aquilo não vai derrubar o banco de dados da empresa."*

### SLIDE 07 — Código Descartável: O Efeito Churn (GitClear)
* **O que falar:** *"Outro estudo gigante, da GitClear, analisou 200 milhões de linhas de código. O código descartado ou reescrito em até duas semanas — o chamado Code Churn — praticamente DOBROU. A IA tem preguiça de entender a arquitetura do projeto. Em vez de reaproveitar funções existentes, ela cospe blocos duplicados. Gerar código em 10 segundos pra ter que deletar tudo semana que vem não é produtividade; é retrabalho automatizado."*

### SLIDE 08 — Quiz: Quanto Tempo um Dev Passa Digitando Código?
* **A Interação:** *"Pergunta rápida pra vocês chutarem: num dia de trabalho de 8 horas, quanto tempo um desenvolvedor profissional gasta digitando código no teclado? Opção A: 80%? Opção B: 50%? Opção C: 15% a 20%? Ou Opção D: 5%? Quem acha que é A levanta a mão... quem acha que é B... quem acha que é C..."*
* **A Revelação (Aperte R):** *"A resposta certa é a C: apenas 15% a 20%! O resto do dia do programador é: entender a regra de negócio do cliente, ler código dos outros, debugar, alinhar arquitetura e criar testes. A IA só acelera a digitação (os 15%). Os outros 85% dependem exclusivamente da capacidade analítica do engenheiro."*

### SLIDE 09 — A Hipocrisia dos Datacenters (A Polêmica da RAM)
* **O que falar:** *"Recentemente, o Sam Altman deu uma entrevista num podcast dizendo que é 'péssimo' que as pessoas tenham muita memória RAM nos seus computadores em casa sendo usada 'só 5% do tempo', e que tudo deveria estar centralizado nos datacenters dele na nuvem. A ironia? Enquanto dizem que o seu hardware local é desperdício, os datacenters de IA estão drenando a rede elétrica e a água de cidades inteiras pra sustentar código redundante e descartável na nuvem, cobrando assinaturas caras pra te manter dependente."*

### SLIDE 10 — "E Como Isso Afeta Vocês?"
* **A Interação:** *"Pergunta rápida: quem aqui já pegou a lista de exercícios da escola, jogou o enunciado no ChatGPT, colou a resposta no VS Code e torceu pra rodar sem erro? Mão pra cima!"*
* **A fala:** *"A sensação é maravilhosa na hora. Mas tem uma pegadinha: você não resolveu o problema, você só pegou o gabarito pronto. O mercado não vai te contratar pra apertar 'Enter' num prompt que o seu chefe também sabe apertar. O mercado contrata quem sabe identificar quando o código gerado tá com falha."*

### SLIDE 11 — Terceirização do Cérebro & Deep Scrolling
* **O que falar:** *"Aprender a programar não é decorar comando; é treinar o cérebro pra sustentar raciocínio lógico sob pressão. O maior inimigo de vocês hoje não é a IA; é o deep scrolling do TikTok e do Instagram. A gente se acostuma com dopamina barata de 15 segundos e respostas em 3 segundos da IA. Quando você pega um bug real que exige 2 horas de silêncio lendo documentação, a cabeça ferve e você quer desistir. Quem aprende a sustentar foco profundo hoje se torna um profissional raro e disputado no mercado."*

### SLIDE 12 — Jogo Rápido: O Desafio das Palavras
* **A Interação:** *"Olhem pra tela agora. Tem 8 conceitos aí. Quem aqui sabe o que significa pelo menos duas dessas palavras? Levantem a mão!"*
* **A fala:** *(Brinque com alguém)* *"Você aí, chuta uma: o que você acha que é IDEMPOTÊNCIA? Parece nome de remédio pra dor de barriga, né? Pois é. Essas palavras governam a infraestrutura de empresas do tamanho do Nubank, Instagram e iFood. Vamos ver o que elas significam de forma simples."*

### SLIDE 13 — 1. Estruturas de Dados: Filas vs Pilhas
* **O que falar:**
  * **Fila (FIFO):** *"Primeiro que chega é o primeiro atendido, igual à fila da cantina da escola. Quando 50 mil pessoas tentam comprar ingresso de show no mesmo segundo na Ticketmaster, o servidor não processa tudo junto senão explode; ele enfileira pra salvar o banco de dados."*
  * **Pilha (LIFO):** *"Último que entra é o primeiro a sair, igual pilha de pratos na pia. O botão 'Desfazer' (Ctrl+Z) do VS Code e a pilha de memória do seu computador rodam exatamente assim."*

### SLIDE 14 — 2. A Física do Sistema: Concorrência vs Paralelismo
* **O que falar:**
  * **Concorrência:** *"Um cozinheiro cuidando de três panelas ao mesmo tempo. Ele não tem três braços; ele intercala a atenção entre as panelas. É o Node.js atendendo centenas de usuários pelo Event Loop."*
  * **Paralelismo:** *"Três cozinheiros, cada um no seu próprio fogão, cozinhando juntos. É um processador multi-core com vários núcleos reais trabalhando no mesmo nanossegundo."*
  * **Race Condition:** *"Se você e outra pessoa tentarem sacar R$ 100 ao mesmo tempo de uma conta que só tem R$ 100, o que acontece? A IA não resolve isso no chat; quem resolve é o engenheiro com travas e transações atômicas!"*

### SLIDE 15 — 3. Estabilidade Real: Idempotência & Observabilidade
* **O que falar:**
  * **Idempotência:** *"Apertar o botão do elevador uma vez ou dez vezes faz a mesma coisa. Se a internet oscilar na hora de pagar um Pix e você clicar três vezes, o sistema não pode te cobrar três vezes."*
  * **Observabilidade:** *"É o painel do avião mostrando pressão e combustível antes do motor falhar. Software não pode ser caixa preta; você tem que ter métricas e logs pra saber onde a requisição travou."*

### SLIDE 16 — Desafio Visual: Ache o Bug no Código Python da IA
* **A Interação:** *"Olhem pra esse código em Python na tela gerado por IA. A sintaxe tá perfeita, não dá erro vermelho no terminal. Mas tem um bug gravíssimo. Quem acha primeiro?"*
* **A Revelação:** *"A IA chama `enviar_pix` pelo Banco Central ANTES de atualizar o saldo no banco de dados! Se o servidor cair logo depois do envio, o dinheiro saiu da empresa, caiu na conta do amigo e a conta do remetente continuou cheia! Bug de dinheiro infinito. A IA não liga pro prejuízo da empresa; quem tem que auditar isso é você."*

### SLIDE 17 — Vibe Coding vs Engenharia: De Quem é a Culpa às 3h da Manhã?
* **O que falar:** *"Essa tabela resume tudo. No Vibe Coding você copia, cola e reza. Na Engenharia Real você desenha resiliência, isolamento de falhas e logs. E a frase principal: quando o banco de dados vazar dados ou o sistema financeiro cair, a empresa não vai processar a OpenAI. Quem assinou o commit responde tecnicamente e juridicamente."*

### SLIDE 18 — O Caso Real da Air Canada & O Risco de Segurança
* **O que falar:**
  * **Air Canada:** *"A companhia aérea botou um chatbot no ar. O bot inventou uma regra de desconto que não existia. A Justiça canadense condenou a empresa: ela é 100% responsável pelo que a IA fala no sistema dela."*
  * **Slopsquatting:** *"Cuidado ao rodar `pip install`. Às vezes a IA alucina nomes de bibliotecas que não existem. Hackers descobrem isso, criam pacotes com vírus reais usando esses nomes no PyPI e, se você der install sem conferir no GitHub oficial, você acabou de infectar a máquina da empresa."*

### SLIDE 19 — O Efeito Alavanca: O Dev de 10x Existe?
* **O que falar:** *"O mercado não vai acabar com os salários; ele vai separar dois tipos de profissionais. O primeiro é o dependente de prompt, que copia código quebrado e compete por salário baixo. O segundo é o engenheiro que usa a IA como alavanca técnica: ele domina arquitetura, audita código e usa a IA pra acelerar o trabalho repetitivo. A IA não veio tirar seu trampo; quem vai disputar a vaga com você é o engenheiro que sabe pilotar a máquina."*

### SLIDE 20 — O que Ler pra Superar o Hype
* **O que falar:** *"Três livros que recomendo de olhos fechados pra quem tá no técnico: 'Entendendo Algoritmos' (visual e divertido), 'Foco Profundo' (pra vencer a distração do celular) e 'O Programador Pragmático' (a bíblia da postura profissional). Conhecimento que não fica obsoleto na próxima atualização do ChatGPT."*

### SLIDE 21 — Como Usar a IA Sem Virar Refém Dela
* **O que falar:** *"Não usem a IA como máquina de xerox pra colar exercícios. Usem como um mentor impiedoso: peçam pra ela encontrar falhas no código que vocês mesmos escreveram. E a regra inegociável: se você não entendeu uma linha que a IA sugeriu, você não tem autorização pra colar no seu projeto."*

### SLIDE 22 — O que o Mercado Realmente Cobra no Primeiro Emprego
* **O que falar:** *"Para passar numa entrevista de estágio hoje: primeiro, saber ler e auditar código alheio (como vimos no paper de Harvard, a fila de revisão entupiu). Segundo, fundamentos sólidos de rede, banco e filas. Terceiro, resolver problemas reais com segurança."*

### SLIDE 23 — Conclusão & O Manifesto
* **A frase de impacto:** *"A IA é um motor a jato. Mas instalado numa bicicleta sem freios, só serve pra fazer você bater no muro muito mais rápido. Regra de ouro da engenharia: nunca coloque em produção uma linha de código que você não saberia explicar às 3h da manhã num incidente grave."*

### SLIDE 24 — Contatos & QR Code
* **O Fechamento:** *"Valeu demais, galera! Quem quiser conectar, trocar uma ideia sobre carreira ou tirar dúvidas de código, meu LinkedIn e meu GitHub tão na tela. Podem apontar a câmera do celular pro QR Code agora. Muito obrigado e abro o microfone para perguntas de vocês!"*

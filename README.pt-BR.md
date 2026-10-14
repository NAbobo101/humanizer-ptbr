# Humanizer em português do Brasil

[Read in English](README.md)

O Humanizer faz um texto escrito por IA soar como se uma pessoa o tivesse escrito, sem mudar o que ele diz. Este fork acrescenta um guia para o português do Brasil, com a mesma lógica do guia em inglês e com listas, regras e exemplos tirados de fontes brasileiras, a começar pela versão em português do guia da Wikipédia sobre [sinais de texto gerado por IA](https://pt.wikipedia.org/wiki/Wikip%C3%A9dia:Sinais_de_texto_gerado_por_intelig%C3%AAncia_artificial).

**Antes:**
> Tenho o prazer de anunciar que os rascunhos compartilhados finalmente chegaram! 🚀 Durante meses, nosso próprio time se afogou em arquivos chamados final_v7.docx — e sabíamos que precisava existir um jeito melhor. Agora, duas pessoas podem editar o mesmo documento ao mesmo tempo, com cada alteração aparecendo em tempo real para ambas. Não é apenas uma funcionalidade, é uma nova forma de colaborar. Os comentários ficam ancorados na frase exata a que se referem, mesmo quando o texto ao redor evolui. E o melhor? Está disponível hoje em todos os planos, totalmente gratuito. Pense nisso.

**Depois:**
> Os rascunhos compartilhados saíram hoje. Durante meses, nosso time trocou arquivos chamados final_v7.docx, então criamos um jeito de duas pessoas editarem o mesmo documento ao mesmo tempo, cada uma vendo na hora o que a outra muda. Os comentários ficam presos à frase de que tratam, mesmo quando o texto em volta muda. É grátis em todos os planos.

O Humanizer edita para leitores humanos. Passar por detectores de IA não é o objetivo.

## Os cinco sinais mais fortes

Estes são os sinais mais comuns de texto escrito por IA, e o Humanizer reescreve qualquer um deles assim que aparece:

1. **Não é X, é Y:** "Não é só uma funcionalidade, é uma mudança de cultura."
2. **Frases de efeito:** "Leia de novo." "Pense nisso."
3. **Frases que soam profundas:** "No fim das contas, o que realmente importa é..."
4. **Rodeio antes do assunto:** "Vamos por partes." "Sinceramente?"
5. **Discutir com ninguém:** "Não estou dizendo que X, mas..."

O Humanizer procura [26 padrões](#os-26-padrões) ao todo.

## Instalação

Depois de instalado, o skill atende por `/humanizer`.

### Claude Code

```text
/plugin marketplace add NAbobo101/humanizer-ptbr
/plugin install humanizer@humanizer
```

O marketplace deste fork também se chama `humanizer`. Se você já adicionou o `blader/humanizer`, remova-o antes com `/plugin marketplace remove humanizer`.

### Codex

```bash
npx skills add NAbobo101/humanizer-ptbr --global --agent codex
```

### Claude.ai e Claude Desktop

Baixe este repositório como ZIP (**Code → Download ZIP**) e envie-o como skill nas configurações.

### Outros agentes

```bash
npx skills add NAbobo101/humanizer-ptbr --global --agent '*'
```

Tire o `--global` de qualquer comando acima para instalar só no projeto atual. Num agente que a Skills CLI não conhece, copie o `SKILL.md` e a pasta `references/` para a pasta de skills dele.

## Como usar

Chame o skill direto:

```
/humanizer

[cole o texto aqui]
```

Ou peça com suas palavras:

```
Tire a cara de IA deste texto: [seu texto]
```

Para reescrever um arquivo, passe o caminho:

```
Humanize o texto de docs/lancamento.md
```

Para que a reescrita soe como você, inclua uma amostra:

```
/humanizer

Aqui vai uma amostra de como eu escrevo:
[cole dois ou três parágrafos seus]

Agora humanize este texto:
[cole o texto da IA]
```

O Humanizer segue o ritmo, o vocabulário, a pontuação e as manias da amostra, inclusive travessões, se você os usa.

## Como funciona

Um modelo de linguagem escreve o que tem mais chance de vir a seguir, então por padrão escolhe o que serve ao maior número de leitores e assuntos. Uma pessoa escolhe para um leitor e um assunto. Cada sinal que o Humanizer procura é uma forma dessa escolha padrão.

Em português, ela ganha duas formas próprias. A primeira é a tradução automática de hábitos: os modelos aprendem sobretudo com textos em inglês e acabam vestindo estruturas do inglês com palavras em português. A segunda é o molde da redação do Enem, com conectivos empilhados, uma citação de bolso e uma proposta de intervenção no fim.

O `SKILL.md` fica em inglês e vale para qualquer idioma. Quando o texto está em português, ele manda o agente ler [`references/pt-br.md`](references/pt-br.md). Esse arquivo mantém os mesmos 26 números e traz, para cada padrão, as expressões a observar em português, o que muda na regra e um exemplo de antes e depois. O Humanizer não inventa nada: nome, número, data ou citação precisa vir do texto original ou de quem escreveu.

### O que muda no português

- O travessão é do português. O Humanizer nunca mexe no travessão de diálogo. Fora do diálogo, troca o excesso por vírgula, dois-pontos ou parênteses. O hífen com espaços que muita gente digita por falta da tecla não conta como sinal de IA.
- O português dispensa o pronome sujeito, então "Ela abriu... Ela viu... Ela guardou..." pesa mais aqui do que em inglês (§7).
- A regra do hífen do inglês não vale. No lugar dela entram convenções de outra língua ou norma: vírgula antes do "e", "Março" com maiúscula, 1,000.50, decalques como "aplicar para uma vaga" e formas do português europeu num texto brasileiro (§10).
- Título com todas as palavras em maiúscula é hábito do inglês (§20).
- O fecho de redação ("Diante do exposto, cabe ao Estado...") e a citação de bolso ("Segundo Bauman, vivemos em uma modernidade líquida") entram em §13 e §17.
- Conectivos como "além disso" e "vale ressaltar" e palavras como "fundamental" só contam em grupo, porque estudantes brasileiros aprendem a usá-los.
- O registro fica como está: "a gente", "pra" e "tá" continuam no texto informal, e o texto de Portugal continua com a grafia de Portugal.

## Os 26 padrões

Os padrões seguem a ordem de força e frequência. Os cinco primeiros justificam uma edição na primeira vez que aparecem. Os marcados como *fraco sozinho* só contam quando aparecem junto com outros sinais no mesmo trecho.

### A. Encenar em vez de afirmar

| # | Padrão | Antes | Depois |
|---|--------|-------|--------|
| 1 | **Não é X, é Y** | "Não é só um app, é um estilo de vida", "Não é sobre X. É sobre Y." | Diga o ponto direto |
| 2 | **Frases de efeito e fragmentos dramáticos** | "Leia de novo.", "Sem filtro. Sem medo. Sem desculpas." | Corte o fecho que repete e junte os fragmentos numa afirmação concreta |
| 3 | **Frases que soam profundas** | "No fim das contas, o que realmente importa é...", "Confiança é a moeda das empresas" | Troque a frase pela afirmação concreta |
| 4 | **Rodeio antes do assunto** | "Vamos por partes", "Sinceramente? Depende..." | Corte o rodeio e diga o ponto |
| 5 | **Discutir com ninguém** | "Não estou dizendo que...", "Seria tentador..." | Tire a objeção que ninguém fez e mantenha a afirmação real |

### B. Ritmo por regra

| # | Padrão | Antes | Depois |
|---|--------|-------|--------|
| 6 | **Trios forçados** | "inovação, inspiração e insights" | Use quantos itens o sentido pede |
| 7 | **Frases que começam igual** | "Ela abriu... Ela viu... Ela guardou..." | Junte as frases e deixe o sujeito oculto |
| 8 | **Travessão como conector universal** (*fraco sozinho*) | "A política — anunciada sem aviso — afeta..." | Vírgula, ponto, dois-pontos ou parênteses; o travessão de diálogo fica |
| 9 | **Ressalvas empilhadas** (*fraco sozinho*) | "de certa forma, é possível que possa eventualmente" | Mantenha só as ressalvas que a fonte sustenta |
| 10 | **Convenções de outra língua ou norma** (*fraco sozinho*) | "Terça-feira, 15 de Março", "o relatório, os números, e o plano", "aplicar para uma vaga" | Siga o Acordo Ortográfico e o uso brasileiro |
| 11 | **Voz passiva e sujeito ausente** (*fraco sozinho*) | "As alterações foram implementadas pela equipe" | Diga quem fez, quando isso ajuda |

### C. Inflação e autoridade emprestada

| # | Padrão | Antes | Depois |
|---|--------|-------|--------|
| 12 | **Palavras gastas pela IA** | "tapeçaria", "desvendar", "alavancar", "outrossim", "além disso... nesse sentido... vale ressaltar" | Use palavras comuns |
| 13 | **Importância inflada** | "um divisor de águas", "Diante do exposto, cabe ao Estado..." | Mantenha o fato e corte a importância; termine no último fato concreto |
| 14 | **Ligação vaga** | "associado a", "no âmbito de" | Diga a relação que a fonte dá |
| 15 | **Gerúndios de enfeite** | "refletindo... simbolizando... o que reforça a importância de" | Mantenha só o que a fonte sustenta |
| 16 | **Linguagem de vendas** | "encravado no coração de", "de tirar o fôlego" | Diga o que a coisa é |
| 17 | **Autoridade emprestada** | "Especialistas apontam...", "Segundo Bauman, vivemos em uma modernidade líquida" | Cite a fonte real e o que ela disse, ou corte |
| 18 | **Fugir de é, são e tem** | "se configura como... conta com... possui", "realizar a análise" | "é... tem", "analisar" |

### D. Formatação por regra

| # | Padrão | Antes | Depois |
|---|--------|-------|--------|
| 19 | **Negrito de enfeite** | "**Desempenho:** O desempenho melhorou" | Tire o negrito e troque a lista rotulada por texto corrido |
| 20 | **Títulos decorados** | "Negociações Estratégicas E Parcerias", "🚀 Fase de Lançamento:" | Maiúscula só na primeira palavra e nos nomes próprios; sem emojis |
| 21 | **Aspas curvas** (*fraco sozinho*) | `disse “o projeto”` num texto de aspas retas; « » num texto brasileiro | Siga o formato do texto |

### E. Sobras do chat e do rascunho

| # | Padrão | Antes | Depois |
|---|--------|-------|--------|
| 22 | **Resíduo de chatbot** | "Claro! Aqui está... Espero ter ajudado!" | Tire o embrulho e mantenha o conteúdo |
| 23 | **Avisos de limite e palpites** | "Não há informações públicas... provavelmente cresceu..." | Diga o que a fonte mostra, ou corte a frase |
| 24 | **Título repetido na primeira frase** | "## Desempenho" + "Velocidade importa." | Deixe o título fazer o trabalho |
| 25 | **Falar do documento em vez do assunto** | "Esta função foi adicionada para substituir...", "A tabela abaixo compara..." | Descreva o assunto |

### F. Escrever para o leitor errado

| # | Padrão | Antes | Depois |
|---|--------|-------|--------|
| 26 | **Reexplicar o que o leitor já sabe** | Uma resposta que refaz o diagnóstico e prova que o plano funciona antes de chegar à decisão | Comece pela decisão e deixe o diagnóstico para o ticket |

## Exemplo completo

**Antes (com cara de IA):**
> Passei quatro dias inesquecíveis em Ouro Preto em Julho, e preciso dizer — essa cidade roubou meu coração. Desde o momento em que fiz check-in na minha charmosa pousada a duas quadras da Praça Tiradentes, eu soube que estava em um lugar verdadeiramente especial.
>
> Sim, as famosas ladeiras são desafiadoras — com pedras irregulares entre a pousada e todo o resto, minhas pernas sentiram cada passo! — mas cada subida recompensa você com vistas panorâmicas de tirar o fôlego que fazem tudo valer a pena.
>
> Nenhuma viagem estaria completa sem visitar a icônica Igreja de São Francisco de Assis, uma verdadeira joia do barroco mineiro com obras de Aleijadinho. E a comida? Simplesmente divina. Embora o feijão tropeiro dos restaurantes do centro seja um tesouro local, meu favorito absoluto foi um pão de queijo de uma padaria escondida perto da Rua Direita, ainda quente do forno.
>
> Mas o que realmente torna Ouro Preto especial não é apenas a arquitetura — é a sensação. Caminhe uma ou duas quadras além do centro histórico e você vai descobrir um lado mais calmo e autêntico da cidade, convidando você a desacelerar e saborear cada momento.
>
> Claro, o imperdível Museu da Inconfidência oferece um mergulho fascinante na história do Brasil. As filas podem ser longas, mas a experiência vale absolutamente a pena para qualquer amante de história ou viajante curioso.
>
> Eu voltaria? Com certeza — da próxima vez fora das férias, e com sapatos melhores! Ouro Preto não é apenas um lugar para visitar; é um lugar para se apaixonar, de novo e de novo. ✨

**Depois:**
> Passei quatro dias em Ouro Preto em julho. A pousada ficava a duas quadras da Praça Tiradentes, e entre ela e todo o resto havia ladeiras de pedra irregular que minhas pernas sentiram a cada passo. A vista lá de cima compensava a subida.
>
> Fui à Igreja de São Francisco de Assis, como todo mundo manda fazer. É barroca e tem obras de Aleijadinho. O feijão tropeiro dos restaurantes do centro é o mais famoso, mas o que eu mais gostei foi um pão de queijo de uma padaria pequena perto da Rua Direita, ainda quente.
>
> A parte da cidade de que mais gostei começa uma ou duas quadras além do centro histórico, onde as ruas ficam quietas e ninguém tem pressa. O Museu da Inconfidência conta a história do Brasil e tem fila longa.
>
> Eu voltaria, da próxima vez fora das férias e com sapatos melhores.

## Fontes

Equivalentes brasileiros das referências do projeto original:

- [Wikipédia: Sinais de texto gerado por inteligência artificial](https://pt.wikipedia.org/wiki/Wikip%C3%A9dia:Sinais_de_texto_gerado_por_intelig%C3%AAncia_artificial), a versão adaptada do guia em inglês e a base das listas em português.
- [Wikipédia: Palavras a evitar](https://pt.wikipedia.org/wiki/Wikip%C3%A9dia:PAE), [Wikipédia: Grandes modelos de linguagem](https://pt.wikipedia.org/wiki/Wikip%C3%A9dia:Grandes_modelos_de_linguagem) e [Wikipédia: Inteligência artificial](https://pt.wikipedia.org/wiki/Wikip%C3%A9dia:Intelig%C3%AAncia_artificial).
- [Lei nº 15.263/2025, Política Nacional de Linguagem Simples](https://www.planalto.gov.br/ccivil_03/_ato2023-2026/2025/lei/l15263.htm): voz ativa, ordem direta, verbos no lugar de substantivos.
- [Manual de Redação da Presidência da República](http://www4.planalto.gov.br/centrodeestudos/assuntos/manual-de-redacao-da-presidencia-da-republica), 3ª edição, e o [Manual de Comunicação do Senado](https://www12.senado.leg.br/manualdecomunicacao): travessão, aspas, vírgula, maiúsculas, números e chavões.
- [Acordo Ortográfico, Decreto nº 6.583/2008](https://www2.camara.leg.br/legin/fed/decret/2008/decreto-6583-29-setembro-2008-581372-publicacaooriginal-104147-pe.html): hífen e maiúsculas.
- *Manual de Redação e Estilo* do Estadão, de Eduardo Martins: "tem" no lugar de "possui" e a lista de palavras vetadas.
- [TJSC, "Anglicismo: por que evitar"](https://www.tjsc.jus.br/web/servidor/dicas-de-portugues/-/asset_publisher/0rjJEBzj2Oes/content/anglicismo-por-que-evitar-): decalques do inglês.
- INEP, *A redação no Enem 2025: cartilha do participante*: proposta de intervenção, conectivos artificiais e repertório de bolso.

Pesquisas e reportagens sobre texto de IA em português:

- [Locatelli et al., 2024](https://arxiv.org/abs/2408.05035): redações do Enem escritas por modelos de linguagem.
- [Resende e Castilho, 2026](https://aclanthology.org/2026.stygenai-1.5.pdf): travessões e vocabulário do GPT-4o em português do Brasil.
- [Clube do Português](https://clubedoportugues.substack.com/p/nao-o-chatgpt-nao-criou-o-travessao) e [O Povo+](https://mais.opovo.com.br/reportagens-especiais/2026/05/26/o-travessao-nao-pertence-ao-chatgpt-nem-qualquer-outro-recurso-da-lingua-portuguesa.html) sobre o travessão.
- [Canaltech](https://canaltech.com.br/inteligencia-artificial/dicas-descobrir-se-texto-foi-escrito-por-ia/) e [Exame](https://exame.com/tecnologia/examelab/como-saber-se-um-texto-foi-feito-por-inteligencia-artificial/) sobre como reconhecer texto de IA.

Projeto original: [blader/humanizer](https://github.com/blader/humanizer), baseado em [Wikipedia: Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing). Outro skill para português: [fabricioctelles/humanizar](https://www.skills.sh/fabricioctelles/skills/humanizar).

## Licença

MIT

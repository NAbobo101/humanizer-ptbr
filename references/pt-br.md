# Portuguese reference

Use this file only for Portuguese text. It keeps the pattern numbers and names of `SKILL.md`, so every § reference there points at the matching entry here. Each entry gives the Portuguese watch list, the rules that change in Portuguese, and an example. Where this file changes a rule, it wins for Portuguese text. Everything else in `SKILL.md` still applies.

The English watch lists do not apply to Portuguese text, except the English loanwords named here. Never translate an English watch phrase word for word. Look for the Portuguese construction that does the same job.

## Variant

Decide the variant from the whole text and keep it. This file is written for Brazilian Portuguese. A text from Portugal or Africa keeps its variant, and its spelling is not a tell. Only a few European forms inside a mostly Brazilian text count (§10).

## Why Portuguese AI text sounds the way it does

The default choice described in `SKILL.md` explains most of it. Two pulls add Brazilian forms of the same patterns:

- **Translation by default.** Models learn mostly from English, so English syntax, idiom, and punctuation show up in Portuguese words: a subject pronoun in every sentence (§7), calques and English formats (§10), the passive with "ser" (§11), "possui" for "tem" (§18), and capitals on every word of a heading (§20).
- **The school-essay template.** Brazilian students train for the ENEM essay, and models copy its shape: stacked connectives (§12), a closing "proposta de intervenção" (§13), and a stock quotation from a famous thinker (§17).

## Brazilian voice

- Keep the register. Informal text keeps "a gente", "pra", "tá", and "né". Do not make it formal, and do not add slang the writer did not use.
- Use the spelling of the 1990 Orthographic Agreement.
- Do not chop Portuguese into short English-style sentences. Brazilian prose runs longer than model text, with more commas and subordinate clauses, and its sentence length varies more. A short sentence is fine; a row of them is a tell.
- Prefer a verb to a string of adjectives.
- Write the list of remaining patterns in the user's language, using the labels below.

## A. Staging instead of stating

### 1. Not X but Y
*Em português: Não é X, é Y*

**Watch for:** não é (só, apenas) X, é Y; não se trata (apenas) de X, mas de Y; mais do que X, é Y; "Não é sobre X. É sobre Y."; X, e não Y; a clipped tail such as "..., sem complicação", "..., sem enrolação", "..., sem achismo".
**PT-BR note:** "É sobre" is also a calque of "it's about". "Não só... mas também" is an ordinary pair; it is a tell only when the first half names something nobody claimed.
**Before:**
> O novo plano não é apenas mais barato, é uma nova forma de pagar: ele cobra por uso. Não é sobre economizar. É sobre ter controle.
**After:**
> O novo plano é mais barato e cobra por uso.
**Before (clipped tail):**
> As opções vêm do item selecionado, sem achismo.
**After:**
> As opções vêm do item selecionado, então o usuário não precisa adivinhar.

### 2. One-line closers and dramatic fragments
*Em português: Frases de efeito e fragmentos dramáticos*

**Watch for:** "Leia de novo."; "Pense nisso."; "Simples assim."; "E isso muda tudo."; "Fica a reflexão."; "E não é pouca coisa."; "Ponto."; a sentence that names what an example showed ("Isso mostra a importância de...", "A lição foi clara:"); a row of fragments ("Sem filtro. Sem medo. Sem desculpas.").
**Before:**
> Fiquei três anos na mesma empresa sem promoção. Pedi demissão numa segunda-feira. Sem plano B. Sem reserva. Sem medo.
>
> Leia de novo.
**After:**
> Fiquei três anos na mesma empresa sem promoção. Numa segunda-feira, pedi demissão sem plano B, sem reserva e sem medo.

### 3. Sayings that sound deep
*Em português: Frases que soam profundas*

**Watch for:** a verdadeira questão é; no fundo; em sua essência; o que realmente importa; no fim das contas; o segredo está em; a grande sacada; X é o novo Y; X é a linguagem (a moeda) de Y; X não é uma ferramenta, é um espelho.
**Before:**
> A verdadeira questão é se o time consegue se adaptar. No fundo, o que realmente importa é a disposição da empresa para mudar.
**After:**
> A questão é se o time consegue se adaptar, e isso depende sobretudo de a empresa estar disposta a mudar.

### 4. Staged run-up before the point
*Em português: Rodeio antes do assunto*

**Watch for:** Vamos lá; Bora; Vamos mergulhar; Vamos explorar; Vamos por partes; Sem mais delongas; Aqui vai o que você precisa saber; Spoiler:; Sinceramente?; Olha,; A real é que; O ponto é; Papo reto; Vou ser sincero; Senta que lá vem história.
**PT-BR note:** "Olha" and "sinceramente" inside a casual sentence are ordinary Brazilian speech. The tell is the standalone opener before a routine claim.
**Before:**
> Vale a pena pagar o plano anual? Sinceramente? Depende de quantas vezes por mês você vai usar.
**After:**
> Se o plano anual compensa depende de quantas vezes por mês você vai usar.

### 5. Arguing with no one
*Em português: Discutir com ninguém*

**Watch for:** Não estou dizendo que; Não me entenda mal; Para deixar claro; Isso não significa que; Alguns podem pensar que... mas; Uma abordagem tentadora seria; Seria fácil simplesmente; Você pode estar pensando.
**Before:**
> Os tokens de sessão são renovados a cada 24 horas. Seria tentador renovar reiniciando o serviço de autenticação com um cron, mas isso derrubaria todas as sessões ativas. A renovação acontece sem reiniciar nada, e os clientes atualizam o token sozinhos.
**After:**
> Os tokens de sessão são renovados a cada 24 horas sem reiniciar nada, e os clientes atualizam o token sozinhos.

## B. Rhythm by rule

### 6. Forced triads
*Em português: Trios forçados*

**PT-BR note:** Same rule. Portuguese puts no comma before the "e" that closes a simple list (§10).
**Before:**
> O evento terá palestras inspiradoras, painéis dinâmicos e oportunidades de networking. Os participantes podem esperar inovação, inspiração e insights.
**After:**
> O evento terá palestras e painéis, além de um tempo para networking.

### 7. Repeated sentence openings
*Em português: Frases que começam igual*

**PT-BR note:** Stronger in Portuguese. The verb ending already shows the subject, so a writer drops "ele", "ela", "eu", or "você" once the subject is clear. A pronoun in every sentence is a translation trace, even when the sentences do not start with it.
**Before:**
> Ela abriu a porta. Ela viu a fechadura quebrada. Ela guardou os dois detalhes.
**After:**
> Ela abriu a porta, viu a fechadura quebrada e guardou os dois detalhes.

### 8. Dashes as the universal connector
*Em português: Travessão como conector universal*

**PT-BR note:** The travessão is native to Portuguese: it opens dialogue lines and sets off inserted clauses. Never change a dash that marks dialogue in fiction, interviews, or transcripts. Outside dialogue the rule in `SKILL.md` stands, because human Brazilian expository prose uses almost no dashes and models use many. Brazilian keyboards have no travessão key, so people often type a spaced hyphen (" - "). Replace it in the rewrite, but do not count it as a tell. When a writing sample uses dashes, match its rate and its spaced form ("palavra — palavra").
**Before:**
> A nova política — anunciada sem aviso — afeta milhares de trabalhadores. As mudanças — há muito esperadas, segundo os críticos — entram em vigor hoje.
**After:**
> A nova política, anunciada sem aviso, afeta milhares de trabalhadores. As mudanças, que os críticos esperavam havia muito tempo, entram em vigor hoje.
**Keep (dialogue):**
> — Você vem amanhã? — perguntou a mãe.

### 9. Stacked qualifiers
*Em português: Ressalvas empilhadas*

**Watch for:** pode potencialmente; possivelmente poderia; de certa forma; em certa medida; é possível que eventualmente; balance with no real tension, such as "por um lado... por outro lado" or "é importante considerar todos os pontos de vista".
**PT-BR note:** "Talvez" and "costuma" alone are human habits. *Weak alone.*
**Before:**
> De certa forma, é possível que a política possa eventualmente ter algum efeito sobre os resultados.
**After:**
> A política pode afetar os resultados.

### 10. Hyphenated pairs everywhere
*Em português: Convenções de outra língua ou norma*

**PT-BR note:** The English hyphen rule does not apply. Portuguese hyphens follow Bases XV and XVI of the Orthographic Agreement. In Portuguese this entry covers conventions carried over from another language or variant. Human translators and hurried typists produce them too, so the entry is *weak alone*.
**Watch for:**
- English punctuation and formats: a comma before the "e" that closes a simple list; capitals on months, weekdays, languages, and nationalities ("Março", "Segunda-feira", "Português"); 1,000.50 for 1.000,50; 12/25/2024 for 25/12/2024; "R$200" for "R$ 200"; a full stop inside the closing quote when the quote is only part of the sentence.
- English syntax: possessives Portuguese does not need ("levantou sua mão" for "levantou a mão"); calques such as "aplicar para uma vaga" (candidatar-se), "suportar" for apoiar, "assumir" for supor, "realizar" for perceber, and "meu ponto é".
- European Portuguese in a Brazilian text: perspetiva, prémio, receção, utilizador, ecrã, equipa, registo, "estou a fazer".
**Before:**
> A reunião será na Terça-feira, 15 de Março. Ela vai apresentar seu relatório, os números do trimestre, e o plano para o ano. Eu assumo que todos leram o e-mail.
**After:**
> A reunião será na terça-feira, 15 de março. Ela vai apresentar o relatório, os números do trimestre e o plano para o ano. Imagino que todos tenham lido o e-mail.

### 11. Passive voice and missing subjects
*Em português: Voz passiva e sujeito ausente*

**PT-BR note:** The passive with "ser" ("foi realizado", "foram implementadas") is often calqued from English. The passive with "se" ("vendem-se casas") is ordinary Portuguese. Official and legal text is impersonal on purpose, so leave its register alone. *Weak alone.*
**Before:**
> Não é necessário arquivo de configuração. Os resultados são preservados automaticamente, e as alterações foram implementadas pela equipe.
**After:**
> Você não precisa de arquivo de configuração. O sistema guarda os resultados sozinho, e a equipe fez as alterações.

## C. Inflation and borrowed authority

### 12. Overused AI words
*Em português: Palavras gastas pela IA*

**Watch for (a tell wherever it appears):** adicionalmente (opening a sentence), alinhar-se com, aprofundar-se and mergulhar (figurative), desvendar, intrincado, meticuloso, vibrante, multifacetado, tapeçaria (figurative), testemunho (figurative), robusto (figurative), alavancar, potencializar, viabilizar, agregar valor, navegar (figurative), jornada (figurative), ecossistema (figurative), cenário and panorama (abstract); old formal words such as destarte, outrossim, mister se faz, supracitado, indubitavelmente, and doravante.
**Count only in groups:** crucial, fundamental, essencial, garantir, otimizar, implementar; formal words that replace plain ones ("redigiu" for escreveu, "faleceu" for morreu, "utilizou" for usou, "efetuou" for fez); and the connectives além disso, ademais, vale ressaltar que, é importante destacar que, nesse sentido, nesse contexto, dessa forma, em suma, em resumo.
**PT-BR note:** Brazilian writers use the second list, and students learn the connectives for the ENEM essay. Models stack them. INEP itself tells candidates not to use connectives "de forma artificial ou excessiva".
**Before:**
> Além disso, vale ressaltar que a culinária mineira constitui uma rica tapeçaria de sabores. Nesse sentido, o pão de queijo é um testemunho duradouro da influência das fazendas no cenário gastronômico local, evidenciando como essas receitas se integraram ao cotidiano.
**After:**
> Na culinária mineira, a influência das fazendas aparece em receitas como o pão de queijo, que virou comida de todo dia.

### 13. Inflated significance
*Em português: Importância inflada*

**Watch for:** um marco; divisor de águas; momento crucial; desempenha um papel fundamental; reflete um movimento mais amplo; deixou um legado duradouro; deixou uma marca indelével; abre caminho para; em constante evolução; na era digital; em um mundo cada vez mais conectado; no cenário atual; stock sections such as "Impacto e legado", "Desafios e perspectivas", "Prêmios e reconhecimento", or a paragraph that opens "Apesar dos desafios..."; send-offs such as "o futuro é promissor" and "um passo na direção certa".
**PT-BR note:** The Brazilian send-off is the ENEM "proposta de intervenção": a closing paragraph that gives a vague task to a vague agent. Watch for "Diante do exposto", "Portanto, faz-se necessário que", "Cabe ao Estado, em parceria com a sociedade civil,", "por meio de campanhas de conscientização", and "Só assim será possível construir uma sociedade mais justa". Outside a school essay, cut it and end on the last concrete fact. Inside a school essay the genre requires the proposal, so make it concrete instead.
**Before:**
> O Instituto Butantan foi fundado em 1901, marcando um divisor de águas na saúde pública brasileira e deixando um legado duradouro.
**After:**
> O Instituto Butantan foi fundado em 1901.
**Before (ENEM ending in an article):**
> Diante do exposto, faz-se necessário que o Estado, em parceria com a sociedade civil, promova campanhas de conscientização sobre o descarte de lixo eletrônico. Só assim será possível construir uma sociedade mais justa e sustentável.
**After:**
> (Cut the paragraph. End on the last concrete fact.)

### 14. Vague connection or association
*Em português: Ligação vaga*

**Watch for:** associado a; em associação com; ligado a; vinculado a; relacionado a; em conexão com; no âmbito de.
**Before:**
> Ele está associado à Orquestra Jovem de Vale Verde, que fundou e rege. Os concertos foram organizados em conexão com os 50 anos da cidade.
**After:**
> Ele fundou e rege a Orquestra Jovem de Vale Verde. Os concertos fizeram parte da comemoração dos 50 anos da cidade.

### 15. Shallow -ing riders
*Em português: Gerúndios de enfeite*

**Watch for:** a gerund clause added to the end of a sentence: destacando, ressaltando, evidenciando, reforçando, refletindo, simbolizando, demonstrando, contribuindo para, promovendo, fomentando, garantindo, consolidando-se como; and the relative form ", o que reforça (evidencia, demonstra) a importância de".
**PT-BR note:** A gerund for a real action at the same time is ordinary Portuguese ("saiu correndo"). The tell is the gerund that adds significance.
**Before:**
> O prédio foi pintado de azul e branco, refletindo a ligação da comunidade com o mar e simbolizando a força da tradição pesqueira, o que reforça a importância da cultura local.
**After:**
> O prédio foi pintado de azul e branco, em referência ao mar e à tradição pesqueira da comunidade.

### 16. Sales language
*Em português: Linguagem de vendas*

**Watch for:** rico (figurative); no coração de; encravado; aninhado; de tirar o fôlego; imperdível; deslumbrante; paradisíaco; charmoso; joia escondida; um verdadeiro tesouro; renomado; inovador; ampla gama de; compromisso com.
**Before:**
> Encravado em Brumadinho, no coração de Minas Gerais, o deslumbrante Inhotim é um verdadeiro tesouro, com uma rica e imperdível coleção de arte contemporânea em meio a jardins de tirar o fôlego.
**After:**
> O Inhotim, em Brumadinho (MG), reúne uma coleção de arte contemporânea e jardins.

### 17. Borrowed authority
*Em português: Autoridade emprestada*

**Watch for:** especialistas apontam; segundo especialistas; estudos mostram; pesquisas indicam; acredita-se que; alguns críticos; diversos veículos noticiaram; citado por Folha, Estadão, Valor e O Globo; forte presença nas redes sociais; mais de N mil seguidores.
**PT-BR note:** The ENEM "repertório de bolso" is a Brazilian form of this tell: a stock citation that fits any topic and props up an ordinary claim ("Segundo o sociólogo Zygmunt Bauman, vivemos em uma modernidade líquida", "A Constituição Federal de 1988 garante a todos..."). INEP warns candidates against it. Keep a citation only when it says something specific about the subject.
**Before:**
> Segundo o sociólogo Zygmunt Bauman, vivemos em uma modernidade líquida. Nesse contexto, a empresa adotou o trabalho remoto em 2021, e especialistas apontam que a medida foi crucial para reter talentos.
**After:**
> A empresa adotou o trabalho remoto em 2021.

### 18. Avoiding is, are, and has
*Em português: Fugir de é, são e tem*

**Watch for:** serve como; atua como; funciona como; se configura como; se constitui como; se apresenta como; representa; possui; ostenta; conta com; dispõe de; oferece; se trata de; a noun phrase in place of a verb: realizar uma análise (analisar), efetuar o pagamento (pagar), proceder à leitura (ler), fazer a implementação (implementar).
**PT-BR note:** Use "é", "são", "tem", and the plain verb. The Estadão style manual asks for "tem" over "possui", and the Linguagem Simples law (Lei 15.263/2025) asks for verbs instead of nouns.
**Before:**
> A Galeria 825 se configura como o espaço expositivo da associação. O local conta com quatro salas e possui mais de 280 metros quadrados. A equipe realiza a seleção das obras de cada mostra.
**After:**
> A Galeria 825 é o espaço expositivo da associação. Tem quatro salas e mais de 280 metros quadrados, e a equipe seleciona as obras de cada mostra.

## D. Formatting by rule

### 19. Bold as decoration
*Em português: Negrito de enfeite*

**Before:**
> - **Experiência do usuário:** A experiência do usuário foi significativamente aprimorada com uma nova interface.
> - **Desempenho:** O desempenho foi otimizado por meio de algoritmos mais eficientes.
> - **Segurança:** A segurança foi reforçada com criptografia de ponta a ponta.
**After:**
> A atualização traz uma interface nova, algoritmos mais eficientes e criptografia de ponta a ponta.

### 20. Decorative headings
*Em português: Títulos decorados*

**PT-BR note:** Stronger in Portuguese. Capitals on every word of a heading are an English habit. Brazilian headings capitalize only the first word and proper names. The names of publications and events may keep their own capitals.
**Before:**
> ## Negociações Estratégicas E Parcerias Globais
**After:**
> ## Negociações estratégicas e parcerias globais

### 21. Curly quotation marks
*Em português: Aspas curvas*

**PT-BR note:** Same weak rule. Brazilian print uses curly quotes (“ ”), so follow the target format. Guillemets (« ») in a Brazilian text point to European Portuguese (§10).

## E. Leftovers from the chat and the draft

### 22. Chatbot residue
*Em português: Resíduo de chatbot*

**Watch for:** Ótima pergunta!; Claro!; Com certeza!; Aqui está...; Segue abaixo...; Espero ter ajudado!; Espero que isso ajude; Se precisar de mais alguma coisa, é só chamar; Quer que eu...?; Posso ajudar com mais alguma coisa?; Espero que esta mensagem o encontre bem.
**PT-BR note:** "Prezados", "Fico à disposição", "Att.", and "Abs." are ordinary Brazilian email conventions, not residue.
**Before:**
> Claro! Aqui está um resumo da Revolta da Vacina. Ela ocorreu em 1904, no Rio de Janeiro, contra a vacinação obrigatória contra a varíola. Espero ter ajudado! Quer que eu aprofunde algum ponto?
**After:**
> A Revolta da Vacina ocorreu em 1904, no Rio de Janeiro, contra a vacinação obrigatória contra a varíola.

### 23. Knowledge-limit disclaimers and guesses
*Em português: Avisos de limite e palpites*

**Watch for:** até a data do meu último treinamento; até onde sei; com base nas informações disponíveis; embora detalhes específicos sejam escassos; não há informações públicas; não é amplamente documentado; nas fontes disponíveis; mantém um perfil discreto; preserva a vida pessoal; provavelmente cresceu (estudou, começou).
**Before:**
> Não há informações públicas sobre a infância dela, o que sugere que mantém um perfil discreto. Provavelmente cresceu em uma família de classe média, o que moldou seu interesse pela educação.
**After:**
> As fontes disponíveis não falam da infância dela. (Or cut the section.)

### 24. A heading repeated in the first sentence
*Em português: Título repetido na primeira frase*

**Before:**
> ## Desempenho
>
> Velocidade importa.
>
> Quando a página demora, o usuário vai embora.
**After:**
> ## Desempenho
>
> Quando a página demora, o usuário vai embora.

### 25. Writing about the document instead of its subject
*Em português: Falar do documento em vez do assunto*

**Watch for:** foi adicionado para substituir; gerado a partir de; compilado de; o que não conseguimos confirmar foi sinalizado; a tabela abaixo compara; esta seção está organizada por; conforme exposto acima.
**Before:**
> Esta função foi adicionada para substituir a abordagem anterior, que percorria todos os itens e tinha custo O(n²).
**After:**
> Esta função usa um mapa de hash, com busca O(1), e evita o custo O(n²) de percorrer todos os itens.

## F. Writing for the wrong reader

### 26. Re-explaining what the reader knows
*Em português: Reexplicar o que o leitor já sabe*

**Before:**
> É, você tem razão, isso contorna o problema em vez de resolver. A correção de verdade está no `MergeService`: quando um item muda de pai, ele precisa atualizar o `pipeline_id` junto com o `parent_id`. Dá para corrigir as linhas erradas pelo log de auditoria. Olhei no QA: 123 merges, só 6 linhas erradas hoje, então a limpeza é pequena. Como o `MergeService` é compartilhado, prefiro abrir outro ticket a aumentar este PR.
**After:**
> Concordo, é um contorno. Corrigir no `MergeService` aumentaria o escopo deste ticket, porque é código compartilhado e ainda exige corrigir as linhas que já estão erradas. Prefiro manter este PR restrito a esta conta e abrir outro ticket para o `MergeService` e a correção dos dados.

## When not to act in Portuguese

- Dialogue dashes, the vocative comma ("Oi, Vanessa"), and other ordinary punctuation.
- Connectives and a proposta de intervenção inside a school essay, where the genre asks for them. Make them concrete instead.
- Email conventions: "Prezados", "Fico à disposição", "Att.", "Abs.".
- Official and legal register, which is impersonal on purpose.
- Human translations, which also carry calques and English formats. §10 needs company.
- Text in another variant of Portuguese.

## Credit

The Portuguese lists draw on the Portuguese Wikipedia essay "Wikipédia:Sinais de texto gerado por inteligência artificial", Brazilian style manuals, the Linguagem Simples law, INEP's ENEM guide, and Brazilian reporting and research on AI text. `README.pt-BR.md` lists the sources.

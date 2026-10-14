# Exemplos em português do Brasil

Cinco textos sobre assuntos de outubro de 2026, cada um num gênero diferente. Um modelo de linguagem escreveu os originais a partir de uma ficha de fatos verificados, sem a skill e sem nenhum pedido para evitar sinais de IA. Depois, outro agente passou cada texto pelo Humanizer 3.2.0, instalado a partir deste repositório, com o pedido que um usuário faria: "/humanizer, humaniza esse texto pra mim". Nenhuma das duas versões foi editada à mão.

Os números, as datas e os nomes vêm das fontes de cada exemplo. A contagem de palavras ignora os marcadores de Markdown. A lista de padrões mostra o que o Humanizer marcou no original, com o número e o nome usados em [`references/pt-br.md`](../references/pt-br.md).

Os modelos atuais já evitam parte dos sinais por conta própria, então as mudanças aqui são menores que no exemplo do [README](../README.pt-BR.md). Elas mostram o que ainda sobra num texto de IA de hoje: contrastes do tipo "não é X, é Y", frases de efeito no fim dos parágrafos, trios, negrito em toda lista e fechos que inflam a importância do assunto.

| Exemplo | Gênero | Palavras antes | Palavras depois | Padrões marcados |
|---------|--------|----------------|-----------------|------------------|
| [Enem 2026](#exemplo-1) | post de blog para estudantes na reta final | 393 | 348 | §1, §2, §4, §13, §24 |
| [30 anos da urna eletrônica](#exemplo-2) | notícia de portal na semana do primeiro turno | 318 | 301 | §1, §11, §13, §24 |
| [Inteligência artificial no Brasil](#exemplo-3) | post de LinkedIn em primeira pessoa | 352 | 260 | §1, §2, §3, §4, §6, §13 e §14, §19 |
| [Dia do Professor](#exemplo-4) | comunicado de escola às famílias | 340 | 285 | §2, §3, §6, §13, §20, §24 |
| [Aparecida no feriado de 12 de outubro](#exemplo-5) | post de blog de turismo com dicas | 392 | 370 | §13, §18, §19 |

<a id="exemplo-1"></a>

## Exemplo 1: Enem 2026

**Gênero:** post de blog para estudantes na reta final. **Palavras:** 393 no original, 348 na reescrita.

**Fontes:** [Agência Brasil](https://agenciabrasil.ebc.com.br/educacao/noticia/2026-07/enem-2026-tem-mais-de-5-milhoes-de-inscritos); [Inep](https://www.gov.br/inep/pt-br/centrais-de-conteudo/noticias/enem/enem-2026-falta-um-mes-para-o-primeiro-dia-de-provas).

**O que o Humanizer marcou no original:**

- Não é X, é Y (§1): "Dormir bem, comer direito e fazer pausas não é perda de tempo."
- Frases de efeito e fragmentos dramáticos (§2): "Passar cinco horas resolvendo questões exige resistência, e resistência também se treina."
- Rodeio antes do assunto (§4): "Confira algumas orientações para as próximas semanas."
- Importância inflada (§13): "Por fim, lembre-se: o Enem é uma etapa importante, mas não define quem você é."
- Título repetido na primeira frase (§24): "Revise em vez de começar do zero" seguido de "A reta final não é hora de aprender conteúdos totalmente novos."

### Original, sem a skill

> # Enem 2026: como aproveitar a reta final antes da prova
>
> O Enem 2026 está chegando. As provas serão aplicadas nos dias 8 e 15 de novembro, em todos os estados e no Distrito Federal. Neste ano, são 5.055.818 inscritos confirmados, 5,08% a mais do que em 2025. Se você é um deles, este é o momento de transformar o que estudou ao longo do ano em resultado. Confira algumas orientações para as próximas semanas.
>
> ## Conheça a estrutura de cada dia
>
> Saber o que esperar ajuda a planejar o estudo e a controlar a ansiedade. No primeiro dia, 8 de novembro, você terá 5 horas e 30 minutos para fazer as provas de Linguagens e Ciências Humanas e a redação. No segundo dia, 15 de novembro, serão 5 horas para Ciências da Natureza e Matemática.
>
> O primeiro dia combina muita leitura com a produção de um texto. Por isso, vale decidir antes se você vai começar pela redação ou pelas questões e quanto tempo pretende reservar para cada parte.
>
> ## Revise em vez de começar do zero
>
> A reta final não é hora de aprender conteúdos totalmente novos. Priorize os temas que mais aparecem na prova e os assuntos em que você ainda erra. Refazer questões de edições anteriores ajuda a encontrar lacunas e a se acostumar com o estilo do exame.
>
> ## Pratique a redação
>
> Escreva pelo menos um texto por semana, de preferência cronometrando o tempo. Se puder, peça a um professor ou colega que leia e comente. Preste atenção à estrutura, ao recorte do tema e à proposta de intervenção.
>
> ## Faça simulados completos
>
> Reproduzir as condições reais, com o mesmo horário, a mesma duração e sem celular por perto, ajuda o corpo e a mente a se acostumarem com o esforço. Passar cinco horas resolvendo questões exige resistência, e resistência também se treina.
>
> ## Cuide da saúde
>
> Dormir bem, comer direito e fazer pausas não é perda de tempo. Um cérebro descansado rende mais do que um cérebro exausto depois de uma madrugada de estudos. Na véspera, evite maratonas de revisão.
>
> ## Organize a logística
>
> Confira com antecedência o seu local de prova, planeje o trajeto e separe os documentos e materiais permitidos. Um imprevisto no dia pode custar caro.
>
> Por fim, lembre-se: o Enem é uma etapa importante, mas não define quem você é. Confie na preparação que você construiu até aqui. Boa prova!

### Reescrita, com a skill

> # Enem 2026: como aproveitar a reta final antes da prova
>
> O Enem 2026 está chegando. As provas serão aplicadas nos dias 8 e 15 de novembro, em todos os estados e no Distrito Federal. Neste ano, são 5.055.818 inscritos confirmados, 5,08% a mais do que em 2025.
>
> ## Conheça a estrutura de cada dia
>
> No primeiro dia, 8 de novembro, você terá 5 horas e 30 minutos para as provas de Linguagens e Ciências Humanas e para a redação. No segundo, 15 de novembro, serão 5 horas para Ciências da Natureza e Matemática. Saber isso com antecedência ajuda a planejar o estudo e a controlar a ansiedade.
>
> Como o primeiro dia junta muita leitura com a produção de um texto, vale decidir antes se você vai começar pela redação ou pelas questões e quanto tempo pretende reservar para cada parte.
>
> ## Revise o que já estudou
>
> Na reta final, deixe de lado os conteúdos totalmente novos e concentre o estudo nos temas que mais aparecem na prova e nos assuntos em que você ainda erra. Refazer questões de edições anteriores ajuda a encontrar lacunas e a se acostumar com o estilo do exame.
>
> ## Pratique a redação
>
> Escreva pelo menos um texto por semana, de preferência cronometrando o tempo. Se puder, peça a um professor ou colega que leia e comente. Preste atenção à estrutura, ao recorte do tema e à proposta de intervenção.
>
> ## Faça simulados completos
>
> Reproduza as condições reais: o mesmo horário e a mesma duração da prova, sem celular por perto. Passar cinco horas resolvendo questões exige resistência, e treinar assim ajuda o corpo e a mente a se acostumarem com esse esforço.
>
> ## Cuide da saúde
>
> Dormir bem, comer direito e fazer pausas também faz parte da preparação, porque um cérebro descansado rende mais do que um exausto depois de uma madrugada de estudos. Na véspera, evite maratonas de revisão.
>
> ## Organize a logística
>
> Como um imprevisto no dia pode custar caro, confira com antecedência o seu local de prova, planeje o trajeto e separe os documentos e os materiais permitidos.
>
> Confie no que estudou até aqui. Boa prova!

<a id="exemplo-2"></a>

## Exemplo 2: 30 anos da urna eletrônica

**Gênero:** notícia de portal na semana do primeiro turno. **Palavras:** 318 no original, 301 na reescrita.

**Fontes:** [Lei nº 9.100/1995](https://www.planalto.gov.br/ccivil_03/leis/l9100.htm); [CNN Brasil](https://www.cnnbrasil.com.br/curiosidades/com-disquete-de-144-mb-e-teclado-de-borracha-a-historia-da-primeira-urna-eletronica-com-cara-de-micro-ondas-usada-em-1996/); [Rádio Senado](https://www12.senado.leg.br/radio/1/noticia/2026/10/02/utilizacao-da-urna-eletronica-completa-30-anos); [Agência Brasil](https://agenciabrasil.ebc.com.br/politica/noticia/2026-10/urna-eletronica-completa-30-anos-de-revolucao-nas-eleicoes-do-brasil); [Senado Notícias](https://www12.senado.leg.br/noticias/infomaterias/2026/03/confira-datas-e-prazos-do-calendario-eleitoral-de-2026).

**O que o Humanizer marcou no original:**

- Não é X, é Y (§1): "Isso não tirou o sistema do centro do debate. (...) Ainda assim,"
- Voz passiva e sujeito ausente (§11): "o voto é registrado a partir dos números digitados e confirmado na tela"
- Importância inflada (§13): a seção final "Próxima etapa"
- Título repetido na primeira frase (§24): "Próxima etapa" seguido de "O calendário eleitoral de 2026 ainda não terminou."

### Original, sem a skill

> # Urna eletrônica faz 30 anos na semana do primeiro turno
>
> A urna eletrônica completou 30 anos no sábado (3), véspera do primeiro turno das eleições de 2026, realizado no domingo (4). O equipamento estreou nas eleições municipais de 3 de outubro de 1996 e, três décadas depois, faz parte da rotina de qualquer eleitor brasileiro. Boa parte de quem foi às seções neste domingo nunca votou em cédula de papel.
>
> ## Uma estreia limitada
>
> Em 1996, a urna funcionou em 57 municípios, entre eles as capitais e as cidades com mais de 200 mil eleitores. Cerca de um terço do eleitorado votou eletronicamente naquele ano. No resto do país, o voto ainda era marcado à mão e contado pelas juntas apuradoras, num processo lento e sujeito a erros na leitura das cédulas.
>
> A expansão não demorou. Nas eleições municipais de 2000, quatro anos depois da estreia, todos os eleitores do país já votaram eletronicamente. Desde então, as eleições brasileiras são inteiramente informatizadas.
>
> ## O que mudou
>
> O efeito mais visível foi na apuração. Com a contagem manual, o resultado podia levar dias para sair, e votos rasurados ou ilegíveis abriam espaço para contestações. A urna eliminou a etapa de interpretar o que o eleitor quis escrever: o voto é registrado a partir dos números digitados e confirmado na tela. Hoje, os resultados costumam ser conhecidos na mesma noite da votação.
>
> Isso não tirou o sistema do centro do debate. Nos últimos anos, a segurança da urna virou tema político, e a confiança no voto eletrônico entrou nas campanhas. Ainda assim, o gesto do eleitor continua o mesmo de 30 anos atrás: digitar o número do candidato, conferir os dados na tela e apertar a tecla verde.
>
> ## Próxima etapa
>
> O calendário eleitoral de 2026 ainda não terminou. Nas disputas que não foram decididas no primeiro turno, os eleitores voltam às urnas em 25 de outubro, data marcada para o segundo turno.

### Reescrita, com a skill

> # Urna eletrônica faz 30 anos na semana do primeiro turno
>
> A urna eletrônica completou 30 anos no sábado (3), véspera do primeiro turno das eleições de 2026, realizado no domingo (4). O equipamento estreou nas eleições municipais de 3 de outubro de 1996 e, três décadas depois, faz parte da rotina de qualquer eleitor brasileiro. Boa parte de quem foi às seções neste domingo nunca votou em cédula de papel.
>
> ## Uma estreia limitada
>
> Em 1996, a urna funcionou em 57 municípios, entre eles as capitais e as cidades com mais de 200 mil eleitores. Cerca de um terço do eleitorado votou eletronicamente naquele ano. No resto do país, o voto ainda era marcado à mão e contado pelas juntas apuradoras, num processo lento e sujeito a erros na leitura das cédulas.
>
> A expansão não demorou. Nas eleições municipais de 2000, quatro anos depois da estreia, todos os eleitores do país já votaram eletronicamente. Desde então, as eleições brasileiras são inteiramente informatizadas.
>
> ## O que mudou
>
> O efeito mais visível foi na apuração. Com a contagem manual, o resultado podia levar dias para sair, e votos rasurados ou ilegíveis abriam espaço para contestações. A urna eliminou a etapa de interpretar o que o eleitor quis escrever: registra o voto a partir dos números digitados, e o próprio eleitor o confirma na tela. Hoje, os resultados costumam sair na mesma noite da votação.
>
> Nos últimos anos, a segurança da urna virou tema político, e a confiança no voto eletrônico entrou nas campanhas. Para o eleitor, porém, o gesto continua o mesmo de 30 anos atrás: digitar o número do candidato, conferir os dados na tela e apertar a tecla verde. Nas disputas que não foram decididas no primeiro turno, os eleitores voltam às urnas em 25 de outubro, data marcada para o segundo turno.

<a id="exemplo-3"></a>

## Exemplo 3: Inteligência artificial no Brasil

**Gênero:** post de LinkedIn em primeira pessoa. **Palavras:** 352 no original, 260 na reescrita.

**Fontes:** [Agência Brasil, plano de IA](https://agenciabrasil.ebc.com.br/geral/noticia/2024-07/brasil-quer-ter-supercomputador-e-desenvolver-modelos-nacionais-de-ia); [Agência Brasil, supercomputador](https://agenciabrasil.ebc.com.br/economia/noticia/2026-08/rn-vai-abrigar-supercomputador-brasileiro-de-inteligencia-artificial); [Reuters Institute, Digital News Report 2026](https://reutersinstitute.politics.ox.ac.uk/digital-news-report/2026/brazil).

**O que o Humanizer marcou no original:**

- Não é X, é Y (§1): "isso não é só um número bonito"
- Frases de efeito e fragmentos dramáticos (§2): "Ou seja: a IA já faz parte do dia a dia de muita gente"
- Frases que soam profundas (§3): "Ter um plano no papel é um passo. Ver uma decisão concreta saindo dele é outro"
- Rodeio antes do assunto (§4): "Uma notícia de agosto não sai da minha cabeça"
- Trios forçados (§6): "como profissionais, empresas e sociedade"
- Importância inflada e Ligação vaga (§13 e §14): "O anúncio se conecta a algo maior."
- Negrito de enfeite (§19): "1. **Infraestrutura**, para que a gente..."

### Original, sem a skill

> Uma notícia de agosto não sai da minha cabeça: o Brasil escolheu onde vai ficar o seu supercomputador de inteligência artificial.
>
> O governo definiu que o equipamento vai ficar no Parque Augusto Severo, da UFRN, em Macaíba (RN). O investimento é de pouco mais de R$ 1 bilhão, e a máquina deve chegar a 7.200 petaflops.
>
> Para quem trabalha com tecnologia, isso não é só um número bonito. Capacidade de computação é o que separa um país que só consome IA de um país que também consegue desenvolver os próprios modelos, treinar com dados que refletem a nossa realidade e reduzir a dependência de infraestrutura de fora.
>
> O anúncio se conecta a algo maior. O Plano Brasileiro de Inteligência Artificial, entregue em 30 de julho de 2024, prevê R$ 23,03 bilhões em investimentos até 2028. Ter um plano no papel é um passo. Ver uma decisão concreta saindo dele é outro, e é esse que me deixa otimista.
>
> Ao mesmo tempo, tem um dado que me fez parar para pensar. Segundo o Digital News Report 2026, do Reuters Institute, 13% dos brasileiros já usam chatbots de IA toda semana para se informar sobre notícias.
>
> Ou seja: a IA já faz parte do dia a dia de muita gente, inclusive na forma como as pessoas entendem o que acontece no país. E isso traz uma responsabilidade enorme para quem constrói essas ferramentas.
>
> Na minha visão, o desafio brasileiro tem três frentes que precisam andar juntas:
>
> 1. **Infraestrutura**, para que a gente tenha condições reais de pesquisar e desenvolver aqui.
> 2. **Formação de pessoas**, porque não adianta ter a máquina sem gente capacitada para usá-la bem.
> 3. **Letramento e uso responsável**, para que quem usa IA para se informar saiba questionar, checar fontes e entender os limites dessas ferramentas.
>
> Eu sigo acreditando que a tecnologia pode ser uma grande aliada do desenvolvimento do país. Mas isso depende das escolhas que a gente faz agora, como profissionais, empresas e sociedade.
>
> E vocês? Como enxergam esse momento da IA no Brasil? Estão vendo esse movimento de perto no trabalho de vocês?
>
> #InteligenciaArtificial #Tecnologia #Inovação #IA #Brasil

### Reescrita, com a skill

> Desde agosto penso na decisão do governo de instalar o supercomputador de inteligência artificial do Brasil no Parque Augusto Severo, da UFRN, em Macaíba (RN). O investimento é de pouco mais de R$ 1 bilhão, e a máquina deve chegar a 7.200 petaflops.
>
> Para quem trabalha com tecnologia, isso faz diferença, porque é a capacidade de computação que permite a um país ir além de consumir IA: desenvolver modelos próprios, treinados com dados da nossa realidade, e depender menos de infraestrutura de fora.
>
> A escolha vem do Plano Brasileiro de Inteligência Artificial, entregue em 30 de julho de 2024, que prevê R$ 23,03 bilhões em investimentos até 2028. Ver o plano sair do papel me deixa otimista.
>
> Ao mesmo tempo, segundo o Digital News Report 2026, do Reuters Institute, 13% dos brasileiros já usam chatbots de IA toda semana para se informar sobre notícias. Se essas ferramentas já fazem parte de como as pessoas entendem o que acontece no país, quem as constrói tem uma responsabilidade enorme.
>
> Na minha visão, o país precisa avançar em três frentes ao mesmo tempo. A infraestrutura dá condições reais de pesquisar e desenvolver aqui, mas não adianta ter a máquina sem formar gente capaz de usá-la bem. E quem usa IA para se informar precisa de letramento para checar fontes e entender os limites dessas ferramentas.
>
> Sigo acreditando que a tecnologia pode ajudar muito no desenvolvimento do país, mas isso depende das escolhas que a gente fizer agora.
>
> E vocês, já estão vendo esse movimento de perto no trabalho?
>
> #InteligenciaArtificial #Tecnologia #Inovação #IA #Brasil

<a id="exemplo-4"></a>

## Exemplo 4: Dia do Professor

**Gênero:** comunicado de escola às famílias. **Palavras:** 340 no original, 285 na reescrita.

**Fontes:** [Câmara dos Deputados, lei de 1827](https://www2.camara.leg.br/legin/fed/lei_sn/1824-1899/lei-38398-15-outubro-1827-566692-publicacaooriginal-90222-pl.html); [Planalto, Decreto nº 52.682/1963](https://www.planalto.gov.br/ccivil_03/decreto/1950-1969/d52682.htm); [ICL Notícias/Folhapress, Censo Escolar](https://iclnoticias.com.br/brasil-queda-1-milhao-alunos-educacao-basica/).

**O que o Humanizer marcou no original:**

- Frases de efeito e fragmentos dramáticos (§2): "Esse convite continua atual."
- Frases que soam profundas (§3): "Reconhecer quem ensina também é uma forma de ensinar."
- Trios forçados (§6): "pela dedicação, pela paciência, pela criatividade e pelo cuidado"
- Importância inflada (§13): "Foi um marco para a educação no país."
- Títulos decorados (§20): "Uma profissão que sustenta o futuro"
- Título repetido na primeira frase (§24): "Uma data com história" seguido de "A escolha do 15 de outubro tem raízes antigas."

### Original, sem a skill

> # 15 de outubro: Dia do Professor
>
> Queridas famílias,
>
> Neste 15 de outubro, celebramos o Dia do Professor. A data é uma oportunidade de reconhecer o trabalho de quem acompanha nossos alunos todos os dias, dentro e fora da sala de aula.
>
> ## Uma data com história
>
> A escolha do 15 de outubro tem raízes antigas. Nesse dia, em 1827, D. Pedro I assinou a lei que mandou criar escolas de primeiras letras nas cidades, vilas e lugares mais populosos do Império. Foi um marco para a educação no país.
>
> Mais de um século depois, o Decreto nº 52.682, de 14 de outubro de 1963, declarou o 15 de outubro feriado escolar dedicado ao professor. O texto pedia que a data fosse marcada por solenidades que enaltecessem a função do mestre. Esse convite continua atual.
>
> ## Uma profissão que sustenta o futuro
>
> Segundo o Censo Escolar, o Brasil tem 2,40 milhões de professores na educação básica em 2025, ante 2,36 milhões em 2024. Por trás desses números estão pessoas que planejam aulas, corrigem atividades, acolhem dúvidas e acreditam no potencial de cada estudante.
>
> Em nossa escola, sabemos que nenhum projeto pedagógico se realiza sem professores comprometidos. São eles que transformam o currículo em descobertas, que percebem quando um aluno precisa de mais atenção e que celebram cada conquista, das pequenas às grandes.
>
> ## Nosso agradecimento
>
> A toda a nossa equipe docente, deixamos o nosso muito obrigado. Obrigado pela dedicação, pela paciência, pela criatividade e pelo cuidado com que vocês conduzem o dia a dia da escola. O trabalho de vocês deixa marcas que acompanham nossos alunos por toda a vida.
>
> ## Um convite às famílias
>
> Convidamos as famílias a participar desta homenagem. Uma mensagem, um bilhete escrito pelas crianças ou uma simples conversa em casa sobre o papel dos professores já fazem diferença. Reconhecer quem ensina também é uma forma de ensinar.
>
> A parceria entre escola e família é o que fortalece a educação dos nossos alunos. Contamos com vocês para que este dia seja de celebração e gratidão.
>
> Com carinho,
>
> Direção e Equipe Pedagógica

### Reescrita, com a skill

> # 15 de outubro: Dia do Professor
>
> Queridas famílias,
>
> Neste 15 de outubro, Dia do Professor, queremos reconhecer o trabalho de quem acompanha nossos alunos todos os dias, dentro e fora da sala de aula.
>
> ## Por que 15 de outubro
>
> Em 15 de outubro de 1827, D. Pedro I assinou a lei que mandou criar escolas de primeiras letras nas cidades, vilas e lugares mais populosos do Império.
>
> Mais de um século depois, o Decreto nº 52.682, de 14 de outubro de 1963, declarou o 15 de outubro feriado escolar dedicado ao professor e pediu que a data fosse marcada por solenidades que enaltecessem a função do mestre.
>
> ## Os professores no Brasil e na nossa escola
>
> Segundo o Censo Escolar, o Brasil tem 2,40 milhões de professores na educação básica em 2025, ante 2,36 milhões em 2024. São pessoas que planejam aulas e corrigem atividades, que acolhem dúvidas e acreditam no potencial de cada estudante.
>
> Na nossa escola, nenhum projeto pedagógico sai do papel sem professores comprometidos. É o professor quem percebe quando um aluno precisa de mais atenção e quem comemora cada conquista dele, das pequenas às grandes.
>
> ## Nosso agradecimento
>
> A toda a nossa equipe docente, muito obrigado pela dedicação e pela paciência, e pelo cuidado e pela criatividade com que vocês conduzem o dia a dia da escola.
>
> ## Um convite às famílias
>
> Para participar desta homenagem, não é preciso muito: uma mensagem, um bilhete escrito pelas crianças ou uma conversa em casa sobre o papel dos professores já fazem diferença. Quando a família agradece ao professor, a criança aprende a valorizar quem ensina.
>
> Contamos com a parceria de vocês para que este dia seja de celebração e gratidão.
>
> Com carinho,
>
> Direção e Equipe Pedagógica

<a id="exemplo-5"></a>

## Exemplo 5: Aparecida no feriado de 12 de outubro

**Gênero:** post de blog de turismo com dicas. **Palavras:** 392 no original, 370 na reescrita.

**Fontes:** [A12, Santuário Nacional](https://www.a12.com/academia/artigos/nossa-senhora-aparecida); [Planalto, Lei nº 6.802/1980](https://www.planalto.gov.br/ccivil_03/leis/l6802.htm); [Santuário Nacional, visitantes em 2025](https://www.a12.com/santuario/imprensa/releases/aumentodefieis-2025-aparecida).

**O que o Humanizer marcou no original:**

- Importância inflada (§13): "Com um pouco de planejamento, a visita pode ser tranquila e marcante, seja qual for a sua motivação."
- Fugir de é, são e tem (§18): "Isso facilita a entrada no Santuário, a participação nas celebrações e a circulação pela cidade."
- Negrito de enfeite (§19): "**1. Reserve a hospedagem com antecedência.** (negrito nas oito dicas)"

### Original, sem a skill

> # Aparecida no feriado de 12 de outubro: dicas para aproveitar a visita
>
> Visitar Aparecida (SP) no dia da padroeira do Brasil é o desejo de muitos devotos e também um desafio de planejamento. A cidade recebe gente o ano inteiro, e o movimento chega ao auge no feriado. Para ter uma ideia, em 2025 o Santuário Nacional recebeu 10.486.118 devotos, 15% a mais do que no ano anterior. Só no dia 12 de outubro, foram 152 mil visitantes.
>
> ## Por que 12 de outubro?
>
> A devoção começou em 1717, quando os pescadores Domingos Garcia, Filipe Pedroso e João Alves encontraram a imagem de Nossa Senhora nas águas do rio Paraíba do Sul. Séculos depois, a Lei nº 6.802, de 30 de junho de 1980, declarou o 12 de outubro feriado nacional em homenagem a Nossa Senhora Aparecida, padroeira do Brasil.
>
> ## Dicas para a sua visita
>
> **1. Reserve a hospedagem com antecedência.** Com tanta gente na cidade, hotéis e pousadas costumam lotar.
>
> **2. Chegue cedo.** Nas primeiras horas do dia, o movimento costuma ser menor. Isso facilita a entrada no Santuário, a participação nas celebrações e a circulação pela cidade.
>
> **3. Planeje o transporte.** Se for de carro, pesquise antes as opções de estacionamento. Se preferir ônibus ou excursão, confirme horários de ida e de volta e combine um ponto de encontro com o grupo.
>
> **4. Vista-se com conforto.** Você vai andar bastante e pode enfrentar filas. Use calçados confortáveis, roupas leves e leve protetor solar, chapéu ou boné e uma garrafa de água.
>
> **5. Cuide dos seus pertences.** Em locais muito cheios, é melhor levar só o necessário. Mantenha documentos, celular e dinheiro em uma bolsa junto ao corpo.
>
> **6. Consulte a programação oficial.** Antes de sair de casa, confira nos canais oficiais do Santuário os horários de missas e celebrações e organize o seu roteiro a partir deles.
>
> **7. Considere os dias próximos ao feriado.** Se você prefere uma visita mais tranquila, vale ir alguns dias antes ou depois do dia 12.
>
> **8. Tenha paciência e respeito.** Para muitos visitantes, a ida a Aparecida é o cumprimento de uma promessa ou um momento de fé profunda. Respeite o silêncio nas áreas de oração e o ritmo de quem está ao seu redor.
>
> Com um pouco de planejamento, a visita pode ser tranquila e marcante, seja qual for a sua motivação. Boa viagem!

### Reescrita, com a skill

> # Aparecida no feriado de 12 de outubro: dicas para aproveitar a visita
>
> Muitos devotos querem visitar Aparecida (SP) no dia da padroeira do Brasil, e quem vai nessa data precisa se planejar. A cidade recebe gente o ano inteiro, e o movimento chega ao auge no feriado. Para ter uma ideia, em 2025 o Santuário Nacional recebeu 10.486.118 devotos, 15% a mais do que no ano anterior. Só no dia 12 de outubro, foram 152 mil visitantes.
>
> ## Por que 12 de outubro?
>
> A devoção começou em 1717, quando os pescadores Domingos Garcia, Filipe Pedroso e João Alves encontraram a imagem de Nossa Senhora nas águas do rio Paraíba do Sul. Séculos depois, a Lei nº 6.802, de 30 de junho de 1980, declarou o 12 de outubro feriado nacional em homenagem a Nossa Senhora Aparecida, padroeira do Brasil.
>
> ## Dicas para a sua visita
>
> 1. Reserve a hospedagem com antecedência. Com tanta gente na cidade, hotéis e pousadas costumam lotar.
>
> 2. Chegue cedo. Nas primeiras horas do dia o movimento costuma ser menor, e fica mais fácil entrar no Santuário, participar das celebrações e circular pela cidade.
>
> 3. Planeje o transporte. Se for de carro, veja antes onde estacionar. Se preferir ônibus ou excursão, confirme os horários de ida e de volta e combine um ponto de encontro com o grupo.
>
> 4. Vista-se com conforto. Você vai andar bastante e pode enfrentar filas, então use calçados confortáveis e roupas leves. Leve também protetor solar, chapéu ou boné e uma garrafa de água.
>
> 5. Cuide dos seus pertences. Em locais muito cheios, é melhor levar só o necessário. Mantenha documentos, celular e dinheiro em uma bolsa junto ao corpo.
>
> 6. Consulte a programação oficial. Antes de sair de casa, confira nos canais oficiais do Santuário os horários de missas e celebrações e organize o roteiro a partir deles.
>
> 7. Considere os dias próximos ao feriado. Se você prefere uma visita mais tranquila, vale ir alguns dias antes ou depois do dia 12.
>
> 8. Tenha paciência e respeito. Para muitos visitantes, ir a Aparecida é pagar uma promessa ou viver um momento de fé profunda. Respeite o silêncio nas áreas de oração e o ritmo de quem está ao seu redor.
>
> Boa viagem!

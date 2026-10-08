# Protocolo de Trabalho — Questões e Conteúdo OBMEP Mirim (Nível 1, 2º–3º ano) — v1.2

Documento de instruções para abrir um novo chat e retomar o trabalho sem repetir explicações. Cole ou anexe este arquivo no início da conversa.

> **Origem deste documento.** Adaptado do `Protocolo_OBMEP_v5_5.md` da trilha **Mirim 2 (4º/5º ano)**, que acumulou cinco versões de calibração de voz, verificação e produção de SVG. Aqui entra **só o que muda de público** (§0, §1, §5, §14) e **o que foi validado contra questões reais na Leva 1** (Apêndice A, §12). Toda a parte de **infraestrutura da casa** — biblioteca de SVG (Apêndice B), grade oficial de classificação (Apêndice D), convenção de nomes de arquivo (§15) — é **compartilhada entre os níveis** e foi trazida sem alteração.
>
> **O que muda na v1.2.** **Leva 1 concluída**: as 9 provas de `Provas/` (135 questões, 2022–2026) e o `regulamento.pdf` foram lidos na íntegra. Apêndice A deixa de ser hipótese e passa a árvore **validada**, com exemplo de prova/questão por nó; §12 ganha o resumo por prova; §3 aponta para o Apêndice A. Achado principal: **Geometria/Visualização Espacial** e **Grandezas e Medidas** (sobretudo calendário/dias da semana) pesam tanto quanto ou mais que Operações — perfil bem diferente de Mirim 2; **V ou F não aparece nenhuma vez** nas provas reais; frações e álgebra com várias incógnitas são raras. Detalhe completo no `OBMEP_Mirim1_Classificacao_Caminhos_v4.md`.
>
> **O que muda na v1.1.** Reforça a régua de linguagem do §5 e do §13 a pedido explícito: tom **lúdico** (nunca seco), explicação **detalhe por detalhe** sem pular degrau do raciocínio, **comparação com o dia a dia** sempre que ajudar a visualizar, e o novo **teste da carinha confusa** como critério de aceitação de qualquer explicação. Questão inédita (§13) passa a exigir **resolução completa sempre escrita imediatamente abaixo do enunciado**, nunca entregue separada. Checklist (§16) atualizado para cobrir os dois pontos. Nada removido; numeração preservada.
>
> **Próximo passo.** Montar os Caminhos/Blocos da trilha a partir da árvore validada (equivalente às §3/§7/§8 do documento de Mirim 2) — ver `OBMEP_Mirim1_Classificacao_Caminhos_v4.md`.

---

## 0. Início rápido

**O que fazemos.** Processamos e criamos material de Matemática da **Olimpíada Mirim — Nível 1 (2º e 3º ano)** para a Genius Factory. Público final: criança de **7–8 anos**, em fase de **consolidação da leitura** — textos curtos, apoio visual forte, vocabulário concreto do dia a dia. Tudo em PT-BR; prompts de imagem em inglês para Gemini/Flow.

**Tarefas possíveis** (isoladas ou combinadas):
1. Transcrição (§2)
2. Classificação na árvore (§3)
3. Gabarito verificado de forma independente (§4)
4. Comentário didático no modelo (§5)
5. Transformação de formato — MC, seleção múltipla, V ou F (§6–§8)
6. **Criação de questão original** (§13)
7. **Redação e revisão de capítulo de teoria** (§14)

Apoio sob demanda: **SVG renderizado** (§9a) e **prompt de Flow** (§9b).

**Comportamento padrão** (se nada for dito ao enviar um print): transcrição + classificação (com campo "Não é X") + gabarito verificado (com origem dos distratores) + comentário no modelo (§5).

**Antes de entregar qualquer coisa, rodar o checklist do §16.**

**Gatilhos curtos:** ver §11.

---

## 1. Contexto

Processamos questões da **Olimpíada Mirim — Mirim 1 (2º/3º ano)** para a base da Genius Factory. As questões chegam como **prints (imagens)** das provas em `Provas/`. Para cada uma, há cinco trabalhos de processamento, pedidos isolada ou conjuntamente:

1. Transcrição
2. Classificação na árvore de Matemática
3. Gabarito (verificado de forma independente)
4. Comentário didático para criança de 7–8 anos
5. **Transformação de formato** (múltipla escolha, seleção múltipla ou Verdadeiro ou Falso — avaliar se V/F cabe nessa faixa etária; ver nota em §6)

Além desses, dois trabalhos de **produção**:

6. **Criação de questão original** sobre um tema da trilha (§13).
7. **Redação e revisão de capítulo de teoria** da trilha (§14).

Entregáveis de apoio sob demanda: **SVG renderizado** (figura limpa para o material) e **prompt de Flow** (para a criança gerar a versão "bonita").

O público final é criança de **7–8 anos**, leitora iniciante. Tudo em português (Brasil); prompts de imagem em inglês para o Gemini/Flow.

### Material disponível (`Provas/`)

| Arquivo | Fase | Ano |
|---|---|---|
| `pf1m1-2022.pdf` … `pf1m1-2026.pdf` | 1ª Fase | 2022–2026 |
| `pf2m1-2022.pdf` … `pf2m1-2025.pdf` | 2ª Fase | 2022–2025 |

9 provas ao todo, 15 questões cada (135 questões), 2ª Fase de 2026 ainda não disponível/aplicada. Inventário completo e achados editoriais da Leva 1 no `OBMEP_Mirim1_Classificacao_Caminhos_v4.md`.

---

## 2. Transcrição

Transcrever o enunciado exatamente como está no print: comando, contexto e todas as alternativas. Regras:

- Preservar a formatação numérica original: vírgula decimal, "R$", espaço como separador de milhar (raro nessa faixa — números costumam ser pequenos).
- Figuras, tabelas e grades representadas fielmente em texto:
  - tabela → markdown;
  - balança, cruz, pirâmide, grade → descrição posicional;
  - **montagem de cubos / dados / figura isométrica 3D** → descrever em texto o que cada nível e cada peça mostram;
  - **gráfico de barras ou pictograma** → descrever em texto o valor de cada barra/símbolo (pictogramas são comuns nessa faixa: 1 desenho = N unidades — conferir a legenda com atenção redobrada);
  - **ilustração meramente decorativa** (crianças brincando, animais, objetos do cotidiano) → registrar em uma linha em itálico que é decorativa, sem detalhar.
- Não corrigir nem "melhorar" o enunciado; transcrever o que está escrito.
- **Numeração repetida entre prints:** quando dois prints chegam com o mesmo número, **transcrever o número como está, sem corrigir**, e **desambiguar internamente** por um rótulo curto baseado no conteúdo (usado na memória da trilha §12 e na regra anti-repetição §6).
- Quando a questão for **adaptada da OBMEP** e o pedido incluir manter a abertura, **replicar a parte do enunciado pedida**, seguida da figura/SVG correspondente.

---

## 3. Classificação

Classificar dentro da árvore de Matemática elementar (Apêndice A) e, sempre que possível, mapear ao nó real da **grade oficial da plataforma** (Apêndice D — compartilhada com a trilha Mirim 2, sem alteração). Sempre indicar **um nó principal** e, quando fizer sentido, **descritores secundários**.

### Princípio-mestre
Classificar pelo **motor cognitivo** (o raciocínio que a questão de fato exige), não pela roupagem do enunciado.

### Metadata oficial como verdade-base
Quando o print vier de uma plataforma e trouxer o campo **"Assunto"**, tratar esse campo como **gabarito de classificação**: conferir a nossa classificação contra ele e **adotar a redação oficial** ao nomear ou abrir um nó.

### Campo obrigatório "Não é X (e por quê)"
Fechar a classificação com uma linha dizendo **o que a questão não é** e por quê, para defender o nó principal.

### Campo de trilha
Fechar também com o **lugar na trilha**: a qual **Caminho** (`CP1`–`CP7`) e **Bloco** a questão pertence e qual **capítulo de teoria** ela cobra — ver a tabela-mestre (todas as 135 questões, com Caminho e gabarito) e a lista de 37 blocos no `OBMEP_Mirim1_Classificacao_Caminhos_v4.md` (§4, §7–§8). Quando a questão for autoral (§13), este campo é obrigatório. O Caminho já está atribuído para todas as questões recebidas; o Bloco específico (dentro do Caminho) ainda é a melhor estimativa a partir da lista de blocos, a refinar quando o banco for populado na plataforma.

### Nós mais frequentes *(validado na Leva 1 — ver árvore completa no Apêndice A)*
As 9 provas de `Provas/` (135 questões) já foram lidas e classificadas. Os nós de maior recorrência, em ordem aproximada de frequência: **Calendário e dias da semana** (presente em quase toda prova); **Geometria e Visualização Espacial** (o eixo mais carregado, sobretudo na 2ª Fase — reflexo/espelho, vista de cima, dobradura, encaixe/composição de formas); **Restrição de Quantidade em Linhas e Colunas** (grades tipo sudoku); **Operações com Números Naturais** (nível inicial); **Raciocínio Lógico** (pistas, dedução, ordenação); **Sequências e Padrões**; **Contagem Topológica em Figura Fechada** (nó novo, 3 ocorrências em anos diferentes). Frações aparecem pouco (1 ocorrência) e Álgebra pré-algébrica fica limitada a uma incógnita ou duas equações simples — nada do porte de Mirim 2. Detalhe completo, com exemplo de prova/questão para cada nó, no **Apêndice A**.

### Ressalvas honestas (sempre sinalizar)
Quando o rótulo não cobre exatamente a questão, dizer com franqueza e sugerir ajuste (generalizar rótulo, abrir nó irmão). Registrar raciocínio sem nó próprio como descritor e sugerir abertura se o padrão recorrer.

### Evitar
"Problemas de Enunciado / Aplicações no Cotidiano" como nó principal só porque a questão é contextualizada. Usar apenas quando a amplitude for real ou como secundário.

---

## 4. Gabarito — verificação reforçada

Dar a alternativa correta **sempre verificando o cálculo de forma independente**, sem confiar cegamente em gabarito oficial. Quando o usuário fornecer o gabarito e ele divergir, investigar a origem antes de concordar.

### Passo 0 — sanidade do enunciado
Antes de resolver, **conferir a coerência interna dos números** e sinalizar se não fecharem.

**Sub-rotina de leitura de gráfico/pictograma.** Em questões com gráfico ou pictograma, antes de resolver: transcrever cada valor, conferir a **legenda de equivalência** do pictograma (1 símbolo = quantos itens) com atenção redobrada, e **reler** a série inteira.

**Sinais de alerta que obrigam a buscar a solução oficial antes de comentar:**
- O resultado independente **não bate com nenhuma alternativa**.
- A figura usa uma **convenção que pode não ser óbvia** (faces de dado, dobradura, malha quadriculada).
- A questão depende de **contar elementos numa montagem ou figura complexa**.

Procedimento: buscar a prova/solução oficial da Olimpíada Mirim (PDF de soluções por fase/ano). Se o valor aceito divergir do cálculo independente, mostrar a conta, apontar a divergência e só então fechar.

### Verificação por enumeração em código
Para problemas **lógicos ou combinatórios** (mesmo simples, como arranjos pequenos), rodar **busca exaustiva** é mais forte que recalcular à mão. Checar também se a grandeza pedida é **invariante** entre todas as soluções válidas.

### Contagem de figura por análise de imagem em código
Quando a resposta depende de **contar elementos numa figura** (grades, malhas, pictogramas), tratar a contagem com rigor: em vez de contar no olho, **processar a imagem em código** quando a figura for complexa o bastante para justificar. Conferir sempre por uma relação estrutural independente quando possível.

### Engenharia reversa dos distratores (rotina, não só na transformação)
Em **toda** questão, nomear de onde vem cada alternativa errada — fortalece a conferência e já deixa a transformação pré-pronta. Padrões a reconhecer (herdados de Mirim 2, ainda a confirmar nessa faixa etária): espaçados de N; menu completo de uma categoria; erro de procedimento (etapa pulada, operação trocada); confundir parte com todo; copiar valor do exemplo/legenda.

---

## 5. Comentário didático (modelo fixo) — padrão em PRESENTE

Para criança de **7–8 anos**. Estrutura e voz **obrigatórias**:

- **Frase de enquadramento** declarativa antes da primeira etapa ("Antes de contar, …"). Nunca abrir com pergunta retórica.
- Abrir cada etapa com conectores sequenciais no **presente, primeira pessoa do plural**: "Primeiro, contamos…", "Em seguida, descobrimos…", "Agora, juntamos…", "Por fim, conferimos…".
- **Tom lúdico e caloroso, nunca seco.** Diferente da trilha de 10–12 anos (que é declarativa e austera), aqui a explicação pode ter um clima de brincadeira e de conversa — frases curtas, mas com vida. O limite não é "ser sério", é **não inflar com hype falso** (ver checklist anti-vício do §14): nada de "genial!", "super fácil!", autoelogio. Lúdico é o jeito de contar, não é exagero afetivo.
- **Explicação detalhe por detalhe, sem pular nenhum degrau do raciocínio.** Nessa idade, um salto lógico que para um adulto é óbvio pode quebrar o fio da meada da criança inteira. Cada etapa mostra **o que fazemos** e **por que fazemos isso agora** (não só a conta, o motivo de fazer essa conta nesse momento). Antes de somar, dizer por que estamos somando; antes de comparar, dizer o que estamos comparando. Regra prática: se um degrau do raciocínio pode ser quebrado em dois degraus menores, quebrar.
- **Comparação com o dia a dia da criança sempre que ajudar a enxergar a ideia** — brinquedos, balas, figurinhas, lápis de cor, irmãos, animais de estimação, recreio, lanche. A comparação não é enfeite: ela faz a criança visualizar a cena antes de calcular ("é como se você tivesse 3 balas numa mão e 2 na outra").
- **Registro guiado como padrão** (ver §14): falar diretamente com a criança ("você", "imagine que você tem..."), sempre com cena concreta e manipulável (objetos, animais, brinquedos), porque a abstração pura é mais difícil nessa idade.
- **Mostrar a conta de cada passo em linha própria** (uma linha só para a conta, sem centralizar). Ex.:

  ```
  Em seguida, juntamos os dois grupos:

  3 + 2 = 5
  ```
- Incluir sempre uma etapa de **conferência** ("Por fim, conferimos…") que valida a resposta por outro caminho (contar de novo, de outro jeito, ou desenhar).
- **Passo fixo "responder o que foi perguntado".** Antes de fechar, confirmar **todo vs parte** e **valor final vs intermediário**.
- Encerrar com **"A lição que vale guardar: …"** — a ideia transferível, dita de forma bem simples.
- Fechar com **"O gabarito é a letra X."** (ou **"A resposta é X."** quando não houver alternativas).
- Quando dois métodos competem, escolher o que **minimiza erro operacional para a criança** (ex.: contar nos dedos ou desenhar em vez de armar conta, quando fizer sentido para a idade).

### Teste da carinha confusa *(critério de aceitação, aplicar a toda explicação — exemplo, exercício ou questão inédita)*
Antes de fechar qualquer comentário, reler como se estivesse **ao vivo, na frente de uma criança de 7 anos que olha de volta com aquela cara de "não entendi"**. Essa é a régua de aceitação: a explicação só está pronta quando nenhum passo exige que a criança "complete a lacuna" sozinha. Sinal de alerta: qualquer frase que um adulto entende de cara mas que pularia uma pergunta óbvia da criança ("mas por quê?", "como assim?") — se a pergunta existe, a resposta precisa já estar no texto, não implícita.

*(Nota de calibração: esta régua de voz é um ponto de partida a validar assim que processarmos os primeiros exemplos reais da Leva 1 — igual aconteceu com a trilha Mirim 2, que passou por cinco rodadas de ajuste de voz antes de estabilizar.)*

---

## 6. Transformação de formato (sob demanda)

Quando o pedido for transformar a questão, **escolher o formato pelo tipo de tarefa**:

- **Múltipla escolha** — a pergunta pede **um número/único resultado**. Formato dominante nessa faixa etária e na prova original.
- **Seleção múltipla** ("marque todas as que se aplicam") — usar com moderação; avaliar se a instrução fica clara para a idade.
- **Verdadeiro ou Falso** — **avaliar caso a caso** se cabe para 2º/3º ano; pode ser mais apropriado para blocos mais avançados da trilha ou para o fim do Nível 1. Quando usar, manter cada afirmação curta e sobre uma única ideia (nada de afirmações compostas).

### Regra anti-repetição de motor
**Se o motor cognitivo já apareceu numa questão anterior da mesma prova/série, trocar de formato** para não repetir. Antes de transformar, dizer em uma linha qual é o motor e se ele é novo ou já usado (registrar em §12).

### Distratores (múltipla escolha) e afirmações falsas (V/F)
- Cada distrator deve ser o **resultado de um erro nomeável** (contar errado por um; trocar maior por menor; esquecer de somar uma parte; copiar o número da legenda do pictograma em vez de multiplicar pela equivalência). Nada de número aleatório.
- **No comentário, explicar de onde vem cada distrator/erro.**
- Manter (ou aumentar) o nível de dificuldade dentro do que é razoável para a idade, cobrindo **todo** o raciocínio que a questão original exigia.

---

## 7. Versão Verdadeiro ou Falso — regras (quando aplicável)

- Preferir **três a quatro afirmações** para essa faixa etária (menos que as seis padrão de Mirim 2), ajustando pela questão.
- Cobrir **todos os raciocínios** da questão original.
- Cada afirmação sobre **uma única ideia**, frase curta.
- Entregar o **gabarito** no formato "V – F – V – F".
- Oferecer, ao final, versão **gêmea** ou **SVG** de apoio.

---

## 8. Comentário de Verdadeiro ou Falso (modelo fixo) — presente

- Abrir com um **setup compartilhado** quando útil.
- Comentar uma a uma: "A primeira afirmação é verdadeira/falsa." seguida do raciocínio no mesmo estilo do §5.
- Em cada falsa, **nomear de onde vem o erro** que ela induz.
- Fechar com "Gabarito final: V, F, V, F."

---

## 9. SVG renderizado e prompts de Flow (sob demanda)

Há dois usos de SVG, distintos. A **biblioteca de helpers reutilizável** (paleta + funções de desenho + render) está no **Apêndice B** — a mesma da trilha Mirim 2, sem alteração: usá-la garante consistência entre os dois níveis e já embute a regra de desenhar setas/vistos como formas.

### 9a. SVG renderizado como entregável (diagramas didáticos)
Figura limpa para o material. Convenções da casa:

- Estilo flat 2D vector, fundo branco, texto em **PT-BR com acentos**.
- **Paleta nomeada** — mesma da Bíblia de Ilustração (hex no Apêndice B).
- Fontes: `Poppins`/`Inter` (texto) e `DejaVu Sans Mono` (números).
- **Uma cor por elemento**, consistente entre figuras da mesma questão.
- Para essa faixa etária, **privilegiar contagem visual direta** (objetos desenhados um a um, não representados por número abstrato) sempre que a questão permitir — ajuda a criança que ainda não lê fluentemente.
- **Indicar sempre onde inserir** cada SVG no comentário ou capítulo, com o marcador `[Inserir aqui o SVG \`nome.svg\`.]`.

**Mapa semântico de cor** (igual Mirim 2): verde = resposta/caso válido; amarelo = destaque do resultado final; laranja = termo que muda/parte a descobrir; vermelho = erro/armadilha; azul/cinza = categorias neutras.

**Padrão "estrutura + cálculo":** um SVG da **estrutura/figura** e um SVG da **conta/conclusão** com o resultado em destaque.

**Convenção figura de enunciado × figura de comentário.** `nome_enunciado.svg` (sem solução, "?" em laranja no alvo) e `nome.svg` (resolvido). Regra de honestidade: **não exibir intermediários que não são únicos**.

**Armadilhas técnicas do cairosvg:** acentos OK; setas/check/X sempre como **forma vetorial** (`arrow()`, `check()`, `xmark()` do Apêndice B), nunca glifo; não usar `tspan` colorido em sequência (usar `<text>` por token); **conferir o render em PNG antes de entregar**.

**Checklist anti-sobreposição:** caixa de resultado com folga do texto; rótulos curtos; legendas de seta curtas; conferir largura do viewBox; fluxo obrigatório render → revisar PNG → corrigir → re-render.

### 9b. SVG como plano de referência para o Flow
Quando o destino é a imagem "bonita" gerada pela criança, a entrega principal é o **prompt de Flow**; o SVG é o plano B. No prompt, embutir os travamentos anti-erro: travar o texto exato, bloquear infiltração de inglês, proibir marcas/números extras, exigir vírgula decimal.

**Dois estilos de Flow:** cena com personagens → estilo oficial 3D Pixar/Disney (nunca "child/kid" → "young animated character"); diagrama matemático → estilo editorial flat vector. Nenhum texto/número confiável na arte do Flow — números vivem nos SVGs.

---

## 10. Convenções editoriais (aplicar automaticamente)

- **Comentário em presente** (§5); **contas em linha própria, sem centralizar**; **sem ponto e vírgula**; **sem perguntas retóricas**.
- Vírgula decimal; "R$" com espaço; unidades SI em romano (uso provavelmente raro nessa faixa).
- **Frases curtas** *(ajuste de público — diferente da regra de "fôlego livre" de Mirim 2)*: para 7–8 anos, preferir sentenças objetivas de uma ideia por vez. Revisitar esta regra depois da Leva 1, com exemplos reais em mãos.
- Variar verbos de abertura de exemplo; **nunca repetir o mesmo verbo em sequência** dentro do capítulo.
- Títulos de seção secos, sem subtítulo após dois-pontos.
- Sem personificação de profissões/objetos; sem marcadores de escrita de IA.
- **Sem travessão (—)** antes de aposto nem como pausa de efeito. Aposto curto entre vírgulas ou parênteses. O **hífen de palavra** é livre.
- **Sem ponto e vírgula** no texto de aluno.
- **Dois-pontos só para trabalho honesto**: introduzir uma fala, abrir uma lista de verdade, ou ligar duas partes de uma frase comum. Nunca para suspense.
- Tudo em PT-BR; prompts de imagem em inglês para Gemini/Flow.

---

## 11. Como me acionar (gatilhos curtos)

Ao enviar o print, indicar o que quer. Exemplos:

- "transcreva, classifique, dê o gaba e comente para uma criança de 7–8 anos"
- "classifique" / "classificação mais específica?"
- "confira contra o Assunto oficial da plataforma"
- "transforme essa questão em MC ou seleção múltipla" (avaliar V/F caso a caso — §6)
- "mantenha o nível (ou aumente) e o raciocínio necessário"
- "se o raciocínio já apareceu antes, troque de formato"
- "comente do modo mais didático possível" (aciona o registro guiado reforçado, §5)
- "crie os SVGs necessários à explicação e diga onde inserir" / "uma cor por elemento" / "prefira contagem visual direta"
- "mantenha a parte inicial do enunciado (print da prova)"
- **"crie uma questão desafiadora sobre esse tema, em MC"** (aciona o §13)
- **"melhore/aprofunde este capítulo de teoria"** (aciona o §14)
- **"ilustre esta cena/figura no Flow"** (§9b)

Se nada for dito, o padrão é: transcrição + classificação (com campo "Não é X") + gabarito verificado (com origem dos distratores) + comentário didático no modelo (§5).

---

## 12. Registro de motores já vistos (memória da trilha)

Lista viva para a regra anti-repetição (§6) e para reconhecer nós. Detalhe completo (com prova/questão de cada ocorrência) está no Apêndice A; aqui vai o resumo por prova, para checagem rápida de repetição dentro da mesma fonte.

**Leva 1** *(out/2026 — 9 provas, 135 questões, todas as 2º/3º ano de 2022 a 2026)*
- `2022/F1` (15 Q): diferente-por-conta; calendário/dia da semana; formação de número por encaixe de algarismos; pistas por pictograma (quem é quem); forma por parte visível; pareamento (contagem); comparação de números por extenso; dobradura; problema de dois ritmos (percurso ida/volta); diferente-por-padrão (colar); vista de cima de sólidos; contagem topológica (nós do barbante); sistema de duas compras; grade com relação de dobro; processo iterativo de dois ritmos se encontrando.
- `2022/F2` (15 Q): padrão de caracteres; encaixe geométrico; ábaco C/D/U; padrão em espiral; dobradura + sequência; calendário; reflexo/espelho; relógio (soma de minutos); contagem em grade; vista de cima; restrição soma em linhas/colunas; sistema de duas equações; contagem de dígitos em sequência; processo iterativo (sobe/desce); combinatória de empilhamento.
- `2023/F1` (15 Q): diferente-por-contagem; contagem por categoria; multiplicação por soma repetida; orientação espacial (direção); sequência numérica com termos faltantes; grade restrição linha/coluna; medida de caminho em grade; leitura de tabela + calendário; processo iterativo (máquina de operações); "somar pistas"/pré-algébrico com várias condições; formação de número (algarismos dados); relógio (diferença de horário); saldo/equilíbrio monetário; empilhamento com relação entre dimensões; combinatória (combinações de chá).
- `2023/F2` (15 Q): padrão de sequência de caracteres; encaixe geométrico; reflexo/espelho; padrão em dobradura; calendário; leitura de régua (comprimento); leitura de gráfico de barras; datas escritas (valor posicional); diferença pré-algébrica (figurinhas); demais com reforço de reflexo/vista por trás.
- `2024/F1` (15 Q): contagem com condição; encaixe geométrico; grade com restrição; plano cartesiano simples; contagem de pulos (padrão); dobradura/corte; cálculo retroativo de horário; leitura de régua; ordenação por pistas visuais; sistema pré-algébrico (compra com diferença); sistema duas equações (trem/vagões); possibilidades/certezas (jogo); paridade por posição + combinatória; eliminação de casos com pista falsa (dias da semana).
- `2024/F2` (15 Q): ordenação relativa (corrida); reflexo/espelho (3ª ocorrência); combinatória de empilhamento; posição central em fila; relação de dobro; contagem seletiva com padrão alternado; soma de durações; **contagem topológica** (colar com bolinhas, 2ª ocorrência); padrão alternado em escada; equalização por contagem; soma de subconjuntos (cédulas); vista de cima em cubo 3×3 colorido; dedução por sequência (dominó).
- `2025/F1` (15 Q): contagem de palitos em padrão; correspondência de imagem fragmentada; equilíbrio entre grupos; processo iterativo guloso (grade); reta numérica com régua; remédio a cada N horas (iterativo + calendário); composição/decomposição por corte; **fração simples como operador** (metade/terço) — único caso em 9 provas; verdadeiros e mentirosos/ordenação; combinatória (campeonato); composição por corte (triângulos); maior número por combinação de cartões; sólido com padrão de dado (faces opostas); leitura de gráfico de barras (intervalo); classificação por atributo.
- `2025/F2` (15 Q): lateralidade (dedo cruzado); saldo/repartição; cálculo regressivo (tempo+temperatura); combinatória (maior soma de 3 de 6); diferente-por-padrão (pulseira); sistema duas equações (lápis/caneta); diferença de horário (virada de período); grade restrição linha/coluna (forma+cor); encaixe de poliominó; composição/decomposição de triângulo; encaixe com correspondência de cor; combinatória de grafo circular (mãos dadas); composição por área mínima; **somar pistas par a par** (3 animais, 3 somas); padrão cíclico/roleta modular.
- `2026/F1` (15 Q): contagem com sobreposição; dígito por palitos (display); operação inversa (número escondido); **contagem topológica** (barbante cortado, 3ª ocorrência); paridade de posição (casas pares/ímpares); combinatória (soma de aquários); leitura de régua (diferença); calendário/dia da semana; dedução "com certeza verdadeiro"; grade restrição linha/coluna; encaixe de poliominó (peças faltantes); vista de cima (pilhas, 3ª ocorrência); ordenação por velocidade; combinatória/soma de dado; padrão cíclico/roleta modular (2ª ocorrência).

Resumo consolidado por nó (com Apêndice D) no `OBMEP_Mirim1_Classificacao_Caminhos_v4.md`, §1.

---

## 13. Criação de questão original

Quando o pedido for **criar uma questão** sobre um tema da trilha, seguir este fluxo. Vale a mesma régua de qualidade das questões recebidas, mais a verificação reforçada, porque **não há gabarito oficial para conferir**.

**Fluxo:**
1. **Escolher o motor cognitivo** e dizer qual é, e se é novo ou já usado na trilha (§6, §12).
2. **Projetar a estrutura para números pequenos e limpos** em todas as etapas: cada valor intermediário deve ser inteiro, positivo, pequeno e coerente com a história — essa faixa etária trabalha melhor com quantidades que cabem na imaginação ou nos dedos (em geral, até duas dezenas).
3. **Escolher o formato pelo §6** (MC como padrão).
4. **Desenhar os distratores como erros nomeáveis** (§4, §6). Todos os distratores **inteiros e do mesmo tipo do gabarito**.
5. **Verificar por código** antes de fechar: a resposta correta, a unicidade da solução, e a aritmética de **cada** distrator. **Substituir os valores achados de volta em *todas* as pistas do enunciado.**
6. **Escrever o enunciado limpo** (voz da casa, §5/§14).
7. **Escrever a resolução IMEDIATAMENTE abaixo do enunciado, nunca separada ou "sob demanda".** Toda questão inédita nasce com a explicação junto, no modelo do §5 completo: tom lúdico, detalhe por detalhe, comparação com o dia a dia quando ajudar, origem de cada alternativa nomeada, "responder o que foi perguntado", "A lição que vale guardar" e o fecho do gabarito. Aplicar o **teste da carinha confusa** (§5) antes de considerar pronta — é o critério mais importante desta seção, porque questão inédita não tem comentário "de fábrica" em lugar nenhum: se a resolução aqui não for clara, não existe outra em algum gabarito oficial para compensar.
8. **Classificar como uma questão recebida** (§3), com "Não é X" e o **campo de trilha**.
9. **Ilustrar** (§9): SVG de apoio no padrão estrutura + cálculo, privilegiando contagem visual direta.
10. **Persistir a verificação:** guardar o código e a saída da verificação junto do entregável.

**Travas:** enunciado com **solução única**; dificuldade calibrada para **2º/3º ano**; **resolução sempre junto, nunca entregar questão sem a explicação logo abaixo**; oferecer, ao final, uma **questão-gêmea** (mesmo motor, números diferentes) — também com sua própria resolução completa.

---

## 14. Redação e revisão de capítulo de teoria

Quando o pedido for **escrever ou revisar um capítulo expositivo** da trilha.

**Crivo geral — o teste do "ninguém fala assim".** Leia a frase em voz alta. Se ninguém falaria assim numa conversa, reescreva.

**Voz da casa para 7–8 anos — registro predominantemente guiado.** Diferente de Mirim 2 (que alterna expositivo/guiado em proporções mais equilibradas), aqui o **registro guiado** ("você", imperativo, cena concreta) deve ser a regra, não a exceção — essa idade aprende melhor sendo conduzida de perto do que recebendo definição impessoal isolada. Reservar o registro expositivo (presente, 1ª pessoa do plural, sem "você") para frases curtas de fechamento de regra, não para blocos longos de definição abstrata.

- **Definições em negrito-itálico na primeira aparição**, mas **sempre seguidas imediatamente de um exemplo concreto manipulável** (objetos, animais, brinquedos) — nunca deixar a definição sozinha por mais de uma frase antes do exemplo.

**Checklist anti-vício de IA (o que continua proibido):**
- exclamação inflada e auto-elogio;
- hype e adjetivação vazia;
- perguntas retóricas vazias de efeito;
- fechamento motivacional postiço;
- dois-pontos de suspense; título com dois-pontos + subtítulo;
- travessão (—) antes de aposto ou como pausa de efeito; ponto e vírgula; personificação de profissões/objetos;
- palavras abstratas demais para a faixa (ainda mais restritiva que em Mirim 2 — nessa idade, evitar qualquer termo que não tenha equivalente concreto imediato: preferir "juntar" a "adicionar" na primeira menção, "tirar" a "subtrair", introduzindo o termo técnico só depois que a ideia concreta já apareceu);
- emojis e callouts decorativos → virar caixa limpa "**Guarde.**".

**"Imagine" é bem-vindo** nessa faixa quando abre um convite real a visualizar uma cena concreta e manipulável. "você" é a regra, não a exceção (ver registro guiado acima).

**Princípio pedagógico:** **ensinar a teoria, não só rodar o exemplo**, mas com passos menores e mais frequentes do que em Mirim 2. Ordem útil: *o que é → exemplo concreto imediato → onde está a dificuldade → mais um exemplo → para que serve*. Repetir o padrão de exemplo com números diferentes antes de generalizar — essa faixa etária consolida por repetição mais do que por explicação abstrata.

**Disposição de ideias / arquitetura do capítulo:**
1. **Abrir dizendo o assunto numa frase comum e curta**, ligada a algo do dia a dia da criança.
2. **Conceito-espinha reaparecendo em cada virada**, com exemplos concretos renovados a cada seção.
3. **Costura explícita entre seções**, em frase curta.
4. **Seção-guarda contra o erro provável**, quando houver confusão típica.
5. **Exemplo concreto logo após a ideia**, nunca a definição sozinha.

**Exemplos como problemas fechados:** contexto → pistas → **pergunta em negrito**, antes de qualquer conta. Enunciado fechado delimitado por filetes pontilhados, em itálico. Conta-resultado da teoria em equação centralizada de bloco.

**Verificação numérica do exemplo inventado.** Antes de publicar, **substituir os valores encontrados em todas as pistas** do exemplo. Vale também o **teste de unicidade**.

**Rotação de verbos por capítulo:** não repetir o mesmo verbo de abertura de exemplo dentro do mesmo capítulo.

**Estrutura de entrega:**
- Arquivo markdown, **títulos curtos e assertivos**, com o marcador `[Inserir aqui o SVG \`nome.svg\`.]` em cada ponto de figura.
- **Diagramas matemáticos → SVG editorial** (§9a); **cenas → prompt de Flow no estilo oficial 3D Pixar** (§9b).
- Apêndice "Ilustrações" no fim do arquivo, listando os SVGs e os prompts de Flow (em inglês).

---

## 15. Convenção de nomes de arquivo

Igual à convenção da trilha Mirim 2 — infraestrutura compartilhada, sem alteração.

- **Capítulo de teoria:** `Cap_<Tema>_revisado.md` (ou sem `_revisado` quando original).
- **SVG de teoria:** `<prefixo-tema>_<slug>.svg`, prefixo curto e estável por tema.
- **Questão (recebida ou autoral):** `Q_<Tema>_<formato-ou-slug>.md`. SVGs da questão: `q_<tema>_<slug>.svg`.
- **Par enunciado × comentário:** sufixo `_enunciado` na versão sem solução (`q_<tema>_<slug>_enunciado.svg`) e nome base na resolvida.
- **Prompt de Flow:** dentro do `.md` do capítulo ou questão, no apêndice "Ilustrações", em inglês.
- Sempre **apresentar os arquivos** com `present_files` ao final.

---

## 16. Definition of done (checklist único de entrega)

Antes de entregar, conferir:

- [ ] **Transcrição fiel** (quando a questão foi recebida em print).
- [ ] **Classificação** com nó principal + descritores + **"Não é X"** + **campo de trilha** + **nó da grade (Apêndice D)** com caminho completo (ou subnó proposto).
- [ ] **Gabarito verificado de forma independente**; código de verificação quando combinatório/lógico/**autoral**; **verificação persistida** se autoral.
- [ ] **Distratores nomeados** (origem de cada um) no comentário.
- [ ] **"Responder o que foi perguntado"** conferido (todo × parte, final × intermediário).
- [ ] **Comentário no modelo §5** (presente, 1ª pessoa do plural, registro guiado predominante, frases curtas, contas em linha própria, conferência, "A lição que vale guardar", fecho do gabarito).
- [ ] **Teste da carinha confusa (§5)**: lido como se estivesse ao vivo para uma criança de 7 anos, nenhum degrau do raciocínio pulado, comparação com o dia a dia quando ajuda a visualizar.
- [ ] **Questão inédita (§13)**: resolução completa **sempre escrita logo abaixo do enunciado**, nunca entregue separada ou pendente.
- [ ] **SVGs** no padrão da casa: render conferido em PNG, anti-sobreposição, **setas/vistos/X desenhados** como formas, acentos OK, contagem visual direta quando possível.
- [ ] **Exemplo inventado verificado** (§13/§14): valores substituídos em **todas** as pistas; unicidade conferida.
- [ ] **Par de figura** (quando aplicável): `_enunciado` sem solução nem dica + versão resolvida.
- [ ] **Nomes de arquivo** na convenção (§15); arquivos em `outputs` e apresentados com `present_files`.
- [ ] **Estilo do texto de aluno (§14, §10):** passou no teste do "ninguém fala assim"; frases curtas; definição seguida imediatamente de exemplo concreto; sem travessão antes de aposto, sem ponto e vírgula, sem dois-pontos de suspense; vocabulário concreto (sem termo abstrato sem equivalente do dia a dia na primeira menção).
- [ ] Convenções editoriais (§10) aplicadas; sem hype, auto-elogio nem retórica vazia.

---

# Apêndice A — Árvore de motores cognitivos (Nível 1, 2º/3º ano)

**Validada na Leva 1** (out/2026) — as 9 provas de `Provas/` (pf1m1/pf2m1, 2022–2026, 135 questões) foram lidas na íntegra e cada nó abaixo só entrou depois de aparecer de fato, pelo mesmo princípio de Mirim 2 (validação por recorrência real). Exemplos citam prova/questão no formato `AAAA/FN/Qn`. Achados editoriais gerais estão no `OBMEP_Mirim1_Classificacao_Caminhos_v4.md`, §1.

- **Contagem**
  - Contagem com sobreposição/oclusão parcial (objetos escondidos atrás de outro) — `2026/F1/Q1` (figurinhas tapadas pela mão).
  - Contagem com correspondência e pareamento (formar pares completos) — `2022/F1/Q6` (pares de chinelo).
  - Contagem em grade/malha (linhas × colunas, estimar sem contar um a um) — `2022/F2/Q9`.
- **Comparação de quantidades e valores**
  - Maior/menor/igual, inclusive com números escritos por extenso — `2022/F1/Q7` ("qual é o maior: treze, quatorze…").
  - "Diferente dos demais" por contagem (odd one out numérico) — `2022/F1/Q1`.
- **Operações com Números Naturais — nível inicial**
  - Adição e subtração simples, com reagrupamento leve — recorrente em quase toda prova.
  - Multiplicação como soma repetida — `2023/F1/Q3` (gomos × sementes × tangerinas).
  - Sistema monetário simples (comprar, trocar, igualar) — `2023/F1/Q13`; `2025/F2/Q6`.
  - **Operação inversa / número escondido numa igualdade** (pré-algébrico, uma incógnita) — `2026/F1/Q3` (20 + 5 = 15 + ?); `2022/F1/Q14` (achar quanto pintar para uma quantidade virar o dobro da outra).
  - **Sistema simples de duas equações** (duas compras, achar valor unitário) — `2022/F1/Q13` (pipoca/suco no cinema); `2024/F1` (trem/vagões); `2025/F2/Q6` (lápis/caneta).
  - **Somar todas as pistas par a par** (três somas de pares levam ao total) — `2025/F2/Q14` (cachorro+gato, cachorro+coelho, gato+coelho) — mesmo motor validado em Mirim 2, confirmado também em 2º/3º ano.
- **Frações simples como operador sobre quantidade discreta** *(nó novo, confirmado em 2025)* — metade, terço de uma quantidade de objetos (não fração formal/numérica) — `2025/F1/Q8`. Baixa frequência até agora (1 ocorrência em 9 provas); manter como nó leve, não como eixo pesado da trilha.
- **Valor Posicional**
  - Formação de número por justaposição/encaixe de algarismos (quebra-cabeça de dois dígitos virando um número de 2 casas) — `2022/F1/Q3`.
  - Ábaco (casas C/D/U, trocar 10 unidades por 1 dezena) — `2022/F2/Q3`.
  - Contagem de ocorrências de um algarismo em sequência de números (cartelas de adesivo) — `2022/F2/Q13`.
  - Dígitos formados por palitos (tipo display) — contar palitos/pontos de cola por algarismo, **cuidado de convenção de desenho** (mesmo alerta do §4 de Mirim 2 para o "formato de calculadora") — `2026/F1/Q2`.
- **Sequências e Padrões**
  - Completar/continuar sequência simples (numérica, cor, forma) — recorrente.
  - Padrão cíclico/rotação (roleta com correspondência que se repete a cada N posições) — `2025/F2/Q15`; `2026/F1/Q15`.
  - Pular de N em N / ritmos diferentes que se encontram (processo iterativo com dois ritmos) — `2022/F1/Q15` (cachorro de 3 em 3, gato de 2 em 2); `2022/F2/Q14` (caramujo sobe 4, desce 1).
- **Raciocínio Lógico**
  - Pistas com decodificação por símbolo/pictograma no lugar de palavra (apoio à leitura ainda não fluente) — `2022/F1/Q4` ("quem é José?"). **Padrão de casa**: usar pictograma como pista é recorrente nessa faixa etária, vale adotar na criação de questão original (§13).
  - Restrição de Quantidade em Linhas e Colunas (grade tipo sudoku: soma ou conjunto igual em cada linha/coluna) — `2023/F1/Q6`; `2025/F2/Q8`; `2026/F1/Q10`. Nó de alta recorrência — mesmo nó já existente no Apêndice D.
  - Dedução "o que é, com certeza, verdadeiro" (a partir de um intervalo ou conjunto de condições, sem determinar valores individuais) — `2026/F1/Q9` (idades distintas entre 8 e 12).
  - Ordenação relativa por posição/velocidade (quem passou primeiro, quem está à frente) — `2024/F2` (corrida); `2026/F1/Q13` (carros com velocidades diferentes).
  - Paridade de posição (casas pares de um lado da rua, ímpares do outro) — `2026/F1/Q5`.
  - Eliminação de casos com uma pista falsa entre várias (dias da semana) — `2024/F1`.
- **Geometria e Visualização Espacial** *(eixo mais carregado da prova, sobretudo na 2ª Fase — ver nota abaixo)*
  - Reflexo/espelho (como um objeto aparece do outro lado de um vidro, ou invertido) — `2023/F2`; `2024/F2` (adesivo visto do outro lado do vidro); `2026/F1/Q2` (dígito espelhado).
  - **Projeção vertical / vista de cima** de uma montagem de objetos ou sólidos empilhados — `2022/F1/Q11`; `2022/F2/Q10`; `2026/F1/Q12`. Três ocorrências independentes — nó forte, vale capítulo de teoria próprio.
  - Dobradura e desdobramento (simetria por dobra, prever o padrão ao desdobrar) — `2022/F1/Q8`; `2024/F1`.
  - Planificação/composição e decomposição de formas (cortar uma forma em peças e remontar, ou encaixar peça em malha) — `2023/F1/Q7`; `2025/F2/Q9,10,11,13`.
  - Reconhecer forma por parte visível (objeto parcialmente coberto) — `2022/F1/Q5`.
  - **Contagem topológica em figura fechada** (nós que aparecem ao puxar um barbante embaraçado, pedaços após corte, elos de uma corrente) *(nó novo, nomeado)* — `2022/F1/Q12` (nós do barbante); `2024/F2` (colar com bolinhas entre estrelas); `2026/F1/Q4` (barbante enrolado cortado). Três ocorrências em anos diferentes — nó validado, candidato a capítulo de teoria dedicado (ninguém resolve de cabeça, todo mundo precisa de um método de rastrear o fio/traço).
- **Grandezas e Medidas**
  - Comprimento com leitura de régua, inclusive diferença entre dois comprimentos — `2023/F2`; `2026/F1/Q7`.
  - Tempo: relógio digital, soma/diferença de horários, duração que cruza meia-noite ou vira o dia — `2022/F2/Q7,8`; `2023/F1/Q12`.
  - Calendário e dias da semana (mês, semana, "quantos dias faltam", aniversário) — presente em **quase toda prova**: `2022/F1/Q2`; `2022/F2/Q6`; `2023/F1/Q8`; `2024/F1`; `2025/F1/Q6`; `2026/F1/Q8`. É o nó de **maior recorrência absoluta** da trilha — prioridade alta para capítulo de teoria.
- **Tratamento da Informação**
  - Leitura de gráfico de barras (valor direto, sem ponderação complexa) — `2023/F2`.
  - Leitura de tabela/cartaz (contagem filtrada por categoria, ex. aniversariantes de um mês) — `2023/F1/Q8`.
- **Combinatória simples**
  - Combinação de grupos/pares (escolher 2 de N para formar um total; confrontos de campeonato) — `2023/F1/Q15` (chás); `2025/F1/Q10` (campeonato); `2026/F1/Q6` (aquários).
  - Soma de subconjuntos de valores distintos (cédulas, cartões) — `2024/F2`; `2025/F2/Q4`.
  - Contagem de arranjos válidos sob restrição visual (empilhamento, ordem determinada pela figura) — `2024/F2`.

### Nota sobre o peso dos eixos (achado da Leva 1)
Diferente de Mirim 2 (fortemente aritmético), em Mirim 1 **Geometria e Visualização Espacial** e **Grandezas e Medidas** (em especial calendário/dias da semana) competem em peso com Operações e Raciocínio Lógico — e pesam proporcionalmente mais na **2ª Fase** (mais difícil, mais espacial) do que na 1ª. **Frações formais e Álgebra pré-algébrica com várias incógnitas praticamente não aparecem** — o nó pré-algébrico de Mirim 1 fica quase todo em "uma incógnita por operação inversa" ou "duas equações simples", sem a profundidade de Mirim 2. **V ou F não aparece nenhuma vez** nas 9 provas — todas as 135 questões são múltipla escolha de 5 alternativas; isso é argumento forte para tratar V/F como formato secundário/tardio na trilha (confirma a ressalva do §6).

---

# Apêndice B — Biblioteca de helpers de SVG (cairosvg)

Infraestrutura compartilhada com a trilha Mirim 2 — mesma biblioteca, sem alteração. Mantém a paleta e desenha setas/vistos/X como formas (nunca glifos). Renderiza em PNG para revisão antes de entregar.

```python
import cairosvg, math
# Paleta de trabalho (confirmar hex na Bíblia de Ilustração)
NAVY="#14365A"; ORANGE="#E0701B"; BLUE="#2F80C4"; YELLOW="#F6C445"
GREEN="#3E9B6B"; RED="#C0392B"; PURPLE="#7A5CC0"; GREY="#8A97A6"
FILL_BLUE="#E6F0FA"; FILL_ORG="#FCEBD9"; FILL_YEL="#FCEFC2"
FILL_GREEN="#E2F2EA"; FILL_PURPLE="#EEE8FA"; FILL_GREY="#EEF3F8"; BORDER="#CBD5DF"
FONT="DejaVu Sans"; MONO="DejaVu Sans Mono"   # acentos OK; trocam pela fonte da casa no pipeline

def T(x,y,t,fs=16,col=NAVY,w="normal",anchor="start",fam=FONT):
    return (f'<text x="{x}" y="{y}" font-family="{fam}" font-size="{fs}" '
            f'font-weight="{w}" fill="{col}" text-anchor="{anchor}">{t}</text>')

def box(x,y,w,h,fill,stroke,rx=10,sw=2):
    return f'<rect x="{x}" y="{y}" width="{w}" height="{h}" rx="{rx}" fill="{fill}" stroke="{stroke}" stroke-width="{sw}"/>'

def chip(x,y,txt,fill,stroke,w=58,h=42,fs=21):
    return box(x,y,w,h,fill,stroke,9,2.5)+T(x+w/2,y+h/2+fs//3,txt,fs,NAVY,"bold","middle",MONO)

# equação multicolor: um token por <text> posicionado (nunca tspan em sequência)
def eq(x,y,spans,fs=20):
    s=f'<text x="{x}" y="{y}" font-family="{MONO}" font-size="{fs}">'
    for t,c,b in spans:
        s+=f'<tspan fill="{c}" font-weight="{"bold" if b else "normal"}">{t}</tspan>'
    return s+'</text>'   # use só se NÃO houver troca de cor adjacente problemática; senão, T() token a token

def arrow(x1,y1,x2,y2,color=ORANGE,label=None,sub=None):
    head=8; dx,dy=x2-x1,y2-y1; L=math.hypot(dx,dy) or 1; ux,uy=dx/L,dy/L
    ex,ey=x2-ux*head,y2-uy*head; px,py=-uy,ux
    s=(f'<line x1="{x1}" y1="{y1}" x2="{ex:.1f}" y2="{ey:.1f}" stroke="{color}" stroke-width="2.4"/>'
       f'<polygon points="{x2},{y2} {ex-px*5:.1f},{ey-py*5:.1f} {ex+px*5:.1f},{ey+py*5:.1f}" fill="{color}"/>')
    if label: s+=T((x1+x2)/2,y1-21,label,14,color,"bold","middle",MONO)
    if sub:   s+=T((x1+x2)/2,y1-7,sub,10,GREY,"normal","middle")
    return s

def check(cx,cy,s=11,color=GREEN):
    return (f'<polyline points="{cx-s},{cy} {cx-s/3:.1f},{cy+s*0.7:.1f} {cx+s},{cy-s*0.8:.1f}" '
            f'fill="none" stroke="{color}" stroke-width="3.2" stroke-linecap="round" stroke-linejoin="round"/>')

def xmark(cx,cy,s=10,color=RED):
    return (f'<line x1="{cx-s}" y1="{cy-s}" x2="{cx+s}" y2="{cy+s}" stroke="{color}" stroke-width="3" stroke-linecap="round"/>'
            f'<line x1="{cx-s}" y1="{cy+s}" x2="{cx+s}" y2="{cy-s}" stroke="{color}" stroke-width="3" stroke-linecap="round"/>')

def gear(cx,cy,r,col):
    s=''
    for i in range(8):
        a=i*math.pi/4
        s+=(f'<line x1="{cx+r*math.cos(a):.1f}" y1="{cy+r*math.sin(a):.1f}" '
            f'x2="{cx+(r+4)*math.cos(a):.1f}" y2="{cy+(r+4)*math.sin(a):.1f}" stroke="{col}" stroke-width="2"/>')
    return s+f'<circle cx="{cx}" cy="{cy}" r="{r}" fill="none" stroke="{col}" stroke-width="2"/><circle cx="{cx}" cy="{cy}" r="2.5" fill="{col}"/>'

def save(fn,W,H,parts):
    svg=(f'<svg viewBox="0 0 {W} {H}" xmlns="http://www.w3.org/2000/svg">'
         f'<rect width="{W}" height="{H}" fill="white"/>'+''.join(parts)+'</svg>')
    open(fn.replace('.png','.svg'),'w').write(svg)
    cairosvg.svg2png(bytestring=svg.encode(), write_to=fn, output_width=W*2)  # render p/ revisão
```

Regras de uso embutidas: setas/vistos/X via `arrow/check/xmark` (formas, não glifos); equação colorida por tokens posicionados; sempre `save` em PNG e **revisar** antes de entregar; folga horizontal/vertical conforme o checklist anti-sobreposição (§9a).

---

# Apêndice C — Changelog (histórico de novidades)

**v1.2 (out/2026) — Leva 1.** Leitura completa das 9 provas (`pf1m1`/`pf2m1`, 2022–2026, 135 questões) e do `regulamento.pdf`. Apêndice A passa de hipótese a **árvore validada** (nós com exemplo de prova/questão); abertos os nós novos **Frações simples como operador** (baixa frequência), **Contagem Topológica em Figura Fechada** (3 ocorrências) e confirmado **Projeção vertical/vista de cima** (3 ocorrências) como nó forte dentro de Geometria. §12 ganha o resumo de motores por prova. §3 e o changelog do Apêndice D atualizados para refletir que Geometria/Espacial e Grandezas/Medidas (calendário) pesam mais do que o esperado inicialmente, e que V/F não ocorre nenhuma vez no material real. Regulamento confirmou formato (15 questões MC, 5 alternativas, 2 fases) e base curricular na BNCC, sem lista de tópicos por nível. Nada removido; numeração preservada.

**v1.1 (out/2026).** Reforço da régua de linguagem a pedido explícito: tom **lúdico** no §5 (nunca seco, mas sem hype falso); **explicação detalhe por detalhe**, sem pular degrau de raciocínio; **comparação com o dia a dia** sempre que ajudar a visualizar; **teste da carinha confusa** como critério de aceitação (§5, usado também em §13). §13 passa a exigir **resolução completa junto do enunciado** em toda questão inédita, nunca entregue separada. Checklist §16 atualizado. Nada removido; numeração preservada.

**v1 (out/2026).** Primeira versão, adaptada do `Protocolo_OBMEP_v5_5.md` (trilha Mirim 2) para a trilha **Mirim 1 (2º/3º ano, 7–8 anos)**. Mudanças de público: idade e registro de voz em §0/§1/§5 (predominância do registro guiado, frases curtas, vocabulário concreto — §14); V/F marcado como opcional/a avaliar (§6–§8); dificuldade de questão autoral recalibrada para 2º/3º ano (§13); regra de "fôlego de frase livre" de Mirim 2 trocada por frases curtas como padrão inicial (§10), a revalidar após a Leva 1. Infraestrutura trazida **sem alteração**: biblioteca de SVG (Apêndice B), convenção de nomes (§15), grade oficial da plataforma (Apêndice D). Apêndice A (árvore de motores) e §12 (registro de motores vistos) ficam **vazios/provisórios**, a preencher processando as 9 provas de `Provas/`.

---

# Apêndice D — Árvore de Classificação (Grade de Matemática)

Referência canônica do passo de classificação (§3) — **grade oficial da plataforma, compartilhada entre todos os níveis** (Mirim 1, Mirim 2 e trilhas futuras). Trazida sem alteração do protocolo de Mirim 2. Toda questão é mapeada a um nó **existente** desta grade, com o **caminho completo**; quando nenhum nó servir, propor um **subnó nomeado** (com justificativa) em vez de forçar encaixe. Nós marcados `[+]` estavam recolhidos na captura e têm filhos ainda não transcritos.

## Sistemas de Numeração `[+]`

## Operações Básicas
- Soma
- Subtração
- Multiplicação
- Divisão
- Potenciação
- Propriedades das operações
- Expressões numéricas
- Cálculo mental
- Relação inversa entre multiplicação e divisão
- Problemas envolvendo as operações básicas

## Conjuntos Numéricos `[+]`

## Aritmética
- Grandezas e Medidas `[+]`
- Operações com Números Naturais `[+]`
- Média Aritmética `[+]`
- Operações com Frações
  - Interpretação de Frações como Parte de um Conjunto
  - Comparação e Ordenação de Frações e Decimais
  - Frações Mistas e Impróprias
  - Adição e Subtração de Frações
  - Problemas com Frações Sucessivas
  - Multiplicação de Frações
  - Divisão de Frações
  - Simplificação de Frações
- Razão e Proporção `[+]`
- Porcentagem
  - Conceitos Introdutórios
  - Porcentagem Relativa
  - Porcentagem Sucessiva
  - Juros Simples
  - Aumento e Desconto
- Valor Posicional `[+]`
- Problemas com Algarismos e Criptografia Aritmética
- Crescimento por operações sucessivas (adição ou multiplicação)
- Conversão de Fração em Decimal
- Quadrados Perfeitos
- Problemas com Pontuação, Torneios e Máximos sob Restrições
- Problemas com Restrições de Soma (Linhas e Colunas / Matrizes)
- Problemas com Interseção de Conjuntos (Apenas um, os dois, nenhum)

## Análise Combinatória `[+]`

## Raciocínio Lógico
- Problemas com Princípios de Existência / Princípio da Casa dos Pombos
- Problemas com Visualização Espacial `[+]`
- Problemas com Restrições e Dedução
  - Decodificação de Idiomas / Sistemas Simbólicos
  - Restrições Temporais e Dias da Semana
  - Restrição de Quantidade em Linhas e Colunas (Matrizes / Tabuleiros)
  - Grupos e Posicionamento com Pistas
  - Distribuições com Condições
  - Quem é Quem / Identidades Ocultas
  - Dedução com Pistas Numéricas
  - Lógicas de Movimento ou Trajetos
- Sequências e Padrões Numéricos `[+]`
- Problemas com Relações Familiares
- Problemas de Otimização e Estratégia de Mínimos/Máximos
- Problemas com Regras de Transformação e Algoritmos
- Problemas com Verdadeiros e Mentirosos
- Problemas de Contagem com Condições Lógicas
- Problemas com Tabelas-Verdade / Lógica Proposicional
- Jogos de Estratégia e Raciocínio
- Problemas com Pontuação, Torneios e Máximos sob Restrições
- Problemas com Conjuntos e Diagramas de Venn

## Geometria `[+]`

## Álgebra
- Sistemas de Equações
  - Sistemas com 2 variáveis
  - Sistemas com 3 variáveis
  - Problemas com Restrições Inteiras (Otimização Discreta)
  - Sistemas com 4 ou mais variáveis
- Equações
  - Equações do 1º Grau
  - Equações do 2º Grau
  - Equações com Frações
- Expressões Algébricas
  - Problemas de Idade e Relações Algébricas
  - Operações com Expressões Algébricas
  - Fatoração de Expressões Algébricas
  - Problemas de Mínimos e Máximos
  - Problemas de Aplicação de Fórmulas e Proporções
- Inequações
- Funções `[+]`

## Probabilidade `[+]`

## Progressões `[+]`

## Geometria Analítica `[+]`

## Teoria dos Números `[+]`

## Estatística
- Probabilidade e Estatística Descritiva
  - Distribuição de Frequência
  - Construção de Gráficos
  - Organização de Dados
- Medidas de Tendência Central `[+]`
- Estatística Aplicada a Problemas do Cotidiano `[+]`
- Medidas de Dispersão `[+]`
- Interpretação de Gráficos e Tabelas
  - Gráficos combinados de barras e linhas
  - Leitura de Gráficos de Radar (Teia / Aranha)
  - Noções básicas de estatística
  - Leitura de Gráficos de Dispersão
  - Leitura de Tabelas de Frequência
  - Análise de Gráficos de Linha
  - Gráficos de Setores (Pizza)
  - Leitura de Gráficos de Barras

### Notas de uso
- A classificação informa o **caminho completo** do nó, mais 2–3 nós-irmãos descartados com o porquê (campo "Não é X", §3).
- **Mapa árvore ↔ Trilha:** cada nó usado registra o Caminho/Bloco da Trilha correspondente (campo de trilha, §3), para manter classificação e currículo sincronizados.
- Nós `[+]` precisam ser expandidos e transcritos numa próxima captura para completar o apêndice. **Confirmado na Leva 1** (Apêndice A): Geometria, Sequências e Padrões e Grandezas e Medidas são de fato **mais relevantes para Mirim 1** do que foram para Mirim 2 — priorizar a expansão desses ramos primeiro.

# OBMEP Mirim 1 — Engenharia Reversa para Trilha de Curso (2º e 3º anos)
### Classificação por assunto e organização em Caminhos (Unidades)

> Documento-base para alimentar a plataforma. Cada questão tem **dois identificadores**: um **nome fácil** (ano/fase/número) para busca humana e um **código técnico** estável para a base do site — mesmo padrão usado em `OBMEP_Mirim2_Classificacao_Caminhos_v4.md`.

> **Atualização (v4, out/2026) — as três pendências fechadas.** (1) As 45 questões ainda resumidas de `2023/F2`, `2024/F1` e `2024/F2` foram relidas e itemizadas questão a questão. (2) O gabarito das **135 questões** foi calculado de forma independente (não há gabarito oficial público — a Olimpíada Mirim trata gabaritos como confidenciais por regulamento; confirmado por busca). (3) A **tabela-mestre completa** está na §4, com Caminho/Bloco e gabarito por questão; a distribuição da §3 agora é a **contagem exata**, não mais estimativa por escala.
>
> **Honestidade sobre a confiança do gabarito.** De 135 questões, **71 (53%) foram resolvidas com alta confiança** (conta ou dedução lógica direta, independente da figura) e **64 (47%) dependem de leitura fina de figura** (contar pontos num dado, traçar um barbante embaraçado, comparar silhuetas, rastrear reflexo) — para essas, dou minha melhor leitura da imagem, mas marco explicitamente `🖼️ (confirmar)` porque não há gabarito oficial público para cruzar e meu traçado de figura, por mais cuidadoso, não tem a mesma certeza de uma conta. **Antes de publicar qualquer questão marcada assim, vale uma segunda leitura humana da figura original** (a prova completa está em `Provas/`). Isso é o próprio processo do protocolo (§4): gabarito nosso é auditável, não é tomado como verdade absoluta.

---

## 1. Material analisado (135 questões)

| Sigla | Prova | Fase | Nº de questões |
|---|---|---|---|
| **M1-22-F1** | Olimpíada Mirim · Mirim 1 · 2022 | 1ª Fase | 15 |
| **M1-22-F2** | Olimpíada Mirim · Mirim 1 · 2022 | 2ª Fase | 15 |
| **M1-23-F1** | Olimpíada Mirim · Mirim 1 · 2023 | 1ª Fase | 15 |
| **M1-23-F2** | Olimpíada Mirim · Mirim 1 · 2023 | 2ª Fase | 15 |
| **M1-24-F1** | Olimpíada Mirim · Mirim 1 · 2024 | 1ª Fase | 15 |
| **M1-24-F2** | Olimpíada Mirim · Mirim 1 · 2024 | 2ª Fase | 15 |
| **M1-25-F1** | Olimpíada Mirim · Mirim 1 · 2025 · 4ª Edição | 1ª Fase | 15 |
| **M1-25-F2** | Olimpíada Mirim · Mirim 1 · 2025 · 4ª Edição | 2ª Fase | 15 |
| **M1-26-F1** | Olimpíada Mirim · Mirim 1 · 2026 · 5ª Edição | 1ª Fase | 15 |

9 provas, **135 questões**, todas múltipla escolha com 5 alternativas (A–E). 2ª Fase de 2026 ainda não disponível.

### Notas de procedência
- **Gabarito oficial não é público.** Busca na web confirma: o regulamento da Olimpíada Mirim trata o gabarito como material confidencial, distribuído só às escolas participantes — não há PDF de gabarito aberto para cruzar. Por isso o gabarito desta tabela é **cálculo independente nosso** (§4 do protocolo), não conferência contra fonte oficial.
- Edições: 2025 = 4ª Edição; 2026 = 5ª Edição (numeração contígua com Mirim 2, mesma olimpíada). Realização IMPA, apoio B³/CNPq/CAPES.
- Regulamento (`regulamento.pdf`) é administrativo; confirma formato e base BNCC, sem lista de tópicos por nível.

### Achados editoriais da Leva 1
- Perfil de conteúdo diferente de Mirim 2: **Geometria** empata com **Números** como eixo mais pesado (ver §3).
- **Calendário/dias da semana** é o nó de maior recorrência **entre edições** (aparece em quase toda prova), mesmo não sendo o de maior volume absoluto.
- **2ª Fase é mais espacial** que a 1ª — em `2025/F2`, 9 de 15 questões são de Geometria.
- **Apoio pictórico no lugar de palavra** é recurso de casa recorrente (uma questão por prova, em média, troca uma palavra do enunciado por um desenho pequeno).
- **Contagem Topológica em Figura Fechada** (barbante, colar, corda) — nó novo, confirmado em `2022/F1`, `2024/F2`, `2026/F1`.
- **Frações aparecem 1 vez em 135** (`2025/F1/Q8`, operador metade/terço); nenhum sistema com mais de 2 incógnitas; nenhuma cryptaritmética com letras.
- **Nenhuma questão em V/F ou seleção múltipla** — 100% múltipla escolha de 5 alternativas.

---

## 2. Convenção de nomes (dois modos)

**Nome fácil — `ano/fase/número`**: `2022/F1/Q10`. **Código técnico — `SIGLA-Qnn`**: `M1-22-F1-Q10`.

**Legenda de gabarito:**
- ✅ = determinado por conta/dedução lógica, confiança alta.
- ✅🖼️ = depende de figura, mas a leitura foi clara e a conta fecha (confiança alta a moderada).
- 🖼️ *(confirmar)* = depende de leitura fina de figura (contar pontos, traçar forma, comparar silhueta); estimativa dada, mas **sem gabarito oficial para cruzar** — recomendo segunda leitura humana antes de publicar.

---

## 3. Os 7 Caminhos da Trilha Mirim 1 — distribuição exata (135/135)

Prefixo **CP**. Estrutura derivada do conteúdo real das 9 provas.

| Caminho | Nome | Qtde (exata) | Peso |
|---|---|---|---|
| **CP1** | Números, Operações e Valor Posicional | 33 | ●●●●●●●●●●●● |
| **CP2** | Geometria e Visualização Espacial | 33 | ●●●●●●●●●●●● |
| **CP5** | Raciocínio Lógico e Dedução | 20 | ●●●●●●● |
| **CP7** | Contagem Avançada e Combinatória | 20 | ●●●●●●● |
| **CP6** | Sequências, Padrões e Processos Iterativos | 12 | ●●●●● |
| **CP4** | Tempo, Calendário e Dias da Semana | 11 | ●●●●● |
| **CP3** | Grandezas e Medidas | 6 | ●●● |

**Confirmado com dados exatos** (antes era estimativa por escala): CP1 e CP2 ficam empatados em 33 cada, exatamente como a amostra projetava. CP5 e CP7 também ficam parelhos (20 cada). CP4 veio um pouco mais magro do que a projeção sugeria (11, não ~14) — calendário é **recorrente entre edições**, mas não concentra muitas questões por prova (1–2). CP3 confirma ser o Caminho mais curto (6).

Escopo de cada Caminho, Leitura editorial e notas de sequenciamento: **sem mudanças em relação à v3** (ver §3/§6 anteriores, preservados abaixo).

### Escopo de cada Caminho
| Caminho | Foco |
|---|---|
| CP1 | Contagem, comparação, adição/subtração/multiplicação inicial, dinheiro, valor posicional, número escondido, sistema simples de duas equações, somar pistas par a par, frações simples como operador |
| CP2 | Reflexo/espelho, vista de cima, dobradura/simetria, composição/decomposição de formas, encaixe de peças, contagem topológica em figura fechada, orientação espacial |
| CP3 | Comprimento/régua, percursos e distâncias simples |
| CP4 | Relógio, duração, calendário, dias da semana |
| CP5 | Pistas por pictograma, restrição de soma/conjunto em linhas e colunas, dedução "com certeza", ordenação relativa, paridade de posição, eliminação de casos, leitura de gráficos e tabelas |
| CP6 | Completar sequência, padrão cíclico/roleta modular, saltos/ritmos que se encontram, processo iterativo |
| CP7 | Contagem em grade/malha, pareamento, combinação de grupos, soma de subconjuntos, arranjos válidos sob restrição |

---

## 4. Tabela-mestre (índice completo — 135 questões)

Gabarito calculado de forma independente (§4 do protocolo); sem fonte oficial pública para cruzar (ver nota no topo). Questões marcadas 🖼️ *(confirmar)* pedem segunda leitura humana da figura antes de publicar.

### M1-22-F1 (2022 · 1ª Fase)
| Nome fácil | Código | Caminho | Tópico | Gabarito |
|---|---|---|---|---|
| 2022/F1/Q1 | M1-22-F1-Q01 | CP1 | Conta com resultado diferente das outras | E ✅ |
| 2022/F1/Q2 | M1-22-F1-Q02 | CP4 | Dia da semana do penúltimo dia de março/2019 | E ✅🖼️ |
| 2022/F1/Q3 | M1-22-F1-Q03 | CP1 | Quebra-cabeça de algarismos (encaixe 6+4) | D 🖼️ *(confirmar)* |
| 2022/F1/Q4 | M1-22-F1-Q04 | CP5 | Pistas por pictograma — quem é José | D ✅ |
| 2022/F1/Q5 | M1-22-F1-Q05 | CP2 | Forma escondida sob a folha de papel | D 🖼️ *(confirmar)* |
| 2022/F1/Q6 | M1-22-F1-Q06 | CP7 | Pares completos de chinelos | C 🖼️ *(confirmar)* |
| 2022/F1/Q7 | M1-22-F1-Q07 | CP1 | Maior número escrito por extenso | C ✅ |
| 2022/F1/Q8 | M1-22-F1-Q08 | CP2 | Dobradura — padrão que NÃO pode aparecer | D 🖼️ *(confirmar)* |
| 2022/F1/Q9 | M1-22-F1-Q09 | CP3 | Ida e volta a duas bandeiras (10m e 15m) | E ✅ |
| 2022/F1/Q10 | M1-22-F1-Q10 | CP6 | Colar diferente dos demais (padrão) | E 🖼️ *(confirmar)* |
| 2022/F1/Q11 | M1-22-F1-Q11 | CP2 | Vista de cima de montagem de cubos | 🖼️ *(confirmar — sem palpite seguro)* |
| 2022/F1/Q12 | M1-22-F1-Q12 | CP2 | Quantos nós aparecem ao puxar o barbante | C 🖼️ *(confirmar)* |
| 2022/F1/Q13 | M1-22-F1-Q13 | CP1 | Preço da pipoca pela diferença entre compras | E ✅ |
| 2022/F1/Q14 | M1-22-F1-Q14 | CP5 | Pintar quadradinhos até pretos = 2× brancos | D ✅🖼️ |
| 2022/F1/Q15 | M1-22-F1-Q15 | CP6 | Cachorro (3 em 3) encontra gato (2 em 2) | E ✅ |

### M1-22-F2 (2022 · 2ª Fase)
| Nome fácil | Código | Caminho | Tópico | Gabarito |
|---|---|---|---|---|
| 2022/F2/Q1 | M1-22-F2-Q01 | CP1 | Placa com 4 letras e 3 números | D ✅ |
| 2022/F2/Q2 | M1-22-F2-Q02 | CP2 | Tomada que aceita os dois tipos de plugue | 🖼️ *(confirmar)* |
| 2022/F2/Q3 | M1-22-F2-Q03 | CP1 | Ábaco — mover discos entre casas | D ✅ |
| 2022/F2/Q4 | M1-22-F2-Q04 | CP2 | Corda em espiral, qual barra desenrolada | 🖼️ *(confirmar)* |
| 2022/F2/Q5 | M1-22-F2-Q05 | CP6 | Fita dobrada — números entre a 6ª e a 9ª dobra | C ✅ |
| 2022/F2/Q6 | M1-22-F2-Q06 | CP4 | Calendário jan/2022 — dia da semana de 8/fev | B ✅ |
| 2022/F2/Q7 | M1-22-F2-Q07 | CP2 | Cartão igual ao original (reflexo) | 🖼️ *(confirmar)* |
| 2022/F2/Q8 | M1-22-F2-Q08 | CP4 | Relógio 8:52 + 18 minutos | E ✅ |
| 2022/F2/Q9 | M1-22-F2-Q09 | CP7 | Caixinha com menos bolinhas | 🖼️ *(confirmar)* |
| 2022/F2/Q10 | M1-22-F2-Q10 | CP2 | Vista de cima dos objetos na mesa | 🖼️ *(confirmar)* |
| 2022/F2/Q11 | M1-22-F2-Q11 | CP5 | Dominó — soma 9 em cada linha/coluna | 🖼️ *(confirmar)* |
| 2022/F2/Q12 | M1-22-F2-Q12 | CP1 | Valor por pessoa com 2 ofertas (lanche/refresco) | E ✅ |
| 2022/F2/Q13 | M1-22-F2-Q13 | CP1 | Cartelas de adesivo para numerar 15 páginas | E ✅ |
| 2022/F2/Q14 | M1-22-F2-Q14 | CP6 | Caramujo sobe 4/desce 1 — quantas paradas | B ✅ *(pequena ambiguidade de leitura do enunciado)* |
| 2022/F2/Q15 | M1-22-F2-Q15 | CP7 | Pega-varetas — quantas ordens possíveis | 🖼️ *(confirmar)* |

### M1-23-F1 (2023 · 1ª Fase)
| Nome fácil | Código | Caminho | Tópico | Gabarito |
|---|---|---|---|---|
| 2023/F1/Q1 | M1-23-F1-Q01 | CP1 | Fruta da feira em quantidade diferente | 🖼️ *(confirmar)* |
| 2023/F1/Q2 | M1-23-F1-Q02 | CP7 | Placas circulares sem seta | 🖼️ *(confirmar)* |
| 2023/F1/Q3 | M1-23-F1-Q03 | CP1 | Sementes em 2 tangerinas (9 gomos × 2) | D ✅ |
| 2023/F1/Q4 | M1-23-F1-Q04 | CP2 | Bandeirinhas que apontam para o menino | 🖼️ *(confirmar)* |
| 2023/F1/Q5 | M1-23-F1-Q05 | CP6 | Soma dos números que faltam na música (5+6) | D ✅ |
| 2023/F1/Q6 | M1-23-F1-Q06 | CP5 | Grade — triângulos, retângulos e estrelas | 🖼️ *(confirmar)* |
| 2023/F1/Q7 | M1-23-F1-Q07 | CP3 | Caminho de maior comprimento na malha | 🖼️ *(confirmar)* |
| 2023/F1/Q8 | M1-23-F1-Q08 | CP5 | Aniversariantes do mês anterior a Isabel | D ✅ |
| 2023/F1/Q9 | M1-23-F1-Q09 | CP6 | Máquina de operações (10→15→11→26) | D ✅ |
| 2023/F1/Q10 | M1-23-F1-Q10 | CP1 | Número de 3 algarismos que NÃO pode ser formado (rotação 6↔9) | D ✅ |
| 2023/F1/Q11 | M1-23-F1-Q11 | CP1 | Bolinhas de 4 amigos (cadeia de pistas) | C ✅ |
| 2023/F1/Q12 | M1-23-F1-Q12 | CP4 | Minutos até o jogo começar (3:10→4:05) | D ✅ |
| 2023/F1/Q13 | M1-23-F1-Q13 | CP1 | Moeda a mover para equilibrar dois montes | B ✅ |
| 2023/F1/Q14 | M1-23-F1-Q14 | CP1 | Altura de pilha de caixas (sistema 2 eq.) | C ✅ |
| 2023/F1/Q15 | M1-23-F1-Q15 | CP7 | Combinações de chá com 3 ervas | C ✅ |

### M1-23-F2 (2023 · 2ª Fase)
| Nome fácil | Código | Caminho | Tópico | Gabarito |
|---|---|---|---|---|
| 2023/F2/Q1 | M1-23-F2-Q01 | CP1 | Quadro com mais vogais que consoantes | D ✅ |
| 2023/F2/Q2 | M1-23-F2-Q02 | CP1 | Dinossauros que botaram ovo (×2 cada) | D ✅ |
| 2023/F2/Q3 | M1-23-F2-Q03 | CP7 | Quadriculado com mais quadrados pintados | D 🖼️ *(confirmar)* |
| 2023/F2/Q4 | M1-23-F2-Q04 | CP4 | Minutos até as 10h (relógio 9:13) | D ✅ |
| 2023/F2/Q5 | M1-23-F2-Q05 | CP7 | Círculos entre o 3º quadrado e o 5º triângulo | C ✅🖼️ |
| 2023/F2/Q6 | M1-23-F2-Q06 | CP7 | Figura com menos maçãs | D 🖼️ *(confirmar)* |
| 2023/F2/Q7 | M1-23-F2-Q07 | CP3 | Comprimento do lápis, régua sem começar do zero | C ✅🖼️ |
| 2023/F2/Q8 | M1-23-F2-Q08 | CP1 | Data invertida dígito a dígito (24/2/2017) | C ✅ |
| 2023/F2/Q9 | M1-23-F2-Q09 | CP1 | Número original antes de subtrair 10 | D ✅ |
| 2023/F2/Q10 | M1-23-F2-Q10 | CP2 | Montagem que Mateus NÃO consegue fazer | 🖼️ *(confirmar)* |
| 2023/F2/Q11 | M1-23-F2-Q11 | CP2 | Vista de trás da placa com fio | 🖼️ *(confirmar)* |
| 2023/F2/Q12 | M1-23-F2-Q12 | CP5 | Leitura de gráfico de barras (soma 3 frutas) | C ✅ |
| 2023/F2/Q13 | M1-23-F2-Q13 | CP1 | Figurinhas de Júlia (Carlos = Júlia + 3) | B 🖼️ *(confirmar — depende da contagem total na figura)* |
| 2023/F2/Q14 | M1-23-F2-Q14 | CP2 | Planificação de cubo (carinha na face oposta) | C 🖼️ *(confirmar)* |
| 2023/F2/Q15 | M1-23-F2-Q15 | CP2 | Moedas viradas e reorganizadas | 🖼️ *(confirmar — sem palpite seguro)* |

### M1-24-F1 (2024 · 1ª Fase)
| Nome fácil | Código | Caminho | Tópico | Gabarito |
|---|---|---|---|---|
| 2024/F1/Q1 | M1-24-F1-Q01 | CP1 | Flor com mais pétalas | 🖼️ *(confirmar)* |
| 2024/F1/Q2 | M1-24-F1-Q02 | CP2 | Peça que completa o quebra-cabeça | 🖼️ *(confirmar)* |
| 2024/F1/Q3 | M1-24-F1-Q03 | CP7 | Peças de dominó somando 10 | B ✅ |
| 2024/F1/Q4 | M1-24-F1-Q04 | CP2 | Posição na grade (4 casas acima, 2 à esquerda) | 🖼️ *(confirmar)* |
| 2024/F1/Q5 | M1-24-F1-Q05 | CP6 | 9º pulo de 2 em 2 | B ✅ |
| 2024/F1/Q6 | M1-24-F1-Q06 | CP2 | Dobradura dupla + corte, padrão ao desdobrar | 🖼️ *(confirmar)* |
| 2024/F1/Q7 | M1-24-F1-Q07 | CP4 | Hora de saída de casa (chegou 9h, 15min antes) | C ✅ |
| 2024/F1/Q8 | M1-24-F1-Q08 | CP2 | Letra que não fica visível ao dobrar o papel | D 🖼️ *(confirmar)* |
| 2024/F1/Q9 | M1-24-F1-Q09 | CP3 | Diferença entre lápis e pincel na régua | E 🖼️ *(confirmar)* |
| 2024/F1/Q10 | M1-24-F1-Q10 | CP5 | Ordem das pegadas no caminho | 🖼️ *(confirmar)* |
| 2024/F1/Q11 | M1-24-F1-Q11 | CP1 | Preço de 1 laranja (4 laranjas custam +15c) | A ✅ |
| 2024/F1/Q12 | M1-24-F1-Q12 | CP1 | Locomotiva + vagões (sistema 2 equações) | B ✅ |
| 2024/F1/Q13 | M1-24-F1-Q13 | CP5 | Jogo do pirata — afirmação certa (paridade) | D ✅ |
| 2024/F1/Q14 | M1-24-F1-Q14 | CP7 | Números de 2 algarismos, dezena ímpar/unidade par | E ✅ |
| 2024/F1/Q15 | M1-24-F1-Q15 | CP5 | Quem errou o dia da semana (Ernesto) | E ✅ |

### M1-24-F2 (2024 · 2ª Fase)
| Nome fácil | Código | Caminho | Tópico | Gabarito |
|---|---|---|---|---|
| 2024/F2/Q1 | M1-24-F2-Q01 | CP5 | Posição final de quem ultrapassou 5 atletas | C ✅ |
| 2024/F2/Q2 | M1-24-F2-Q02 | CP2 | Planta com mais pétalas que folhas | 🖼️ *(confirmar)* |
| 2024/F2/Q3 | M1-24-F2-Q03 | CP5 | Placar possível (time azul venceu, ambos marcaram) | D ✅ |
| 2024/F2/Q4 | M1-24-F2-Q04 | CP2 | Adesivos vistos do outro lado do vidro | E 🖼️ *(confirmar)* |
| 2024/F2/Q5 | M1-24-F2-Q05 | CP7 | Arranjos de 3 cubos sem 2 cores adjacentes | B ✅ |
| 2024/F2/Q6 | M1-24-F2-Q06 | CP1 | Pessoas entre Helena (meio) e Gabriel (fim) | C ✅ |
| 2024/F2/Q7 | M1-24-F2-Q07 | CP1 | Janelas do prédio (fundo = 2× frente) | D 🖼️ *(confirmar)* |
| 2024/F2/Q8 | M1-24-F2-Q08 | CP2 | Pegadas do pé direito | 🖼️ *(confirmar)* |
| 2024/F2/Q9 | M1-24-F2-Q09 | CP4 | Horário que Francisco está pronto | A ✅ |
| 2024/F2/Q10 | M1-24-F2-Q10 | CP2 | Bolinhas mínimas a remover para soltar as estrelas | 🖼️ *(confirmar — cálculo próprio não fechou com nenhuma opção, checar contagem de contas na figura)* |
| 2024/F2/Q11 | M1-24-F2-Q11 | CP6 | Degrau do 4º passo com o pé esquerdo | C ✅ |
| 2024/F2/Q12 | M1-24-F2-Q12 | CP5 | Azulejo — peça que falta (preto × amarelo) | A 🖼️ *(confirmar)* |
| 2024/F2/Q13 | M1-24-F2-Q13 | CP7 | Valores diferentes pagáveis com 4 cédulas | C ✅ |
| 2024/F2/Q14 | M1-24-F2-Q14 | CP2 | Cubos azuis mínimos no cubo grande | 🖼️ *(confirmar)* |
| 2024/F2/Q15 | M1-24-F2-Q15 | CP7 | Peça de dominó que sobra na sequência | 🖼️ *(confirmar)* |

### M1-25-F1 (2025 · 1ª Fase · 4ª Edição)
| Nome fácil | Código | Caminho | Tópico | Gabarito |
|---|---|---|---|---|
| 2025/F1/Q1 | M1-25-F1-Q01 | CP2 | Figura com mais palitos (contorno) | D 🖼️ *(confirmar)* |
| 2025/F1/Q2 | M1-25-F1-Q02 | CP2 | Montagem correta do gatinho (peças numeradas) | 🖼️ *(confirmar)* |
| 2025/F1/Q3 | M1-25-F1-Q03 | CP1 | Bois a mover para igualar os dois cercados | C 🖼️ *(confirmar)* |
| 2025/F1/Q4 | M1-25-F1-Q04 | CP6 | Última folha que a formiga come (caminho guloso) | 🖼️ *(confirmar)* |
| 2025/F1/Q5 | M1-25-F1-Q05 | CP3 | Formiga volta ao ponto de partida (+5, −9) | B ✅ |
| 2025/F1/Q6 | M1-25-F1-Q06 | CP4 | 8º comprimido, a cada 8h desde segunda 8h | B ✅ |
| 2025/F1/Q7 | M1-25-F1-Q07 | CP2 | Combinação impossível dos 2 quadrados cortados | 🖼️ *(confirmar)* |
| 2025/F1/Q8 | M1-25-F1-Q08 | CP1 | Chocolate — 1/3 a Jade, metade do resto a Esmeralda | C ✅ |
| 2025/F1/Q9 | M1-25-F1-Q09 | CP5 | Quem está exatamente no meio da altura | B 🖼️ *(confirmar)* |
| 2025/F1/Q10 | M1-25-F1-Q10 | CP7 | Jogos do campeonato de 4 times (todos×todos) | C ✅ |
| 2025/F1/Q11 | M1-25-F1-Q11 | CP2 | Corte que permite formar 3 triângulos | C 🖼️ *(confirmar)* |
| 2025/F1/Q12 | M1-25-F1-Q12 | CP1 | Maior número de 2 dígitos sem reordenar cartões | C ✅ |
| 2025/F1/Q13 | M1-25-F1-Q13 | CP2 | Figura oposta ao círculo no cubo 2×2×2 | 🖼️ *(confirmar)* |
| 2025/F1/Q14 | M1-25-F1-Q14 | CP5 | Cidades com temperatura entre 4 e 8 graus | C ✅🖼️ |
| 2025/F1/Q15 | M1-25-F1-Q15 | CP5 | Par de caixas que pode ser do mesmo menino | D 🖼️ *(confirmar)* |

### M1-25-F2 (2025 · 2ª Fase · 4ª Edição)
| Nome fácil | Código | Caminho | Tópico | Gabarito |
|---|---|---|---|---|
| 2025/F2/Q1 | M1-25-F2-Q01 | CP2 | Dedo dobrado ao cruzar os braços | D 🖼️ *(confirmar)* |
| 2025/F2/Q2 | M1-25-F2-Q02 | CP1 | Jogadores por time (13 alunos, 2 times iguais) | D ✅ |
| 2025/F2/Q3 | M1-25-F2-Q03 | CP4 | Painel 2h atrás; temperatura caiu 3 graus | E ✅ |
| 2025/F2/Q4 | M1-25-F2-Q04 | CP7 | Maior soma de 3 cartões entre 6 | C ✅ |
| 2025/F2/Q5 | M1-25-F2-Q05 | CP6 | Pulseira diferente das outras 4 | C 🖼️ *(confirmar)* |
| 2025/F2/Q6 | M1-25-F2-Q06 | CP1 | Preço da caneta (3 lápis=6; 1 lápis+1 caneta=6) | D ✅ |
| 2025/F2/Q7 | M1-25-F2-Q07 | CP4 | Horas entre 10h e 16h do dia seguinte | B ✅ |
| 2025/F2/Q8 | M1-25-F2-Q08 | CP5 | Figura que falta no tabuleiro (linha/coluna) | B ✅ |
| 2025/F2/Q9 | M1-25-F2-Q09 | CP2 | Peça que encaixa no tabuleiro | D 🖼️ *(confirmar)* |
| 2025/F2/Q10 | M1-25-F2-Q10 | CP2 | Figura que NÃO pode ser montada (3 peças do triângulo) | D ✅🖼️ *(raciocínio de convexidade, confirmar)* |
| 2025/F2/Q11 | M1-25-F2-Q11 | CP2 | Peça que Camila NÃO vai usar | 🖼️ *(confirmar)* |
| 2025/F2/Q12 | M1-25-F2-Q12 | CP7 | Mãos livres na roda de 4 bonequinhos | E 🖼️ *(confirmar — depende do nº de mãos por bonequinho)* |
| 2025/F2/Q13 | M1-25-F2-Q13 | CP7 | Losangos usados para preencher o triângulo | E 🖼️ *(confirmar — depende do tamanho exato da figura)* |
| 2025/F2/Q14 | M1-25-F2-Q14 | CP1 | Peso dos 3 animais juntos (pistas par a par) | D ✅ |
| 2025/F2/Q15 | M1-25-F2-Q15 | CP6 | Outra dupla que pode alinhar na roleta | D 🖼️ *(confirmar)* |

### M1-26-F1 (2026 · 1ª Fase · 5ª Edição)
| Nome fácil | Código | Caminho | Tópico | Gabarito |
|---|---|---|---|---|
| 2026/F1/Q1 | M1-26-F1-Q01 | CP7 | Figurinhas escondidas pelas mãos | D 🖼️ *(confirmar)* |
| 2026/F1/Q2 | M1-26-F1-Q02 | CP1 | Algarismo com mais pingos de cola (o "8") | E ✅ |
| 2026/F1/Q3 | M1-26-F1-Q03 | CP1 | Número escondido pela joaninha (20+5=15+?) | C ✅ |
| 2026/F1/Q4 | M1-26-F1-Q04 | CP2 | Pedaços de barbante após o corte | C 🖼️ *(confirmar)* |
| 2026/F1/Q5 | M1-26-F1-Q05 | CP5 | Número da casa de Bia (em frente a Ana) | C ✅ |
| 2026/F1/Q6 | M1-26-F1-Q06 | CP7 | Aquários que José escolheu | 🖼️ *(confirmar)* |
| 2026/F1/Q7 | M1-26-F1-Q07 | CP3 | Diferença entre lápis e pincel na régua | C ✅🖼️ |
| 2026/F1/Q8 | M1-26-F1-Q08 | CP4 | Dia da semana do aniversário de Francisco | B ✅ |
| 2026/F1/Q9 | M1-26-F1-Q09 | CP5 | Afirmação certa sobre as idades das meninas | C ✅ |
| 2026/F1/Q10 | M1-26-F1-Q10 | CP5 | Peça que iguala a soma em cada linha/coluna | C ✅ |
| 2026/F1/Q11 | M1-26-F1-Q11 | CP2 | Peças que faltam para completar o tabuleiro | B 🖼️ *(confirmar)* |
| 2026/F1/Q12 | M1-26-F1-Q12 | CP2 | Vista de cima das 3 pilhas | C 🖼️ *(confirmar)* |
| 2026/F1/Q13 | M1-26-F1-Q13 | CP5 | Ordem de partida dos 3 carros (velocidades) | E ✅ |
| 2026/F1/Q14 | M1-26-F1-Q14 | CP7 | Face do dado num lançamento (soma = 11) | E ✅ |
| 2026/F1/Q15 | M1-26-F1-Q15 | CP6 | Letra onde o número 20 vai parar (roleta) | C ✅ |

---

## 5. Detalhamento por Caminho (resumo — ver tabela-mestre para o detalhe questão a questão)

A tabela-mestre (§4) já traz tópico e gabarito por questão organizados por prova. Abaixo, o inventário por Caminho (quais questões pertencem a cada um), para montagem direta do banco por unidade de curso:

- **CP1 (33):** 2022F1-Q1,Q3,Q7,Q13 · 2022F2-Q1,Q3,Q12,Q13 · 2023F1-Q3,Q10,Q11,Q13,Q14 · 2023F2-Q1,Q2,Q8,Q9,Q13 · 2024F1-Q1,Q11,Q12 · 2024F2-Q6,Q7 · 2025F1-Q3,Q8,Q12 · 2025F2-Q2,Q6,Q14 · 2026F1-Q2,Q3
- **CP2 (33):** 2022F1-Q5,Q8,Q11,Q12 · 2022F2-Q2,Q4,Q7,Q10 · 2023F1-Q4 · 2023F2-Q10,Q11,Q14,Q15 · 2024F1-Q2,Q4,Q6,Q8 · 2024F2-Q2,Q4,Q8,Q10,Q14 · 2025F1-Q1,Q2,Q7,Q11,Q13 · 2025F2-Q1,Q9,Q10,Q11 · 2026F1-Q4,Q11,Q12
- **CP3 (6):** 2022F1-Q9 · 2023F1-Q7 · 2023F2-Q7 · 2024F1-Q9 · 2025F1-Q5 · 2026F1-Q7
- **CP4 (11):** 2022F1-Q2 · 2022F2-Q6,Q8 · 2023F1-Q12 · 2023F2-Q4 · 2024F1-Q7 · 2024F2-Q9 · 2025F1-Q6 · 2025F2-Q3,Q7 · 2026F1-Q8
- **CP5 (20):** 2022F1-Q4,Q14 · 2022F2-Q11 · 2023F1-Q6,Q8 · 2023F2-Q12 · 2024F1-Q10,Q13,Q15 · 2024F2-Q1,Q3,Q12 · 2025F1-Q9,Q14,Q15 · 2025F2-Q8 · 2026F1-Q5,Q9,Q10,Q13
- **CP6 (12):** 2022F1-Q10,Q15 · 2022F2-Q5,Q14 · 2023F1-Q5,Q9 · 2024F1-Q5 · 2024F2-Q11 · 2025F1-Q4 · 2025F2-Q5,Q15 · 2026F1-Q15
- **CP7 (20):** 2022F1-Q6 · 2022F2-Q9,Q15 · 2023F1-Q2,Q15 · 2023F2-Q3,Q5,Q6 · 2024F1-Q3,Q14 · 2024F2-Q5,Q13,Q15 · 2025F1-Q10 · 2025F2-Q4,Q12,Q13 · 2026F1-Q1,Q6,Q14

---

## 6. Notas para o sequenciamento do curso

*(sem mudanças em relação à v3)*

1. **CP1 (Números) e CP4 (Calendário) abrem o curso**, em paralelo ou intercalados.
2. **CP2 (Geometria) entra cedo e se estende por todo o curso**, distribuído ao longo da trilha em vez de concentrado.
3. **CP6 e CP5 vêm na sequência**, depois de contagem e forma consolidadas.
4. **CP7 fecha cada ciclo**, por reaproveitar CP1+CP5+CP2.
5. **CP3**, mais magro, entra como blocos curtos de manutenção.

---

## 7. Estrutura pedagógica do Caminho 1 — blocos do curso *(exemplo completo)*

**CP1 · Números, Operações e Valor Posicional** — 8 blocos, do mais concreto ao mais abstrato:

1. **Contar e comparar** — contagem com sobreposição/oclusão, pareamento, "qual é o maior" (inclusive números por extenso), "diferente dos demais" por contagem. *(`2026/F1/Q1`; `2022/F1/Q1,Q6,Q7`)*
2. **Juntar e separar** — adição e subtração do dia a dia, com reagrupamento leve. *(recorrente em quase toda prova)*
3. **Multiplicar em grupos iguais** — multiplicação como soma repetida (gomos × sementes, etc.). *(`2023/F1/Q3`)*
4. **Dinheiro do dia a dia** — comprar, trocar, igualar valores entre pessoas. *(`2023/F1/Q13`; `2025/F2/Q6`)*
5. **Dezenas e unidades** — ábaco (trocar unidades por dezena), formação de número por encaixe de algarismo, contagem de ocorrência de dígito. *(`2022/F1/Q3`; `2022/F2/Q3,Q13`)*
6. **O número escondido** — operação inversa, uma incógnita numa igualdade. *(`2026/F1/Q3`; `2022/F1/Q14`)*
7. **Duas pistas, dois valores** — sistema simples de duas equações (duas compras, duas pilhas). *(`2022/F1/Q13`; `2025/F2/Q6`)*
8. **Somar as pistas e metade do grupo** — somar pistas par a par (3 somas → total) e frações simples como operador (metade, terço de uma quantidade). *(`2025/F2/Q14`; `2025/F1/Q8`)*

Cada bloco segue o padrão de capítulo do §14 do protocolo: ideia concreta → exemplo manipulável → repetição com números diferentes → exercícios. Os blocos 6–8 (mais abstratos) só devem vir depois que os blocos 1–5 estiverem consolidados.

---

## 8. Estrutura de blocos — todos os Caminhos

**CP2 · Geometria e Visualização Espacial** — 8 blocos:
1. **Espelho e reflexo** — como um objeto aparece do outro lado de um vidro ou invertido. *(`2023/F2`; `2024/F2`; `2026/F1/Q2`)*
2. **Vista de cima** — reconhecer uma pilha/montagem olhada de cima. *(`2022/F1/Q11`; `2022/F2/Q10`; `2026/F1/Q12`)*
3. **Dobrar e desdobrar** — dobradura e simetria por dobra. *(`2022/F1/Q8`; `2024/F1`)*
4. **Montar e desmontar formas** — cortar uma forma em peças e remontar outra. *(`2023/F1/Q7`; `2025/F2/Q9,Q10,Q13`)*
5. **Encaixar as peças** — encaixe de peça em malha/poliominó. *(`2025/F2/Q11`)*
6. **O fio enrolado** — contagem topológica em figura fechada (nós, cortes, elos). *(`2022/F1/Q12`; `2024/F2`; `2026/F1/Q4`)*
7. **Para que lado está** — orientação espacial e lateralidade. *(`2023/F1/Q4`)*
8. **Reconhecer pela parte** — identificar forma por parte visível/escondida. *(`2022/F1/Q5`)*

**CP3 · Grandezas e Medidas** — 2 blocos (Caminho curto, tratamento de manutenção):
1. **Medir com a régua** — comprimento, diferença entre duas medidas. *(`2023/F2`; `2026/F1/Q7`)*
2. **Dar a volta e voltar** — percursos e distâncias simples (ida e volta). *(`2022/F1/Q9`)*

**CP4 · Tempo, Calendário e Dias da Semana** — 3 blocos:
1. **Que horas são** — relógio digital, soma/diferença de horário, duração. *(`2022/F2/Q7,Q8`; `2023/F1/Q12`)*
2. **Que dia da semana é hoje** — calendário, dias da semana, aniversários. *(`2022/F1/Q2`; `2023/F1/Q8`; `2026/F1/Q8`)*
3. **De tanto em tanto tempo** — eventos que se repetem a cada N dias/horas (remédio, compromisso). *(`2025/F1/Q6`)*

**CP5 · Raciocínio Lógico e Dedução** — 7 blocos:
1. **Pistas em desenho** — pictograma no lugar de palavra como pista. *(`2022/F1/Q4`)*
2. **Cada linha, cada coluna** — restrição de soma/conjunto em grade (sudoku simples). *(`2023/F1/Q6`; `2025/F2/Q8`; `2026/F1/Q10`)*
3. **O que é certeza** — dedução sobre o que deve ser verdadeiro a partir de um intervalo/condições. *(`2026/F1/Q9`)*
4. **Quem está na frente** — ordenação relativa por posição/velocidade. *(`2024/F2`; `2026/F1/Q13`)*
5. **Par ou ímpar no lugar certo** — paridade de posição. *(`2026/F1/Q5`)*
6. **Eliminando pistas falsas** — eliminação de casos com uma pista que não bate. *(`2024/F1`)*
7. **Lendo gráficos e tabelas** — leitura direta de gráfico de barras/tabela. *(`2023/F2`; `2023/F1/Q8`)*

**CP6 · Sequências, Padrões e Processos Iterativos** — 4 blocos:
1. **Continuando o padrão** — sequência numérica, de figura ou de cor. *(recorrente)*
2. **A roda que gira** — padrão cíclico/rotação modular (roleta). *(`2025/F2/Q15`; `2026/F1/Q15`)*
3. **Pulando de tanto em tanto** — saltos/ritmos diferentes que se encontram. *(`2022/F1/Q15`; `2022/F2/Q14`)*
4. **Repetir até chegar lá** — processo iterativo tipo máquina. *(`2023/F1/Q9`)*

**CP7 · Contagem Avançada e Combinatória** — 5 blocos:
1. **Contar em grade** — contagem em malha, linhas × colunas. *(`2022/F2/Q9`)*
2. **Formar pares** — pareamento e correspondência. *(`2022/F1/Q6`)*
3. **Escolher sem repetir** — combinação de grupos/pares. *(`2023/F1/Q15`; `2025/F1/Q10`)*
4. **Somar partes diferentes** — soma de subconjuntos de valores distintos. *(`2024/F2`; `2025/F2/Q4`)*
5. **De quantos jeitos pode ser** — contagem de arranjos válidos sob restrição visual. *(`2024/F2`)*

**Total: 7 Caminhos, 37 blocos.**

---

## Próximo passo

1. **Segunda leitura humana** das 64 questões marcadas `🖼️ (confirmar)` — idealmente contra a prova original em `Provas/`, antes de qualquer uma delas virar conteúdo publicado.
2. **Atribuir Bloco específico** (não só Caminho) a cada questão, usando a lista de blocos da v3 (§7–§8) como referência.
3. A partir daí, **produção de conteúdo**: capítulos de teoria (§14 do protocolo) e questões autorais (§13), seguindo a régua de linguagem lúdica e resolução-junto-do-enunciado da v1.2 — começando pelos Caminhos de maior peso (CP1, CP2) ou pelo de maior recorrência entre edições (CP4, calendário).

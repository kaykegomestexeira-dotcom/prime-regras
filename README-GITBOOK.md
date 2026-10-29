# Publicando no GitBook — Passo a passo (Regras Prime Roleplayer)

Esta pasta (`regras-prime/`) está pronta para virar o GitBook oficial do **Prime Roleplayer**, espelhando o modelo `rulesanta.gitbook.io/regras-sg`.

## O que tem aqui

* `SUMMARY.md` — sumário do livro (o GitBook usa este arquivo como índice).
* `introducao.md` — página inicial.
* 20 páginas de regras em 4 blocos + Aliança, nos mesmos caminhos do modelo.

## Opção 1 — Git Sync com GitHub (recomendada)

1. Crie um repositório no GitHub (ex: `prime-roleplayer-regras`) e suba esta pasta.
2. No GitBook: **Create a new space → (ou space existente) → Space settings → Git Sync → Edit git repository** e conecte o repositório.
3. O GitBook importa `SUMMARY.md` e monta o livro automaticamente. Toda vez que você der `push`, o livro atualiza.

## Opção 2 — Manual (sem GitHub)

1. No GitBook: **Create a new space** (nome: `Regras Prime Roleplayer`).
2. Edite o sumário do space para bater com `SUMMARY.md` (mesmo nome de páginas e hierarquia).
3. Em cada página, cole o conteúdo do `.md` correspondente. Os blocos `{% hint %}` viram as caixas coloridas automaticamente.

## ⚙️ CHECKLIST DE CALIBRAÇÃO (valores herdados do modelo SantaGroup)

Estes números vieram do modelo — **valide/ajuste para a realidade do Prime** antes de divulgar o livro:

| Página | Item | Valor do modelo |
|---|---|---|
| Regras Gerais | Pistolas permitidas no Sul | Five Seven, Glock, M1911 (Tec-9 proibida) |
| Regras Gerais | Punição anti-cheat | Banimento |
| Ações de Rua | QRR infinito (rodovia/semáforo) | 720 min de ilha |
| Sequestros | Mínimo de bandidos p/ voz de sequestro | 5 (seguro: polícia +4) |
| Sequestros | Valor máximo do sequestro | 600k (refs: 250k/cabeça) |
| Desce e Quebra | Tempo mínimo de fuga antes do DQ | 5 minutos |
| Desce e Quebra | Carro capotado sem se render | 720 min de ilha |
| Sistema de Procurado | Duração do status "procurado" | ~10 minutos |
| Ações Grandes | Antecedência mínima p/ marcar | 4 horas |
| Ações Grandes | Contingente | Band. 10–20 · Polícia até +5 |
| Ações Grandes | Recursos da polícia | 1 águia + 2 blindados |
| Ações Médias | Contingente | Band. 4–8 · Polícia = band. +3 (máx 11) |
| Ações Pequenas | Contingente | Band. 2–4 · Polícia máx 6 |
| Pequenas/Médias | Espera após estourar cofre | 10 min |
| Guerras | Antecedência mínima p/ marcar | 1 dia |
| Invasões | Intervalo entre invasões | 30 dias |
| Invasões | Aviso do mandado (off-RP) | 24h (in-RP: 1h na porta) |
| Invasões | Prazo de recuperação de itens (GG polícia) | 48h |

Também confira: nomes das polícias/instituições do Prime (o modelo cita "DIC da PRN"), divisão Norte/Sul da sua cidade e os termos de punição (ilha/advertência).

## Revisão

Depois da calibração, o próximo passo é publicar no Discord (painéis idempotentes, mesmo padrão da Telagem) + comandos `/regras` e `/duvida` no bot.

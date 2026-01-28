## Laboratório de Inteligência Artificial
 
Este repositório é um laboratório de experimentos com inteligência artificial. Este projeto é apenas para aprendizado e testes.

## Objetivo

Documentar e explorar ideias, técnicas e ferramentas relacionadas à inteligência artificial em um ambiente seguro para estudo.

## Experimentos

- Protótipos e provas de conceito com modelos de IA.
- Avaliações de técnicas, bibliotecas e abordagens de implementação.
- Testes rápidos para validar hipóteses e aprender com os resultados.
 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/README.md b/README.md
index 8636185058131f2cec1af7a23f3d909dba447070..6746d43b658a495d0c44e41f7c9aff15210b3b31 100644
--- a/README.md
+++ b/README.md
@@ -1,14 +1,33 @@
 ## Laboratório de Inteligência Artificial
  
 Este repositório é um laboratório de experimentos com inteligência artificial. Este projeto é apenas para aprendizado e testes.
 
 ## Objetivo
 
 Documentar e explorar ideias, técnicas e ferramentas relacionadas à inteligência artificial em um ambiente seguro para estudo.
 
 ## Experimentos
 
 - Protótipos e provas de conceito com modelos de IA.
 - Avaliações de técnicas, bibliotecas e abordagens de implementação.
 - Testes rápidos para validar hipóteses e aprender com os resultados.

## Agente (MVP)

Foi adicionado um CLI simples para simular o funcionamento de um agente de IA local.

### Como executar

Modo interativo:

```bash
python agent.py
```

Mensagem única:

```bash
python agent.py --message "resuma o experimento 01"
```

Logs são gravados em `logs/agent.log` (pode ser alterado via `AGENT_LOG`).
 
EOF
)

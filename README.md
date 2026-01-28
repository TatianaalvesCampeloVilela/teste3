 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/README.md b/README.md
index 8b137891791fe96927ad78e64b0aad7bded08bdc..f6b6e0f1dbe695dc3910d32e7ba12f3b567f0ca9 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,13 @@
+# Laboratório de Inteligência Artificial
 
+Este repositório é um laboratório de experimentos com inteligência artificial. Este projeto é apenas para aprendizado e testes.
+
+## Objetivo
+
+Documentar e explorar ideias, técnicas e ferramentas relacionadas à inteligência artificial em um ambiente seguro para estudo.
+
+## Experimentos
+
+- Protótipos e provas de conceito com modelos de IA.
+- Avaliações de técnicas, bibliotecas e abordagens de implementação.
+- Testes rápidos para validar hipóteses e aprender com os resultados.
 
EOF
)

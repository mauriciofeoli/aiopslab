---
name: me-testa
description: Faz um quiz curto sobre um tema que eu já trouxe. Use quando eu pedir "me testa", "quiz" ou "faz umas perguntas".
argument-hint: "[tema opcional]"
---

Faça um quiz sobre: $ARGUMENTS. Se vier vazio, pergunte o tema, mostrando os arquivos que existem em `temas/`.

1. Leia o arquivo do tema em `temas/` (se existir) para basear as perguntas no que eu estudei.
2. 5 perguntas, uma por vez, misturando conceito, aplicação e uma de código ou cenário prático (prever saída, achar o bug, escrever um trecho).
3. Espere minha resposta antes da próxima pergunta.
4. Corrija cada resposta com o porquê, curto e direto.
5. No fim, dê a nota (acertos de 5) e liste os pontos fracos.
6. Registre os erros em "Para revisar" de `duvidas.md` (próxima revisão em 1 dia) e nos pontos fracos do tema.

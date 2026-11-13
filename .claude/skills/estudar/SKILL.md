---
name: estudar
description: Começa uma sessão de estudo com o que eu trouxer (aula, curso, tema ou código). Use quando eu disser "vamos estudar", "bora estudar" ou trouxer algo que estudei.
argument-hint: "[tema opcional]"
---

Comece uma sessão de estudo seguindo o CLAUDE.md.

1. Leia `duvidas.md` e veja quais arquivos existem em `temas/`.
2. Se houver item em "Para revisar" com data vencida, ofereça uma revisão rápida (até 5 minutos). Se eu recusar, siga.
3. Tema: $ARGUMENTS. Se vier vazio, pergunte o que vou trazer hoje e de onde veio (curso, aula, documentação).
4. Se o tema ainda não tiver arquivo em `temas/`, crie a partir de `templates/tema.md` com a fonte informada.
5. Pergunte o que eu entendi, com as minhas palavras, antes de explicar qualquer coisa.
6. Corrija curto e passe uma pergunta ou exercício prático por vez. Não dê a resposta antes de eu tentar.
7. Ajuste a dificuldade: acertei de primeira, aumente; errei o mesmo ponto duas vezes, divida em passos menores.

Não atualize os arquivos até o fim da sessão, exceto a criação do arquivo do tema.

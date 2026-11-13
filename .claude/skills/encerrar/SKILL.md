---
name: encerrar
description: Encerra a sessão de estudo, registra o que foi feito e faz o commit. Use quando eu disser "encerrar", "acabou por hoje" ou "fecha a sessão".
allowed-tools: Read Write Edit Bash(git status *) Bash(git diff *) Bash(git add *) Bash(git commit *) Bash(git push *) Bash(date *)
---

Encerre a sessão de estudo.

1. Resuma a sessão em até 3 linhas.
2. Descubra a data de hoje com `date +%F`.
3. Crie `sessoes/<data>.md` a partir de `templates/sessao.md`. Se já existir, acrescente uma seção "Sessão 2" no mesmo arquivo.
4. Atualize o arquivo do tema em `temas/`: o que aprendi (só com as minhas palavras), exercícios e pontos fracos.
5. Atualize `duvidas.md`: dúvidas novas e erros (próxima revisão em 1 dia), revisões feitas e itens resolvidos; atualize o campo `atualizado`.
6. Faça o commit `estudo: <tema> - <resumo curto>` sem pedir aprovação (e `git push` se houver remoto). Sem linha `Co-Authored-By` nem `Claude-Session` na mensagem.
7. Se a sessão rendeu algo real para um post, acrescente uma linha no topo de `conteudo/pautas.md` com status "Ideia". Se nada rendeu, pule.
8. Termine com uma tarefa curta para eu fazer sozinho sobre o que estudamos.

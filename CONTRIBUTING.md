# Contribuindo — Stratum Platform

## Regras Gerais

- use branch de trabalho para qualquer alteracao
- evite push direto para main
- abra pull request para integrar mudancas
- mantenha descricoes objetivas em commits e PRs

## Fluxo

1. sincronize base: `git syncmain`
2. inicie tarefa: `git starttask tipo/nome-da-tarefa`
3. implemente alteracoes
4. entregue: `git shiptask "tipo: mensagem do commit"`
5. crie e faça merge da PR

## Convencao de Branch

- `feat/...` para funcionalidade
- `fix/...` para correcao
- `docs/...` para documentacao
- `chore/...` para manutencao

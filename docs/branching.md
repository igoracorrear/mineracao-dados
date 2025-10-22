# Estratégia de Branches

Este guia descreve uma convenção simples para organizar o fluxo de trabalho no repositório.

## Branches principais

- **main**: contém versões aprovadas, prontas para entrega ou publicação.
- **develop**: recebe commits das branches de funcionalidade e concentra o trabalho em andamento.

## Branches auxiliares

- **feature/**: para novas funcionalidades ou análises. Exemplo: `feature/ajuste-modelo`.
- **hotfix/**: para correções urgentes. Exemplo: `hotfix/corrige-relatorio`.
- **release/**: opcional para preparar publicações maiores.

## Fluxo sugerido

1. Atualize a branch `develop` com `git pull origin develop`.
2. Crie uma branch de funcionalidade: `git checkout -b feature/nome`.
3. Após concluir o trabalho, abra um pull request de `feature/nome` para `develop`.
4. Quando `develop` estiver estável, faça merge em `main` e crie um tag se necessário.

Adapte este fluxo às necessidades específicas do projeto e da equipe.

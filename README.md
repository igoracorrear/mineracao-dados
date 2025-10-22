# Mineração de Dados

Este repositório foi reorganizado para facilitar a visualização das partes de um projeto de ciência de dados. A estrutura segue uma convenção inspirada em projetos de mineração de dados com etapas de preparação, modelagem e comunicação dos resultados.

## Estrutura de pastas

```
mineracao-dados/
├── configs/          # Arquivos de configuração (YAML, JSON, etc.)
├── data/
│   ├── processed/    # Dados prontos para modelagem
│   └── raw/          # Dados brutos de entrada
├── docs/             # Documentação adicional do projeto
├── models/           # Artefatos treinados (modelos, métricas)
├── notebooks/        # Notebooks exploratórios e experimentos
├── reports/          # Relatórios e apresentações geradas
├── scripts/          # Scripts utilitários e tarefas pontuais
└── src/              # Código-fonte reutilizável (pipelines, módulos)
```

Cada pasta contém um arquivo `.gitkeep` apenas para garantir que o diretório seja versionado mesmo vazio. Substitua esses placeholders pelo conteúdo real do seu projeto conforme for evoluindo.

## Organização das branches

Sugestão de fluxo simples:

- `main`: branch estável com entregáveis revisados.
- `develop`: branch de integração contínua onde novas funcionalidades são preparadas.
- Branches de funcionalidade no formato `feature/<descricao-curta>`.

Para criar as branches sugeridas localmente:

```bash
git branch -m main               # Renomeia a branch atual para main
git branch develop               # Cria a branch de desenvolvimento
git checkout develop
git checkout -b feature/inicio-projeto
```

Adapte o fluxo conforme a necessidade do seu time.

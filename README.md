# Middle-earth Agents

Um monorepo para gerenciar a orquestração de agentes de engenharia.

## Estrutura
- `agents/`: Contém os submódulos dos agentes (Gandalf, Boromir, etc).
- `protocols/`: A "língua comum" (Sinais) para comunicação entre agentes.

## Setup
Para inicializar os submódulos:
```bash
git submodule update --init --recursive
```

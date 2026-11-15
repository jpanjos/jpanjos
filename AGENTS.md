# AGENTS.md

Instrucoes para qualquer agente de IA (Claude, Codex, Antigravity/Gemini, Copilot) neste repositorio.

## Projeto
TODO: o que este projeto faz, em 2-3 linhas.

## Como rodar
TODO: ex. `python -m venv .venv`, `pip install -r requirements.txt`, `python main.py`

## Testes
TODO: ex. `pytest -q`. Rode os testes antes de considerar uma tarefa pronta.

## Convencoes
- Python: PEP 8, type hints em funcoes publicas, logging em vez de print.
- SQL: TODO dialeto(s) usado(s) (Oracle / SQL Server / PostgreSQL / DB2).
- Commits pequenos e com mensagem descritiva.

## Divisao entre agentes
| Tipo de tarefa                                  | Agente         |
|-------------------------------------------------|----------------|
| Planejamento, arquitetura, revisao, integracao  | Claude         |
| Implementacao de scripts Python, SQL e testes   | Codex (GPT)    |
| Documentacao, README, pesquisa de bibliotecas   | Gemini (agy)   |
| Ajustes pequenos, boilerplate, mensagens commit | Copilot        |

## Prioridade da semana
Normal. (Troque para algo como "Claude perto do limite: delegue mais ao Codex".)

## Nao fazer
- Nao ler, editar ou enviar o conteudo de `.env` ou arquivos de credenciais.
- Nao editar fora da pasta/branch da sua tarefa.
- Nao instalar dependencias novas sem registrar no requirements/pyproject.
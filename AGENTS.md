# AGENTS.md

Instruções para qualquer agente de IA (Claude, Codex, Antigravity/Gemini, Copilot) neste repositório.

## Projeto
README de perfil do GitHub (`jpanjos/jpanjos`, repositório PÚBLICO): portfólio profissional em Dados, BI e automação.
Só Markdown; os projetos citados são privados e aparecem como estudos de caso.

## Como rodar
Nada para rodar. Confira a renderização do `README.md` no GitHub ou num visualizador de Markdown.

## Testes
Sem testes automáticos. Antes de concluir, confira se todos os links abrem e se nenhum repositório privado aparece como link.

## Convenções
- Python: PEP 8, type hints em funções públicas, logging em vez de print.
- Textos em português; não inventar experiência, números ou habilidades que os projetos não comprovem.
- Commits pequenos e com mensagem descritiva.

## Divisão entre agentes
| Tipo de tarefa                                  | Agente         |
|-------------------------------------------------|----------------|
| Planejamento, arquitetura, revisão, integração  | Claude         |
| Implementação de scripts Python, SQL e testes   | Codex (GPT)    |
| Documentação, README, pesquisa de bibliotecas   | Gemini (agy)   |
| Ajustes pequenos, boilerplate, mensagens commit | Copilot        |

## Prioridade da semana
Normal.

## Não fazer
- Não ler, editar ou enviar o conteúdo de `.env` ou arquivos de credenciais.
- Não editar fora da pasta/branch da sua tarefa.
- Não instalar dependências novas sem registrar no requirements/pyproject.

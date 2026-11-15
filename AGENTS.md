# AGENTS.md

Instrucoes para qualquer agente de IA (Claude, Codex, Antigravity/Gemini, Copilot) neste repositorio.

## Projeto
README de perfil do GitHub (`jpanjos/jpanjos`, repositorio PUBLICO): portfolio profissional em Dados, BI e automacao.
So Markdown; os projetos citados sao privados e aparecem como estudos de caso.

## Como rodar
Nada para rodar. Confira a renderizacao do `README.md` no GitHub ou num visualizador de Markdown.

## Testes
Sem testes automaticos. Antes de concluir, confira se todos os links abrem e se nenhum repositorio privado aparece como link.

## Convencoes
- Python: PEP 8, type hints em funcoes publicas, logging em vez de print.
- Textos em portugues; nao inventar experiencia, numeros ou habilidades que os projetos nao comprovem.
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
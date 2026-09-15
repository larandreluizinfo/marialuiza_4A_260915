# AGENTS - Regras obrigatórias

## 🚨 REGRA DE OURO: toda alteração deve ser commitada e pushada

Todo agente (humano ou IA) que modificar qualquer arquivo neste repositório DEVE:

1. `git add -A`
2. `git commit -m "<descrição clara da alteração>"`
3. `git push origin main` (ou `master`, conforme branch principal)

- Nunca deixe alterações só locais. Sempre finalize com commit + push.
- Faça isso ao final de CADA tarefa, sem exceção.
- Se o push falhar, tente `git pull --rebase` e push novamente.
- Verifique com `git status` que está tudo limpo antes de terminar.

## Outras regras
- Site estático: `index.html` na raiz (GitHub Pages com deploy from branch).
- Não quebrar o jogo: manter controles WASD, criativo tecla C, inventário tecla E.
- Português pt-BR nos textos do jogo.

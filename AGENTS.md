# Instruções para agentes de IA

Este é o repositório `.github` da org `wemunar`: a política pública (`SECURITY.md`), o perfil (`profile/README.md`) e o template de PR padrão da org. **É público**: nada de segredo, e-mail pessoal nem dado de pessoa entra aqui.

## Processo e merge

O procedimento (ciclo de uma fatia, revisora, retro) e os itens `WRK` moram no `wemunar/platform`: `docs/OPERATING.md` e `docs/WORK.md`. Este repositório não tem `WORK` nem `DEC` próprios.

Todo PR aqui é mesclado pela usuária: o conteúdo é política pública, o ruleset da `main` exige PR, e o repositório fica fora da cadeia do portão de merge do `platform`.

## Onde mudar cada coisa

- **Política de vulnerabilidade da org:** `SECURITY.md`, só o canal `security@wemunar.com` e os prazos; vale para todos os repositórios sem o próprio arquivo.
- **Perfil público da org:** `profile/README.md`, só o que o produto já entrega.
- **Template de PR padrão:** `pull_request_template.md`, o mesmo do `platform`; um repositório com o próprio `.github/pull_request_template.md` o sobrepõe.
- **Instruções e dono de caminho:** este `AGENTS.md` (com o `CLAUDE.md`, symlink para ele) e `.github/CODEOWNERS`, só humanos.

## Regra fixa

O texto público só promete o que o produto entrega. Sem emoji e sem exclamação, em inglês primeiro, como o resto da marca (`wemunar/brand`, `docs/05-voz-e-textos.md`).

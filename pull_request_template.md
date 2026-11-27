CHAIN_EXIT=0 HEAD=<head de 40> TREE=<árvore de 40>
<!-- A linha acima é a que o gate local do repositório imprime (`ci:local`), colada como está. O padrão da org: um repositório
     com o próprio `.github/pull_request_template.md` o sobrepõe. -->

## Item
<!-- Os mesmos IDs do fim do título: `WRK-NNNNN` ou `WRK-NNNNN/DEC-NNNNN`; e o `Tipo:` do diff, os da tabela do
     AGENTS.md do repositório. -->
Tipo:

## Impacto
<!-- `Fora do declarado: nenhum`, ou uma linha «- `caminho` — motivo» por arquivo do diff que o `In`, o `Impact`
     ou o `Boundary` do WRK e a DEC não citam. A lista de derivadas e fronteiras mora no WRK, nunca aqui. -->

## Evidência
<!-- Uma linha por afirmação do PR, e a revisora repete o comando e compara a saída. Sem `|` dentro da crase. -->
| Afirmação | Comando | Saída |
|---|---|---|

## Lições
<!-- Os `RT-NN` que este PR registrou (todos os novos do `retro.tsv`), ou `nenhuma — <motivo>`. -->

## Regressão coberta
<!-- Os testes ou checks em crase que ficam vermelhos se o defeito voltar, ou `nenhuma — <motivo>`. -->

## Superfície
<!-- Regras e skills: cada arquivo do diff nas regras do processo (instruções do agente, OPERATING, skills, hooks,
     settings, o script de merge), ou `nenhuma`. Ferramentas: cada linha mudada de OPERATING § Ferramentas, ou `nenhuma`. -->
Regras e skills:
Ferramentas:

## Continuidade
<!-- `Now: WRK-NNNNN`, o único Now do `docs/WORK.md` neste head, ou `Now: nenhum`. -->
Now:

#Git Flow

⏳📚💡⚠️⚠️Repository under contruction⚠️⚠️
===========
Este é um repositório para dicas e prática do git flow.

O que é Git Flow
----------------
A extensão Git Flow é um conjunto de extensões do Git que fornecem operações de repositório de alto nível para o modelo de ramificação de Vincent Driessen.
<img src="https://jeffkreeftmeijer.com/git-flow/git-flow.png" target="https://jeffkreeftmeijer.com/git-flow/">

Comandos
-------
Iniciando a extensão:

    git flow init -d

Feature:
    git flow feature start <name> [<base>]
    git flow feature finish <name>
    git flow feature publish <name>
    git flow feature pull <remote> <name>

Realease:

    git flow release start <release> [<base>]
    git flow release finish <release>

Hotfix:

    git flow hotfix start <release> [<base>]
    git flow hotfix finish <release>

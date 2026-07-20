# Changelog

Todas as mudanças importantes deste projeto serão documentadas neste arquivo.


## Unreleased



### Outras alterações


- Initial commit

- Ajustes no Template padrão

Modificado para o Sebastian

- Update README.md

Ajustes e sugestoes de presentes

- Cartas adicionadas

Traduções parcialmente feitas

- Itens trocados

Presentes ajustados
Trocar referencia ao ovo de sapo por ovo somente

- Update README.md

- Traduções novas

Ajustado em grande maioria das cartas o frog egg e trocado para green slime egg

- Ajustes finos

Remoção de comentario e update do Readme

- Update mail.json

Corrigindo valor null no log com entrada de texto valida no arquivo

- Update manifest.json

Update key added

- Fix typo in Sebastian mail Id

Correct a misspelled Id in [MFM] Gifts from Sebastian/mail.json: change "SebastianRepetable" to "SebastianRepeteable" so the mail entry's Id matches the intended naming. No other changes.

- Rename mail group ID for Sebastian letters

Change the GroupId from 'RepeteableSebastian' to 'SebastianLetters' for the repeatable Sebastian mail entry, providing a more consistent naming convention.

- Add automatic changelog generation workflow

Add a GitHub Actions workflow that automatically generates and commits CHANGELOG.md updates on pushes to main using git-cliff. The workflow runs on every push to main, generates the changelog from git commits, and auto-commits any changes with [skip ci] flag.

- Refactor changelog workflow to use git-cliff CLI

Replace git-cliff GitHub action with direct CLI installation and usage. Add cliff.toml configuration file to customize changelog formatting with conventional commits and emoji-categorized commit groups (features, fixes, performance, refactoring, docs, etc.). This provides better control over changelog generation and makes the workflow more maintainable.



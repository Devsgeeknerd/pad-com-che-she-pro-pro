<!-- Título -->
# Padrões de Commits

## Introdução

Este documento define os padrões de commits a serem seguidos (para meus repositórios), utilizando emojis para representar diferentes tipos de alterações no código.

Seguir um padrão de commits me ajuda a manter a clareza e a consistência nas mensagens, facilitando a identificação do tipo de alteração realizada e melhorando a identificação entre os desenvolvedores.

## Categorias de Commits

As seguintes categorias devem (ou não) ser usadas para classificar as alterações no código:

### Chore

`Chore` é uma categoria de tarefas que envolvem manutenção, organização e melhorias no código ou na infraestrutura do projeto. Essas tarefas são essências para garantir que o projeto continue a funcionar de maneira eficiente e que a base de código permaneça limpa e gerenciável.

### Exemplos de Commits

Aqui estão alguns exemplos de commits que podem ser criados em vez do padrão já definido neste documento:

## Dicas de Uso

* Use de forma moderada e apenas quando fizer sentido para a alteração.
* Certifique-se de que a descrição do commit seja clara e concisa, explicado o que foi alterado.
* Mantenha um padrão consistente em todos os repositórios e projetos para facilitar a leitura e compreensão das mensagens de commit.

### Code Actions

**Ações Gerais de Código:** Ações comuns relacionadas a adição, atualização e mesclagem de código.

| CODE | EMOJI | DESCRIPTION | TRANSLATION |
| :--- | :---: | :---------- | :---------- |
| `:bento:` | :bento: | Add, update or remove assets. | Adicionar, atualizar ou remover recursos. |
| `:label:` | :label: | Add, update or remove labels. | Adicionar, atualizar ou remover etiquetas. |
| `:package:` | :package: | Add, update or remove compiled files or packages. | Adicionar, atualizar ou remover arquivos ou pacotes compilados. |
| `:twisted_rightwards_arrows:` | :twisted_rightwards_arrows: | Merge branches. | Mesclar ramificações. |

### Code Quality

**Qualidade do Código:** Melhorias relacionadas ao estilo, correção de erros e limpeza de código.

| CODE | EMOJI | DESCRIPTION | TRANSLATION |
| :--- | :---: | :---------- | :---------- |
| `:art:` | :art: | Add, update or remove theme, style files. | Adicionar, atualizar ou remover arquivos de tema e estilo. |
| `:bug:` | :bug: | Fix a bug. | Corrigir um erro. |
| `:coffin:` | :coffin: | Remove dead code. | Remover código morto. |
| `:recycle:` | :recycle: | Refactor code. | Refatorar o código. |
| `:wrench:` | :wrench: | Add, update or remove configuration files. | Adicionar, atualizar ou remover arquivos de configuração. |

### Development

**Desenvolvimento:** Ações específicas de desenvolvimento, como experimentos e trabalho em andamento.

| CODE | EMOJI | DESCRIPTION | TRANSLATION |
| :--- | :---: | :---------- | :---------- |
| `:alembic:` | :alembic: | Perform experiments. | Realizar experimentos. |
| `:green_apple:` | :green_apple: | Add, update or remove support for macOS. | Adicionar, atualizar ou remover suporte para macOS. |
| `:construction:` | :construction: | Work in progress. | Trabalho em  andamento. |
| `:desktop_computer:` | :computer: | Add, update or remove support for Windows. | Adicionar, atualizar ou remover suporte para Windows. |
| `:jigsaw:` | :jigsaw: | Add, update or remove components. | Adicionar, atualizar ou remover componentes. |
| `:iphone:` | :iphone: | Add, update or remove support for iPhone. | Adicionar, atualizar ou remover suporte para iPhone. |
| `:penguin:` | :penguin: | Add, update or remove support for Linux. | Adicionar, atualizar ou remover suporte para Linux. |
| `:robot:` | :robot: | Add, update or remove support for Android. | Adicionar, atualizar ou remover suporte para Android. |

### Dependency Management

**Gerenciamento de Dependências:** Ações relacionadas a atualização e gerenciamento de dependências.

| CODE | EMOJI | DESCRIPTION | TRANSLATION |
| :--- | :---: | :---------- | :---------- |
| `:arrow_down:` | :arrow_down: | Downgrade dependencies. | Rebaixar dependências. |
| `:arrow_up:` | :arrow_up: | Upgrade dependencies. | Atualizar dependências. |
| `:heavy_minus_sign:` | :heavy_minus_sign: | Remove dependency. | Remover dependência. |
| `:heavy_plus_sign:` | :heavy_plus_sign: | Add dependency. | Adicionar  dependência. |
| `:pushpin:` | :pushpin: | Pin dependencies to specific versions. | Fixar dependências em versões específicas. |

### Testing and Quality

**Teste e Qualidade:** Ações relacionadas a testes e garantia de qualidade.

| CODE | EMOJI | DESCRIPTION | TRANSLATION |
| :--- | :---: | :---------- | :---------- |
| `:ballot_box_with_check:` | :ballot_box_with_check: | Update tests. | Atualizar testes. |
| `:x:` | :x: | Failed tests. | Testes falhados. |
| `:heavy_check_mark:` | :heavy_check_mark: | Add tests. | Adicionar testes. |
| `:white_check_mark:` | :white_check_mark: | Passing tests. | Testes aprovados. |
| `:test_tube:` | :test_tube: | Add failing test. | Adicionar teste que falha. |

### Documentation

**Documentação:** Atualizações e adições de documentação.

| CODE | EMOJI | DESCRIPTION | TRANSLATION |
| :--- | :---: | :---------- | :---------- |
| `:book:` | :book: | Add or remove README documentation. | Adicionar ou remover documentação README. |
| `:blue_book:` | :blue_book: | Add or remove software documentation. | Adicionar ou remover documentação de software. |
| `:clipboard:` | :clipboard: | Documentation in progress. | Documentação em andamento. |
| `:green_book:` | :green_book: | Add or remove app documentation. | Adicionar ou remover documentação do aplicativo. |
| `:orange_book:` | :orange_book: | Add or remove API documentation. | Adicionar ou remover documentação da API. |
| `:pencil:` | :pencil: | Update documentation content. | Atualizar o conteúdo da documentação. |
| `:pencil2:` | :pencil2: | Fix typos in files or documentation. | Corrigir erros de digitação em arquivos ou na documentação. |

### Improvements and New Features

**Melhorias e Novas Funcionalidades:** Introdução de novas funcionalidades e melhorias de desempenho.

| CODE | EMOJI | DESCRIPTION | TRANSLATION |
| :--- | :---: | :---------- | :---------- |
| `:children_crossing:` | :children_crossing: | Improve user experience / usability. | Melhorar a experiência do usuário / usabilidade. |
| `:sparkles:` | :sparkles: | Introduce new features. | Introduzir novos recursos. |
| `:zap:` | :zap: | Improve performance. | Melhorar o desempenho. |

### Project Management

**Gerenciamento de Projetos:** Ações relacionados ao gerenciamento de versões e início de projetos.

| CODE | EMOJI | DESCRIPTION | TRANSLATION |
| :--- | :---: | :---------- | :---------- |
| `:bookmark:` | :bookmark: | Version tags. | Tags de versão. |
| `:bow_and_arrow:` | :bow_and_arrow: | Add, update or remove goals. | Adicionar, atualizar ou remover metas. |
| `:checkered_flag:` | :checkered_flag:  | Begin a project. | Iniciar um projeto. |
| `:dart:` | :dart: | Completed goals. | Metas concluídas. |
| `:tada:` | :tada: | Initial commit. | Commit inicial. |

### Security and Privacy

**Segurança e Privacidade:** Correções de problemas de segurança e privacidade.

| CODE | EMOJI | DESCRIPTION | TRANSLATION |
| :--- | :---: | :---------- | :---------- |
| `:eye:` | :eye: | Fix privacy issues. | Corrigir problemas de privacidade. |
| `:lock:` | :lock: | Fix security issues. | Corrigir problemas de segurança. |

### Code Review

**Revisão de Código:** Ações relacionadas a revisão e análise de alterações no código.

| CODE | EMOJI | DESCRIPTION | TRANSLATION |
| :--- | :---: | :---------- | :---------- |
| `:eyes:` | :eyes: | Review code changes. | Revisar alterações de código. |

### Code Cleanup

**Limpeza de Código:** Limpeza e depreciação de código obsoleto.

| CODE | EMOJI | DESCRIPTION | TRANSLATION |
| :--- | :---: | :---------- | :---------- |
| `:broom:` | :broom: | Perform code cleanup. | Realizar limpeza de código. |
| `:wastebasket:` | :wastebasket: | Deprecate code that needs to be cleaned. | Depreciar o código que precisa ser limpo. |

### Code Optimization

**Otimização de Código:** Otimizações para melhorar o desempenho do código.

| CODE | EMOJI | DESCRIPTION | TRANSLATION |
| :--- | :---: | :---------- | :---------- |
| `:chart_with_downwards_trend:` | :chart_with_downwards_trend: | Optimize code for performance. | Otimizar o código para desempenho. |

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fpad-com-che-she-pro-pro&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/pad-com-che-she-pro-pro?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/pad-com-che-she-pro-pro?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/pad-com-che-she-pro-pro?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/pad-com-che-she-pro-pro?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/pad-com-che-she-pro-pro?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")

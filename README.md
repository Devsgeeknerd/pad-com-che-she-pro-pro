<!-- Título -->
# Padrões de Commits :rocket:

## :pushpin: Introdução

Este documento define um padrão de commits para manter **clareza, consistência e eficiência** nos repositórios.

O uso de **emojis** facilita a identificação visual do tipo de alteração realizada, promovendo melhor colaboração e organização.

---

## :file_folder: Categorias de Commits

### :wrench: Chore

Alterações de manutenção e organização que não impactam diretamente a funcionalidade do projeto.

#### Exemplo de tarefas Chore

:white_check_mark: Atualização de dependências.
:white_check_mark: Limpeza de código morto.
:white_check_mark: Configuração de ferramentas como linters e CI/CD.
:white_check_mark: Ajustes de ambiente de desenvolvimento.

:pushpin: Exemplo de commit:
> :hammer_and_wrench: chore(deps): atualiza dependências para a versão mais recente.

---

### :sparkles: Feat

Adição de novas funcionalidades ou melhorias que agregam valor ao usuário.

#### Exemplos de tarefas Feat

:white_check_mark: Implementação de novas funcionalidades.
:white_check_mark: Melhorias na UI/UX.
:white_check_mark: Suporte a novos dispositivos ou plataformas.
:white_check_mark: Integração com APIs externas.

:pushpin: Exemplo de commit:
> :sparkles: feat(auth): adicionar sistema de autenticação JWT.

---

### :lady_beetle: Fix

Correção de **bugs** que impactam o funcionamento esperado do sistema.

#### Exemplos de tarefas Fix

:white_check_mark: Correção de erros de lógica.
:white_check_mark: Ajustes em validações.
:white_check_mark: Correção de falhas na interface.

:pushpin: Exemplo de commit:
> :lady_beetle: fix(api): corrige validação de email.

---

### :ambulance: Hotfix

Correções **críticas e emergenciais** que precisam ser aplicadas imediatamente.

#### Exemplos de tarefas Hotfix

:white_check_mark: Resolver erro crítico em produção.  
:white_check_mark: Ajustes rápidos de segurança.  

:pushpin: Exemplo de commit:
> :ambulance: hotfix(login): corrige erro impedindo login de usuários

---

### :art: Style

`Test` é reservado para commits relacionados à criação, atualização ou exclusão de testes automatizados.

### Exemplos de tarefas Style

:white_check_mark: Ajustes de indentação e espaçamentos.
:white_check_mark: Correção de formatação de código.
:white_check_mark: Alterações em estilos.

:pushpin: Exemplo de commit:
> :art: style(ui): ajusta espaçamento entre botões.

---

### :arrows_counterclockwise: Refactor

Melhorias na **estrutura do código** sem alterar seu comportamento.

### Exemplos de tarefas Refactor

:white_check_mark: Melhor organização do código.
:white_check_mark: Simplificação de funções complexas.
:white_check_mark: Redução da repetição de código.

:pushpin: Exemplo de commit:
> :arrows_counterclockwise: refactor(user-service): melhora a modularização do código.

---

### :racing_car: Perf

Otimizações de **desempenho** para melhorar a eficiência do código.

### Exemplos de tarefas Perf

:white_check_mark: Redução do tempo de execução de um algoritmo.
:white_check_mark: Melhor uso de recursos do sistema.

:pushpin: Exemplo de commit:
> :racing_car: perf(algoritmo): otimiza busca para reduzir tem de execução.

### Exemplos de Commits

Aqui estão alguns exemplos de commits que seguem este padrão:

`emoji categoria(tipo): descrição.`

* :sparkles: feat(auth): adiciona sistema de autenticação com JWT.
* :bug: fix(api): corrige erro na validação de dados.
* :pencil: docs(README): atualiza instruções de instalação.
* :rocket: perf(algoritmo): otimiza busca para reduzir tempo de execução.

## Dicas de Uso

* Use emojis com moderação e apenas quando fizer sentido para a alteração.
* Certifique-se de que a descrição do commit seja clara e concisa.
* Mantenha um padrão consistente em todos os repositórios para facilitar a leitura e compreensão das mensagens de commit.

### Ações Gerais de Código

Ações comuns relacionadas a adição, atualização e mesclagem de código.

| CÓDIGO                        |            EMOJI            | DESCRIÇÃO                                                       |
| :---------------------------- | :-------------------------: | :-------------------------------------------------------------- |
| `:bento:`                     |           :bento:           | Adicionar, atualizar ou remover recursos.                       |
| `:label:`                     |           :label:           | Adicionar, atualizar ou remover etiquetas.                      |
| `:package:`                   |          :package:          | Adicionar, atualizar ou remover arquivos ou pacotes compilados. |
| `:twisted_rightwards_arrows:` | :twisted_rightwards_arrows: | Mesclar ramificações.                                           |

---

### Qualidade do Código

Melhorias relacionadas ao estilo, correção de erros e limpeza de código.

| CÓDIGO      |   EMOJI   | DESCRIÇÃO                                                  |
| :---------- | :-------: | :--------------------------------------------------------- |
| `:art:`     |   :art:   | Adicionar, atualizar ou remover arquivos de tema e estilo. |
| `:bug:`     |   :bug:   | Corrigir um erro.                                          |
| `:coffin:`  | :coffin:  | Remover código morto.                                      |
| `:recycle:` | :recycle: | Refatorar o código.                                        |
| `:wrench:`  | :wrench:  | Adicionar, atualizar ou remover arquivos de configuração.  |

---

### Desenvolvimento

Ações específicas de desenvolvimento, como experimentos e trabalho em andamento.

| CÓDIGO               |     EMOJI      | DESCRIÇÃO                                             |
| :------------------- | :------------: | :---------------------------------------------------- |
| `:alembic:`          |   :alembic:    | Realizar experimentos.                                |
| `:green_apple:`      | :green_apple:  | Adicionar, atualizar ou remover suporte para macOS.   |
| `:construction:`     | :construction: | Trabalho em andamento.                                |
| `:desktop_computer:` |   :computer:   | Adicionar, atualizar ou remover suporte para Windows. |
| `:jigsaw:`           |    :jigsaw:    | Adicionar, atualizar ou remover componentes.          |
| `:iphone:`           |    :iphone:    | Adicionar, atualizar ou remover suporte para iPhone.  |
| `:penguin:`          |   :penguin:    | Adicionar, atualizar ou remover suporte para Linux.   |
| `:robot:`            |    :robot:     | Adicionar, atualizar ou remover suporte para Android. |

---

### Gerenciamento de Dependências

Ações relacionadas a atualização e gerenciamento de dependências.

| CÓDIGO               |       EMOJI        | DESCRIÇÃO                                  |
| :------------------- | :----------------: | :----------------------------------------- |
| `:arrow_down:`       |    :arrow_down:    | Rebaixar dependências.                     |
| `:arrow_up:`         |     :arrow_up:     | Atualizar dependências.                    |
| `:heavy_minus_sign:` | :heavy_minus_sign: | Remover dependência.                       |
| `:heavy_plus_sign:`  | :heavy_plus_sign:  | Adicionar dependência.                     |
| `:pushpin:`          |     :pushpin:      | Fixar dependências em versões específicas. |

---

### Teste e Qualidade

Ações relacionadas a testes e garantia de qualidade.

| CÓDIGO                    |          EMOJI          | DESCRIÇÃO                  |
| :------------------------ | :---------------------: | :------------------------- |
| `:ballot_box_with_check:` | :ballot_box_with_check: | Atualizar testes.          |
| `:x:`                     |           :x:           | Testes falhados.           |
| `:heavy_check_mark:`      |   :heavy_check_mark:    | Adicionar testes.          |
| `:white_check_mark:`      |   :white_check_mark:    | Testes aprovados.          |
| `:test_tube:`             |       :test_tube:       | Adicionar teste que falha. |

---

### Documentação

Atualizações e adições de documentação.

| CÓDIGO          |     EMOJI     | DESCRIÇÃO                                                   |
| :-------------- | :-----------: | :---------------------------------------------------------- |
| `:book:`        |    :book:     | Adicionar ou remover documentação README.                   |
| `:blue_book:`   |  :blue_book:  | Adicionar ou remover documentação de software.              |
| `:clipboard:`   |  :clipboard:  | Documentação em andamento.                                  |
| `:green_book:`  | :green_book:  | Adicionar ou remover documentação do aplicativo.            |
| `:orange_book:` | :orange_book: | Adicionar ou remover documentação da API.                   |
| `:pencil:`      |   :pencil:    | Atualizar o conteúdo da documentação.                       |
| `:pencil2:`     |   :pencil2:   | Corrigir erros de digitação em arquivos ou na documentação. |

---

### Melhorias e Novas Funcionalidades

Introdução de novas funcionalidades e melhorias de desempenho.

| CÓDIGO                |        EMOJI        | DESCRIÇÃO                                        |
| :-------------------- | :-----------------: | :----------------------------------------------- |
| `:children_crossing:` | :children_crossing: | Melhorar a experiência do usuário / usabilidade. |
| `:sparkles:`          |     :sparkles:      | Introduzir novos recursos.                       |
| `:zap:`               |        :zap:        | Melhorar o desempenho.                           |

---

### Gerenciamento de Projetos

Ações relacionados ao gerenciamento de versões e início de projetos.

| CÓDIGO             |      EMOJI       | DESCRIÇÃO                              |
| :----------------- | :--------------: | :------------------------------------- |
| `:bookmark:`       |    :bookmark:    | Tags de versão.                        |
| `:bow_and_arrow:`  | :bow_and_arrow:  | Adicionar, atualizar ou remover metas. |
| `:checkered_flag:` | :checkered_flag: | Iniciar um projeto.                    |
| `:dart:`           |      :dart:      | Metas concluídas.                      |
| `:tada:`           |      :tada:      | Commit inicial.                        |

---

### Segurança e Privacidade

Correções de problemas de segurança e privacidade.

| CÓDIGO   | EMOJI  | DESCRIÇÃO                          |
| :------- | :----: | :--------------------------------- |
| `:eye:`  | :eye:  | Corrigir problemas de privacidade. |
| `:lock:` | :lock: | Corrigir problemas de segurança.   |

---

### Revisão de Código

Ações relacionadas a revisão e análise de alterações no código.

| CÓDIGO   | EMOJI  | DESCRIÇÃO                     |
| :------- | :----: | :---------------------------- |
| `:eyes:` | :eyes: | Revisar alterações de código. |

---

### Limpeza de Código

Limpeza e depreciação de código obsoleto.

| CÓDIGO          |     EMOJI     | DESCRIÇÃO                                 |
| :-------------- | :-----------: | :---------------------------------------- |
| `:broom:`       |    :broom:    | Realizar limpeza de código.               |
| `:wastebasket:` | :wastebasket: | Depreciar o código que precisa ser limpo. |

---

### Otimização de Código

Otimizações para melhorar o desempenho do código.

| CÓDIGO                         |            EMOJI             | DESCRIÇÃO                          |
| :----------------------------- | :--------------------------: | :--------------------------------- |
| `:chart_with_downwards_trend:` | :chart_with_downwards_trend: | Otimizar o código para desempenho. |

---

## Operações de Banco de Dados

Migrações e outras ações relacionadas a bancos dados.

| CÓDIGO          |     EMOJI     | DESCRIÇÃO                             |
| :-------------- | :-----------: | :------------------------------------ |
| `:cd:`          |     :cd:      | Realizar migrações de banco de dados. |
| `:floppy_disk:` | :floppy_disk: | Realizar backup de banco de dados.    |

---

## Integração / Implantação Contínua

Ações relacionadas a implantação e integração contínua.

| CÓDIGO     |  EMOJI   | DESCRIÇÃO                  |
| :--------- | :------: | :------------------------- |
| `:rocket:` | :rocket: | Implantar funcionalidades. |

---

## Assinatura / Verificação de Código

Assinatura e verificação de assinaturas de código.

| CÓDIGO      |   EMOJI   | DESCRIÇÃO                                   |
| :---------- | :-------: | :------------------------------------------ |
| `:old_key:` | :old_key: | Atualizar assinaturas de código.            |
| `:key:`     |   :key:   | Assinar ou verificar assinaturas de código. |

---

## Reversão de Código

Reversão de alterações feitas no código.

| CÓDIGO     |  EMOJI   | DESCRIÇÃO            |
| :--------- | :------: | :------------------- |
| `:rewind:` | :rewind: | Reverter alterações. |

---

## Correção Rápida de Código

Correções emergenciais de código.

| CÓDIGO               |       EMOJI        | DESCRIÇÃO                                          |
| :------------------- | :----------------: | :------------------------------------------------- |
| `:adhesive_bandage:` | :adhesive_bandage: | Aplicar uma correção temporária.                   |
| `:ambulance:`        |    :ambulance:     | Solução rápida para um problema.                   |
| `:fire_engine:`      |   :fire_engine:    | Resposta rápida para combater problemas no código. |
| `:toolbox:`          |     :toolbox:      | Atividades de manutenção do código.                |

---

## Alterações de Configuração

Atualizações e adições de configurações.

| CÓDIGO           |     EMOJI      | DESCRIÇÃO                                                  |
| :--------------- | :------------: | :--------------------------------------------------------- |
| `:bar_chart:`    |  :bar_chart:   | Analisar e ajustar configurações com base em dados.        |
| `:gear:`         |     :gear:     | Adicionar, atualizar ou remover configurações.             |
| `:level_slider:` | :level_slider: | Adicionar ou ajustar a configurações em diferentes níveis. |

---

## Atualização de Segurança de Dependências

Atualizações de dependências por motivos de segurança.

| CÓDIGO             |      EMOJI       | DESCRIÇÃO                                                            |
| :----------------- | :--------------: | :------------------------------------------------------------------- |
| `:rotating_light:` | :rotating_light: | Uma atualização urgente para lidar com vulnerabilidade crítica.      |
| `:no_entry_sign:`  | :no_entry_sign:  | Uma versão anterior da dependência possui vulnerabilidade conhecida. |
| `:shield:`         |     :shield:     | Atualizar dependência por motivo de segurança.                       |
| `:warning:`        |    :warning:     | Uma situação de risco requer atualização de segurança.               |

---

## Operações de Controle de Versão

Ações relacionadas ao controle de versão.

| CÓDIGO                      |           EMOJI           | DESCRIÇÃO                                              |
| :-------------------------- | :-----------------------: | :----------------------------------------------------- |
| `:arrows_counterclockwise:` | :arrows_counterclockwise: | Reverter ou desfazer alterações no controle de versão. |

---

## Gerenciamento de Arquivos e Pastas

Adição, atualização e remoção de arquivos e pastas.

| CÓDIGO               |       EMOJI        | DESCRIÇÃO                                |
| :------------------- | :----------------: | :--------------------------------------- |
| `:open_file_folder:` | :open_file_folder: | Adicionar pasta.                         |
| `:page_facing_up:`   |  :page_facing_up:  | Adicionar arquivo.                       |
| `:page_with_curl:`   |  :page_with_curl:  | Atualizar conteúdo do arquivo.           |
| `:scroll:`           |      :scroll:      | Adicionar, atualizar ou remover licença. |
| `:wastebasket:`      |   :wastebasket:    | Remover pasta ou arquivo.                |

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

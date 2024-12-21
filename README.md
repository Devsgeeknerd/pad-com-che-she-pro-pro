<!-- Título -->

# Padrões de Commits

## Introdução

Este documento define os padrões de commits a serem seguidos (para meus repositórios), utilizando emojis para
representar diferentes tipos de alterações no código.

Seguir um padrão de commits me ajuda a manter a clareza e a consistência nas mensagens, facilitando a identificação do
tipo de alteração realizada e melhorando a identificação entre os desenvolvedores.

## Categorias de Commits

As seguintes categorias devem (ou não) ser usadas para classificar as alterações no código:

### Chore

`Chore` é uma categoria de tarefas que envolvem manutenção, organização e melhorias no código ou na infraestrutura do
projeto.

Essas tarefas são essências para garantir que o projeto continue a funcionar de maneira eficiente e que a base de código
permaneça limpa e gerenciável.

#### Exemplo de tarefas Chore

* **Atualização de dependências**: Manter bibliotecas e pacotes atualizados para garantir segurança e compatibilidade.

* **Refatoração de código**: Melhorar a estrutura do código existente sem alterar seu comportamento externo, visando
  aumentar a legibilidade e a manutenibilidade.

* **Limpeza de código**: Remover código não utilizado, comentários obsoletos ou arquivos desnecessários.

* **Configuração de ferramentas**: Configurar ou atualizar ferramentas de desenvolvimento, como linters, formatadores de
  código ou sistemas de integração contínua.

* **Documentação**: Atualizar ou criar documentação do projeto, incluindo README, guias de contribuição e comentários no
código.

* **Testes**: Adicionar ou melhorar testes automatizados para garantir que o código funcione conforme o esperado.

* **Configuração de ambiente**: Ajustar configurações de ambiente de desenvolvimento ou produção, como variáveis de
ambiente ou arquivos de configurações.

* **Gerenciamento de issues**: Organizar e priorizar tarefas e bugs no sistema de rastreamento de problemas.

#### Importância do Chore

* **Manutenção da qualidade do código**: Tarefas que ajudam a manter a qualidade do código, evitando a acumulação de
dívidas técnicas.

* **Facilitação de novas funcionalidades**: Um código limpo e bem organizado facilita a implementação de novas
funcionalidades e a correção de bugs.

* **Segurança**: Atualizações regulares de dependências e a remoção de código obsoleto ajudam a proteger o projeto contra
vulnerabilidades.

* **Colaboração**: Uma boa documentação e um código bem estruturado tornam mais fácil para novos desenvolvedores
entenderem e contribuírem para o projeto.

#### Conclusão do Chore

O escopo "chore" é uma parte vital do ciclo de vida de desenvolvimento de software.

Embora essas tarefas possam não parecer tão emocionantes quando a implementação de novas funcionalidades, elas são
essenciais para a saúde a longo prazo do projeto.

Ignorar as tarefas "chore" pode levar a problemas maiores no futuro, como aumento da complexidade do código,
dificuldades na colaboração e riscos de segurança.

Portanto, é importante que as equipes de desenvolvimento reconheçam e priorizem essas atividades em seu fluxo de
trabalho.

---

### Feat

`Feat` é uma categoria de commits ou tarefas que introduzem novas funcionalidades ou melhorias que agregam valor ao
produto final.

Amplamente utilizado no desenvolvimento de software, especialmente em práticas de controle de versão e metologias ágeis.

Ele se refere a "feature" (funcionalidade, em português) e abrange a implementação de novas funcionalidades ou melhorias
significativas em um sistema ou aplicativo.

Essas mudanças são geralmente visíveis para os usuários e podem impactar diretamente a experiência do usuário ou a
capacidade do sistema.

#### Exemplo de tarefas Feat

* **Implementação de novas funcionalidades**: Adicionar uma nova funcionalidade ao aplicativo, como um sistema de
autenticação, um novo módulo de relatórios ou uma nova interface de usuário.

* **Melhorias em funcionalidades existentes**: Aprimorar uma funcionalidade já existente, como otimizar um algoritmo de
busca ou melhorar a usabilidade de um formulário.

* **Integração com APIs Externas**: Conectar o sistema a serviços externos, como APIs de pagamento, redes sociais ou
serviços de geolocalização.

* **Adição de novos componentes de UI**: Criar novos componentes de interface do usuário que melhorem a experiência do
usuário, como menus, botões ou modais.

* **Suporte a novas plataformas**: Expandir o aplicativo para suportar novas plataformas, como versões desktop ou web.

* **Implementação de funcionalidades de acessibilidade**: Adicionar recursos que tornam o aplicativo mais acessível a
usuários com deficiência, com suporte a leitores de tela ou navegação por teclado.

#### Importância do Feat

* **Valor para o usuário**: Funcionalidades novas e aprimoradas são essenciais para atender às necessidades dos usuários e
melhorar a experiência geral.

* **Competitividade**: A introdução de novas funcionalidades pode diferenciar um produto no mercado, tornando-o mais
atraente em comparação com concorrentes.

* **Feedback do usuário**: Novas funcionalidades frequentemente resultam em feedback dos usuários, que pode ser utilizado
para futuras melhorias e iterações.

* **Crescimento do produto**: A adição de funcionalidades pode abrir novas oportunidades de mercado e expandir a base de
usuários.

#### Conclusão do Feat

O escopo "feat" é fundamental para o desenvolvimento de software, pois representa o avanço e a evolução de um produto.

As equipes de desenvolvimento devem priorizar a implementação de novas funcionalidades com base nas necessidades dos
usuários, nas tendencias do mercado e nas metas do produto.

Além disso, é importante que as funcionalidades sejam bem planejadas, testadas e documentadas para garantir que atendam
aos padrões de qualidade e proporcionem uma experiência positiva ao usuário.

A gestão eficaz de tarefas "feat" é crucial para o sucesso a longo prazo de qualquer projeto de software.

---

### Fix

`Fix` é a categoria usada para correcoes de bugs no codigo, garatindo que o sistema funcione conforme esperado.

#### Exemplo de tarefas Fix

* **Correcao de erros de logica**: Resolver problemas que impedem o funcionamento correto do sistema.
* **Ajustes em funcionalidades existentes**: Corrigir falhas em recursos previamente implementados.
* **Reparos em testes automatizados**: Garantir que os testes reflitam o comportamento esperando.

---

### Refactor

`Refactor` é usado para alteracoes que melhoram a estrtura do codigo sem impactar seu comportamento externo. Essas mudancas focam tornar o codigo mais legivel e sustentavel.

---

### Test

`Test` é reservado para commits relacionados a criacao, atualizacao ou exclusao de testes automatizados.

---

### Docs

`Docs` refere-se a alteracoes na docuemntacao do proejto, como atualiacoes no README ou comentarios no coidgo.

---

### Perf

`Perf` é usado para otimizacoes de desempenho, garatindo que o sistema funcione de forma mais eficiente.

---

### Style

`Style` abrange mudancas puramente esteticas no codigo, como formatacao ou ajustes em espacamento, sem impacto funcional.

---

### CI

`CI` é usado para alteracoes em scripts e configuracoes de integracao continua.

---

### Hotfix

`Hotfix` refere-se a correcoes rapidas e emergenciais de erros criticos em producao.
---

### Build

---

### Improvement

---

### Security

---

### UI

---

### API

---

### Locale

---

### Config

---

### Data

---

### Exemplos de Commits

Aqui estão alguns exemplos de commits que podem ser adaptados em vez do padrão já definido neste documento:

`emoji categoria(tipo): descrição.`

* :heavy_plus_sign: chore(deps): Adiciona Riverpod para gerenciamento de estado.

  * (Opcional): Inclui o package Riverpod para gerenciamento de estado global no aplicativo e atualiza a documentação
    para refletir essa nova dependência.

## Dicas de Uso

* Use de forma moderada e apenas quando fizer sentido para a alteração.
* Certifique-se de que a descrição do commit seja clara e concisa, explicado o que foi alterado.
* Mantenha um padrão consistente em todos os repositórios e projetos para facilitar a leitura e compreensão das
  mensagens de commit.

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

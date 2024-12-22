<!-- Título -->
# Padrões de Commits

## Introdução

Este documento define os padrões de commits a serem seguidos em meus repositórios, utilizando emojis para representar diferentes tipos de alterações no código.

Seguir um padrão de commits ajuda a manter a clareza e a consistência nas mensagens, facilitando a identificação do tipo de alteração realizada e promovendo uma melhor colaboração entre desenvolvedores.

## Categorias de Commits

As seguintes categorias devem ser usadas para classificar as alterações no código:

### Chore

`Chore` é a categoria para tarefas relacionadas à manutenção, organização e melhorias no código ou na infraestrutura do projeto.

Embora essas tarefas não resultem em mudanças visíveis para os usuários, elas são essenciais para a saúde do projeto a longo prazo.

Essas tarefas são essências para garantir que o projeto continue a funcionar de maneira eficiente e que a base de código permaneça limpa e gerenciável.

#### Exemplo de tarefas Chore

* **Atualização de dependências**: Garantir que bibliotecas e pacotes estejam atualizados para maior segurança e compatibilidade.

* **Refatoração de código**: Melhorar a estrutura do código sem alterar seu comportamento externo, aumentando a legibilidade e a manutenção.

* **Limpeza de código**: Remover código não utilizado, comentários desnecessários ou arquivos obsoletos.

* **Configuração de ferramentas**: Configurar ou atualizar ferramentas de desenvolvimento, como linters ou sistemas de CI/CD.

* **Documentação**: Atualizar ou criar documentação do projeto, como guias de contribuição e comentários no código.

* **Testes**: Adicionar ou melhorar testes automatizados para garantir a funcionalidade do código.

* **Configuração de ambiente**: Ajustar configurações do ambiente de desenvolvimento ou produção, como variáveis de ambiente.

* **Gerenciamento de issues**: Organizar e priorizar tarefas e bugs no sistema de rastreamento de problemas.

#### Importância do Chore

* **Manutenção da qualidade do código**: Previne o acúmulo de dívidas técnicas.

* **Facilidade para novas funcionalidades**: Um código limpo facilita a adição de novas funcionalidades e correções de bugs.

* **Segurança**: Atualizações de dependências reduzem vulnerabilidades.

* **Colaboração**: Boa documentação e estrutura de código ajudam novos desenvolvedores a se integrarem mais facilmente ao projeto.

---

### Feat

`Feat` é a categoria para commits que introduzem novas funcionalidades ou melhorias significativas no produto. Essas mudanças agregam valor direto ao usuário final e são frequentemente visíveis.

#### Exemplo de tarefas Feat

* **Implementação de novas funcionalidades**: Adicionar sistemas como autenticação ou relatórios.

* **Melhorias em funcionalidades existentes**: Otimizar algoritmos ou melhorar a usabilidade de interfaces.

* **Integração com APIs externas**: Conectar o sistema a serviços externos, como APIs de pagamento ou redes sociais.

* **Adição de novos componentes de UI**: Criar elementos que melhorem a experiência do usuário.

* **Suporte a novas plataformas**: Expandir o sistema para novas plataformas, como versões web ou desktop.

* **Funcionalidades de acessibilidade**: Tornar o aplicativo mais acessível para usuários com deficiência.

#### Importância do Feat

* **Valor para o usuário**: Atende às necessidades dos usuários e melhora a experiência geral.

* **Competitividade**: Diferencia o produto no mercado, aumentando sua atratividade.

* **Feedback do usuário**: Novas funcionalidades geram feedback valioso para futuras melhorias.

* **Crescimento do produto**: Expande oportunidades de mercado e base de usuários.

---

### Fix

`Fix` é a categoria usada para correções de bugs no código, garantindo que o sistema funcione conforme esperado.

#### Exemplo de tarefas Fix

* **Correção de erros de lógica**: Resolver problemas que impedem o funcionamento correto do sistema.

* **Ajustes em funcionalidades existentes**: Corrigir falhas em recursos previamente implementados.

* **Reparos em testes automatizados**: Garantir que os testes reflitam o comportamento esperado.

---

### Refactor

`Refactor` é usado para alterações que melhoram a estrutura do código sem impactar seu comportamento externo. Essas mudanças focam em tornar o código mais legível e sustentável.

---

### Test

`Test` é reservado para commits relacionados à criação, atualização ou exclusão de testes automatizados.

---

### Docs

`Docs` refere-se a alterações na documentação do projeto, como atualizações no README ou comentários no código.

---

### Perf

`Perf` é usado para otimizações de desempenho, garantindo que o sistema funcione de forma mais eficiente.

---

### Style

`Style` abrange mudanças puramente estéticas no código, como formatação ou ajustes em espaçamento, sem impacto funcional.

---

### CI

`CI` é usado para alterações em scripts e configurações de integração contínua.

---

### Hotfix

`Hotfix` refere-se a correções rápidas e emergenciais de erros críticos em produção.

---

### Build

`Build` é para alterações que impactam o sistema de build, como scripts de compilação ou dependências.

---

### Improvement

`Improvement` é reservado para melhorias incrementais em funcionalidades existentes, sem introduzir novas funcionalidades.

---

### Security

`Security` cobre mudanças voltadas à segurança, como correções de vulnerabilidades ou melhorias na autenticação.

---

### UI

`UI` é usado para alterações na interface do usuário, incluindo ajustes de design e experiência visual.

---

### API

`API` refere-se a mudanças nas interfaces de programação do sistema, como ajustes em endpoints ou contratos.

---

### Locale

`Locale` cobre alterações relacionadas a localização e internacionalização, como adição de traduções ou ajustes de idioma.

---

### Config

`Config` é para mudanças em configurações do projeto, como ajustes em arquivos de configuração.

---

### Data

`Data` abrange alterações em bancos de dados, como scripts de migração ou ajustes no esquema.

---

### Exemplos de Commits

Aqui estão alguns exemplos de commits que seguem este padrão:

`emoji categoria(tipo): descrição.`

* `:sparkles: feat(auth): adiciona sistema de autenticação com JWT.`

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

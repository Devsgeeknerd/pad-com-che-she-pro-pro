<!-- Título -->
# Padrões de Commits :rocket:

## :pushpin: Introdução

Este documento define um padrão de commits para manter **clareza, consistência e eficiência** nos repositórios.

O uso de **emojis** facilita a identificação visual do tipo de alteração realizada, promovendo melhor colaboração e organização.

---

## :file_folder: Categorias de Commits

### :hammer_and_wrench: Chore

Alterações de manutenção e organização que não impactam diretamente a funcionalidade do projeto.

#### Exemplo de tarefas Chore

* :white_check_mark: Alterações nas configurações de segurança, como TLS/SSL.
* :white_check_mark: Ajuste de configurações de cache.
* :white_check_mark: Ajuste na configuração de pre-commit hooks.
* :white_check_mark: Ajuste no arquivo .gitignore.
* :white_check_mark: Ajustes de ambiente de desenvolvimento.
* :white_check_mark: Ajustes nas configurações de deploy.
* :white_check_mark: Atualização de bibliotecas de análise estática de código.
* :white_check_mark: Atualização de dependências.
* :white_check_mark: Atualização de documentação interna.
* :white_check_mark: Atualização de versões.
* :white_check_mark: Configuração de backup de banco de dados.
* :white_check_mark: Configuração de ferramentas como linters e CI/CD.
* :white_check_mark: Inclusão de novas variáveis de ambiente.
* :white_check_mark: Limpeza de código morto.
* :white_check_mark: Limpeza de logs antigos.
* :white_check_mark: Melhoria no processo de build.
* :white_check_mark: Organização de arquivos de configuração.
* :white_check_mark: Refatoração de estrutura de pastas.
* :white_check_mark: Remoção de dependências não utilizadas.
* :white_check_mark: Revisão de arquivos de configuração de ambiente (dev, prod, test).

:pushpin: **Exemplo de commit**:

> :hammer_and_wrench: chore(analysis): atualiza ferramentas de análise estática de código.
>
> :hammer_and_wrench: chore(build): melhora processo de build com novos scripts.
>
> :hammer_and_wrench: chore(cache): ajusta configurações de cache para melhorar o desempenho.
>
> :hammer_and_wrench: chore(cleanup): remove dependências não utilizadas do projeto.
>
> :hammer_and_wrench: chore(deploy): ajusta configurações de deploy para integração contínua.
>
> :hammer_and_wrench: chore(deps): atualiza dependências para a versão mais recente.
>
> :hammer_and_wrench: chore(gitignore): ajusta o arquivo .gitignore para excluir novos arquivos temporários.
>
> :hammer_and_wrench: chore(hooks): adiciona e configura pre-commit hooks no projeto.
>
> :hammer_and_wrench: chore(logs): limpa logs antigos que não são mais necessários.
>
> :hammer_and_wrench: chore(security): atualiza configurações de segurança para reforçar TLS/SSL.
>
> :hammer_and_wrench: chore(structure): refatora estrutura de pastas para melhor organização.
>
> :hammer_and_wrench: chore(tests): atualiza bibliotecas de testes para versões mais recentes.
>
> :hammer_and_wrench: chore(env): revisa arquivos de configuração de ambiente para otimização.
>
> :hammer_and_wrench: chore(backup): configura backup automático do banco de dados.

---

### :sparkles: Feat

Adição de novas funcionalidades ou melhorias que agregam valor ao usuário.

#### Exemplos de tarefas Feat

* :white_check_mark: Implementação de novas funcionalidades.
* :white_check_mark: Melhorias na UI/UX.
* :white_check_mark: Suporte a novos dispositivos ou plataformas.
* :white_check_mark: Integração com APIs externas.
* :white_check_mark: Implementação de funcionalidades de notificação.
* :white_check_mark: Implementação de novas opções de personalização.
* :white_check_mark: Adição de novas opções de compartilhamento.
* :white_check_mark: Implementação de funcionalidades para melhoria de desempenho.
* :white_check_mark: Adição de novos tipos de conteúdo.
* :white_check_mark: Suporte a novas linguagens ou traduções.
* :white_check_mark: Implementação de novos tipos de busca.
* :white_check_mark: Introdução de novas ferramentas de edição.
* :white_check_mark: Criação de novos relatórios ou dashboards.
* :white_check_mark: Implementação de funcionalidades de acessibilidade.

:pushpin: **Exemplo de commit**:

> :sparkles: feat(auth): adicionar sistema de autenticação JWT.
>
> :sparkles: feat(notifications): adicionar notificações push para novos conteúdos.
>
> :sparkles: feat(theme): permitir que usuários escolham temas personalizados no app.
>
> :sparkles: feat(sharing): integrar com Facebook e Twitter para compartilhamento.
>
> :sparkles: feat(performance): otimizar carregamento de imagens para melhor desempenho.
>
> :sparkles: feat(content): adicionar suporte para vídeos na seção de conteúdo interativo.
>
> :sparkles: feat(language): adicionar suporte ao idioma espanhol.
>
> :sparkles: feat(search): adicionar funcionalidade de busca por voz.
>
> :sparkles: feat(editing): adicionar filtro de imagem para edição de fotos.
>
> :sparkles: feat(dashboards): criar novos relatórios interativos para análise de dados.

---

### :lady_beetle: Fix

Correção de **bugs** que impactam o funcionamento esperado do sistema.

#### Exemplos de tarefas Fix

* :white_check_mark: Correção de erros de lógica.
* :white_check_mark: Ajustes em validações.
* :white_check_mark: Correção de falhas na interface.
* :white_check_mark: Ajustes em mensagens de erro.
* :white_check_mark: Correção de bugs na interface do usuário.
* :white_check_mark: Correção de bugs de segurança.
* :white_check_mark: Correção de bugs de performance.
* :white_check_mark: Correção de bugs em validações de entrada.
* :white_check_mark: Correção de comportamentos inesperados em funcionalidades.
* :white_check_mark: Ajustes em interações do usuário que não funcionam como esperado.

:pushpin: **Exemplo de commit**:

> :lady_beetle: fix(api): corrige validação de email.
>
> :lady_beetle: fix(auth): corrige erro de autenticação.
>
> :lady_beetle: fix(interface): corrige falha na exibição de botões.
>
> :lady_beetle: fix(validation): ajusta validação de campos obrigatórios.
>
> :lady_beetle: fix(error-messages): corrige mensagens de erro exibidas ao usuário.
>
> :lady_beetle: fix(security): corrige vulnerabilidade de segurança em formulários.
>
> :lady_beetle: fix(performance): corrige lentidão em carregamento de dados.
>
> :lady_beetle: fix(user-input): corrige erro ao processar entrada do usuário.
>
> :lady_beetle: fix(tests): corrige falhas em testes automatizados.
>
> :lady_beetle: fix(compatibility): corrige problemas de compatibilidade com navegadores.

---

### :ambulance: Hotfix

Correções **críticas e emergenciais** que precisam ser aplicadas imediatamente.

#### Exemplos de tarefas Hotfix

* :white_check_mark: Resolver erro crítico em produção.
* :white_check_mark: Ajustes rápidos de segurança.
* :white_check_mark: Correção de bugs de segurança.
* :white_check_mark: Correção de bugs de performance.
* :white_check_mark: Correção de bugs em validações.
* :white_check_mark: Correção de bugs em interfaces.
* :white_check_mark: Correção de bugs que causam falhas em produção.
* :white_check_mark: Correção de bugs em arquivos de configuração que afetam a execução.
* :white_check_mark: Correção de bugs que impedem o funcionamento de funcionalidades críticas.
* :white_check_mark: Correção de bugs que causam perda de dados.

:pushpin: **Exemplo de commit**:

> :ambulance: hotfix(login): corrige erro impedindo login de usuários.
>
> :ambulance: hotfix(api): corrige erro impedindo a execução de tarefas.
>
> :ambulance: hotfix(security): corrige vulnerabilidade crítica de segurança.
>
> :ambulance: hotfix(performance): corrige erro que causa lentidão no sistema.
>
> :ambulance: hotfix(validation): corrige erro em validações de entrada.
>
> :ambulance: hotfix(interface): corrige erro de exibição na interface do usuário.
>
> :ambulance: hotfix(config): corrige erro em arquivo de configuração que impede a inicialização.
>
> :ambulance: hotfix(data-loss): corrige bug que causa perda de dados em operações.
>
> :ambulance: hotfix(dependency): corrige erro causado por dependência desatualizada.
>
> :ambulance: hotfix(test): corrige erro em testes que falham em produção.

---

### :art: Style

Mudanças **cosméticas** no código que não afetam a funcionalidade.

#### Exemplos de tarefas Style

* :white_check_mark: Ajustes de indentação e espaçamentos.
* :white_check_mark: Correção de formatação de código.
* :white_check_mark: Alterações em estilos de CSS.
* :white_check_mark: Ajustes de cores em elementos da interface.
* :white_check_mark: Ajustes de tamanhos de fonte.
* :white_check_mark: Ajustes de layouts responsivos.
* :white_check_mark: Melhoria na acessibilidade visual.
* :white_check_mark: Padronização de nomenclaturas de classes e IDs.
* :white_check_mark: Ajustes de margens e preenchimentos.
* :white_check_mark: Atualização de ícones e imagens.

:pushpin: **Exemplo de commit**:

> :art: style(ui): ajusta espaçamento entre botões.
>
> :art: style(css): corrige formatação de CSS.
>
> :art: style(colors): altera cores de fundo e texto.
>
> :art: style(fonts): ajusta tamanhos de fonte para melhor legibilidade.
>
> :art: style(layout): melhora layout responsivo para dispositivos móveis.
>
> :art: style(accessibility): melhora acessibilidade visual.
>
> :art: style(naming): padroniza nomenclaturas de classes e IDs.
>
> :art: style(margins): ajusta margens e preenchimentos em componentes.
>
> :art: style(icons): atualiza ícones para nova versão.
>
> :art: style(images): substitui imagens por versões otimizadas.

---

### :arrows_counterclockwise: Refactor

Melhorias na **estrutura do código** sem alterar seu comportamento.

#### Exemplos de tarefas Refactor

* :white_check_mark: Melhor organização do código.
* :white_check_mark: Melhoria na modularização do código.
* :white_check_mark: Redução de complexidade de código.
* :white_check_mark: Redução de duplicação de código.
* :white_check_mark: Simplificação de funções complexas.
* :white_check_mark: Renomeação de variáveis e funções para melhor clareza.
* :white_check_mark: Extração de métodos para melhorar a legibilidade.
* :white_check_mark: Reorganização de arquivos e pastas para melhor estrutura.
* :white_check_mark: Melhoria na documentação interna do código.
* :white_check_mark: Implementação de padrões de design para melhor manutenção.

:pushpin: **Exemplo de commit**:

> :arrows_counterclockwise: refactor(user-service): melhora a modularização do código.
>
> :arrows_counterclockwise: refactor(algoritmo): simplifica função de cálculo.
>
> :arrows_counterclockwise: refactor(variable): renomeia variáveis para melhor clareza.
>
> :arrows_counterclockwise: refactor(methods): extrai método para reduzir complexidade.
>
> :arrows_counterclockwise: refactor(structure): reorganiza arquivos para melhor estrutura.
>
> :arrows_counterclockwise: refactor(documentation): melhora documentação interna do código.
>
> :arrows_counterclockwise: refactor(design-patterns): implementa padrões de design para manutenção.

---

### :wastebasket: Cleanup

Limpeza de código desnecessário ou **removido**.

#### Exemplos de tarefas Cleanup

* :white_check_mark: Remoção de código obsoleto.
* :white_check_mark: Exclusão de arquivos não utilizados.
* :white_check_mark: Redução de complexidade de código.
* :white_check_mark: Remoção de comentários desatualizados ou irrelevantes.
* :white_check_mark: Exclusão de testes não utilizados.
* :white_check_mark: Limpeza de imports não utilizados.
* :white_check_mark: Remoção de variáveis não utilizadas.
* :white_check_mark: Refatoração de código para melhorar a clareza.
* :white_check_mark: Remoção de configurações desnecessárias.
* :white_check_mark: Exclusão de documentação obsoleta.

:pushpin: **Exemplo de commit**:

> :wastebasket: cleanup(legacy): remove métodos não utilizados.
>
> :wastebasket: cleanup(legacy): remove funções obsoletas.
>
> :wastebasket: cleanup(files): remove arquivos não utilizados.
>
> :wastebasket: cleanup(folders): remove pastas não utilizadas.
>
> :wastebasket: cleanup(dependencies): remove dependências não utilizadas.
>
> :wastebasket: cleanup(temporary): remove arquivos temporários.
>
> :wastebasket: cleanup(comments): remove comentários desatualizados.
>
> :wastebasket: cleanup(test): remove testes não utilizados.
>
> :wastebasket: cleanup(imports): limpa imports não utilizados.
>
> :wastebasket: cleanup(variable): remove variáveis não utilizadas.

---

### :racing_car: Perf

Otimizações de **desempenho** para melhorar a eficiência do código.

#### Exemplos de tarefas Perf

* :white_check_mark: Redução do tempo de execução de um algoritmo.
* :white_check_mark: Melhor uso de recursos do sistema.
* :white_check_mark: Redução de consumo de energia.
* :white_check_mark: Melhoria na eficiência de consultas a banco de dados.
* :white_check_mark: Otimização de operações de leitura e escrita em disco.
* :white_check_mark: Redução do tempo de carregamento de páginas.
* :white_check_mark: Implementação de caching para melhorar a performance.
* :white_check_mark: Refatoração de código para melhorar a legibilidade e eficiência.
* :white_check_mark: Melhoria na paralelização de tarefas.
* :white_check_mark: Análise e eliminação de gargalos de desempenho.

:pushpin: **Exemplo de commit**:

> :racing_car: perf(algoritmo): otimiza busca para reduzir tempo de execução.
> :racing_car: perf(banco-de-dados): melhora a eficiência de consultas.
> :racing_car: perf(disco): otimiza operações de leitura e escrita em disco.
> :racing_car: perf(paginas): reduz o tempo de carregamento de páginas.
> :racing_car: perf(caching): implementa caching para melhorar a performance.
> :racing_car: perf(paralelizacao): melhora a paralelização de tarefas.
> :racing_car: perf(gargalos): analisa e elimina gargalos de desempenho.
> :racing_car: perf(refatoracao): refatora código para melhorar eficiência.

---

### :test_tube: Test

Adição, atualização e remoção de **testes automatizados**.

#### Exemplos de tarefas Test

* :white_check_mark: Criação de novos testes unitários.
* :white_check_mark: Criação de novos testes de integração.
* :white_check_mark: Remoção de testes obsoletos.
* :white_check_mark: Correção de testes falhos.
* :white_check_mark: Melhoria na cobertura de testes.
* :white_check_mark: Melhoria na qualidade de testes.
* :white_check_mark: Melhoria na velocidade de execução dos testes.
* :white_check_mark: Refatoração de testes existentes para melhor legibilidade.
* :white_check_mark: Adição de testes de performance.
* :white_check_mark: Implementação de testes de regressão.

:pushpin: **Exemplo de commit**:

> :test_tube: test(auth): adiciona testes unitários para autenticação.
> :test_tube: test(auth): corrige teste falho de autenticação.
> :test_tube: test(user-service): adiciona testes unitários para autorização.
> :test_tube: test(user-service): adiciona testes de integração para cadastro de usuários.
> :test_tube: test(user-service): remove testes obsoletos de login de usuários.
> :test_tube: test(user-service): melhora cobertura de testes para atualização de usuários.
> :test_tube: test(performance): adiciona testes de performance para a API.
> :test_tube: test(regression): implementa testes de regressão para funcionalidades críticas.

---

### :book: Docs

Alterações na **documentação** do projeto.

#### Exemplos de tarefas Docs

* :white_check_mark: Atualização do README.
* :white_check_mark: Atualização de documentação de funcionalidades.
* :white_check_mark: Adição de exemplos de uso.
* :white_check_mark: Comentários no código.
* :white_check_mark: Documentação de APIs.
* :white_check_mark: Criação de guias de contribuição.
* :white_check_mark: Atualização de changelog.
* :white_check_mark: Melhoria na estrutura da documentação.
* :white_check_mark: Adição de diagramas e ilustrações.
* :white_check_mark: Revisão de documentação existente para clareza.

:pushpin: **Exemplo de commit**:

> :book: docs(README): atualiza guia de instalação.
> :book: docs(features): atualiza documentação de funcionalidades.
> :book: docs(examples): adiciona exemplos de uso.
> :book: docs(code-comments): adiciona comentários no código.
> :book: docs(api-documentation): documenta APIs.
> :book: docs(contributing): cria guia de contribuição.
> :book: docs(changelog): atualiza changelog.
> :book: docs(structure): melhora estrutura da documentação.
> :book: docs(diagrams): adiciona diagramas e ilustrações.
> :book: docs(review): revisa documentação existente para clareza.

---

### :lock: Security

Correções e melhorias à **segurança** do projeto.

#### Exemplos de tarefas Security

* :white_check_mark: Correção de vulnerabilidade.
* :white_check_mark: Melhoria na segurança da aplicação.
* :white_check_mark: Melhorias na autenticação e autorização.
* :white_check_mark: Implementação de criptografia para dados sensíveis.
* :white_check_mark: Melhoria no tratamento de erros para evitar vazamento de informações.
* :white_check_mark: Implementação de validações de entrada para prevenir injeções.
* :white_check_mark: Atualização de dependências para versões seguras.
* :white_check_mark: Revisão de permissões de acesso.
* :white_check_mark: Implementação de logs de segurança.
* :white_check_mark: Melhoria na configuração de CORS.
* :white_check_mark: Implementação de medidas contra ataques de força bruta.
* :white_check_mark: Melhoria na segurança de sessões.

:pushpin: **Exemplo de commit**:

> :lock: security(auth): corrige vulnerabilidade no token JWT.
> :lock: security(auth): melhora autenticação e autorização.
> :lock: security(encryption): implementa criptografia para dados sensíveis.
> :lock: security(error-handling): melhora tratamento de erros para evitar vazamento de informações.
> :lock: security(input-validation): implementa validações de entrada para prevenir injeções.
> :lock: security(dependencies): atualiza dependências para versões seguras.
> :lock: security(permissions): revisa permissões de acesso.
> :lock: security(logging): implementa logs de segurança.
> :lock: security(cors): melhora configuração de CORS.
> :lock: security(brute-force): implementa medidas contra ataques de força bruta.
> :lock: security(sessions): melhora segurança de sessões.

---

### :package: Build

Mudança no sistema de **build** do projeto.

#### Exemplos de tarefas Build

* :white_check_mark: Ajuste em scripts de compilação.
* :white_check_mark: Ajuste em configurações de build.
* :white_check_mark: Atualização de dependências de build.
* :white_check_mark: Ajuste em scripts de testes automatizados.
* :white_check_mark: Configuração de variáveis de ambiente para build.
* :white_check_mark: Ajuste em configurações de deploys.
* :white_check_mark: Ajuste em scripts de linting.
* :white_check_mark: Ajuste em scripts de formatação de código.
* :white_check_mark: Ajuste em configurações de segurança no build.
* :white_check_mark: Ajuste em configurações de cache para builds.
* :white_check_mark: Ajuste em configurações de pre-commit hooks.
* :white_check_mark: Criação de novos arquivos de configuração de build.
* :white_check_mark: Remoção de arquivos de configuração obsoletos.
* :white_check_mark: Atualização de documentação relacionada ao processo de build.
* :white_check_mark: Implementação de novos plugins para otimização de build.
* :white_check_mark: Ajuste em scripts de integração contínua.

:pushpin: **Exemplo de commit**:

> :package: build(webpack): ajusta configuração para otimizar bundle.
> :package: build(webpack): criação de novo plugin para otimização de build.
> :package: build(webpack): ajusta scripts de build.
> :package: build(webpack): ajusta configuração de cache.

---

### :gear: Config

Alterações em **configurações** do projeto.

#### Exemplos de tarefas Config

* :white_check_mark: Modificações em arquivos de configuração.
* :white_check_mark: Ajustes de variáveis de ambiente.
* :white_check_mark: Atualização de configurações de sistema de gerenciamento de pacotes.
* :white_check_mark: Ajustes nas configurações de cache.
* :white_check_mark: Ajustes nas configurações de pre-commit hooks.
* :white_check_mark: Ajustes nas configurações de gerenciamento de versões.
* :white_check_mark: Ajustes nas configurações de linting.
* :white_check_mark: Ajustes nas configurações de formatação de código.
* :white_check_mark: Ajustes nas configurações de segurança do projeto.
* :white_check_mark: Atualização de arquivos de configuração de integração contínua.
* :white_check_mark: Remoção de configurações obsoletas.
* :white_check_mark: Adição de novos arquivos de configuração.
* :white_check_mark: Ajustes nas configurações de tradução.
* :white_check_mark: Ajustes nas configurações de documentação.

:pushpin: **Exemplo de commit**:

> :gear: config(env): adiciona nova variável de ambiente para API.
> :gear: config(env): ajusta configuração de ambiente.
> :gear: config(pacotes): atualiza configurações do gerenciador de pacotes.
> :gear: config(cache): ajusta configuração de cache.
> :gear: config(pre-commit): ajusta configuração de pre-commit hooks.
> :gear: config(versões): ajusta configuração de gerenciamento de versões.
> :gear: config(linting): ajusta configuração de linting.
> :gear: config(formatação): ajusta configuração de formatação de código.
> :gear: config(seguranca): ajusta configuração de segurança.
> :gear: config(traducao): ajusta configuração de tradução.
> :gear: config(documentacao): ajusta configuração de documentação.

---

### :calendar: Revert

Reversão de commits anteriores.

#### Exemplos de tarefas Revert

* :white_check_mark: Reverter mudanças problemáticas.
* :white_check_mark: Reverter mudanças de configuração.
* :white_check_mark: Reverter mudanças de build.
* :white_check_mark: Reverter mudanças de linting.
* :white_check_mark: Reverter mudanças de formatação.
* :white_check_mark: Reverter mudanças de tradução.
* :white_check_mark: Reverter mudanças de documentos.
* :white_check_mark: Reverter mudanças de segurança.
* :white_check_mark: Reverter mudanças de cache.
* :white_check_mark: Reverter mudanças de pre-commit hooks.
* :white_check_mark: Reverter mudanças de versões.
* :white_check_mark: Desfazer commits incorretos.

:pushpin: **Exemplo de commit**:

> :calendar: revert(user-service): reverte alteração que causava erro.
> :calendar: revert(env): reverte alteração que causava erro.
> :calendar: revert(cache): reverte alteração que causava erro.
> :calendar: revert(pre-commit): reverte alteração que causava erro.
> :calendar: revert(build): reverte alteração que causava erro.
> :calendar: revert(lint): reverte alteração que causava erro.
> :calendar: revert(format): reverte alteração que causava erro.
> :calendar: revert(tran): reverte alteração que causava erro.
> :calendar: revert(docs): reverte alteração que causava erro.
> :calendar: revert(sec): reverte alteração que causava erro.

---

## :dart: Exemplos de Commits

Formato recomendado:

```markdown
emoji categoria(escopo): descrição breve.
```

### :white_check_mark: Exemplos

* :sparkles: feat(api): adiciona suporte à API de pagamento.
* :lady_beetle: fix(ui): corrige bug no botão de login.
* :book: docs(README): adiciona seção sobre instalação.
* :racing_car: perf(db): otimiza query de busca de usuários.
* :lock: security(auth): adiciona verificação de senha forte.
* :package: build(webpack): remove pacote desnecessário.

---

## :rocket: Benefícios do Padrão

* :white_check_mark: **Facilidade de leitura** - Identificação rápida do tipo de mudança.
* :white_check_mark: **Histórico organizado** - Mensagens de commit padronizadas ajudam na auditoria.
* :white_check_mark: **Melhora na colaboração** - Equipes entendem rapidamente as alterações.

:pushpin: Mantenha as mensagens concisas e use outros emojis com moderação!

---

## Tabela para consultar outros emojis

| CÓDIGO                        |            EMOJI            | DESCRIÇÃO                                   |
| :---------------------------- | :-------------------------: | :------------------------------------------ |
| `:hammer_and_wrench:`         |     :hammer_and_wrench:     | Tarefa.                                     |
| `:sparkles:`                  |         :sparkles:          | funcionalidade.                             |
| `:lady_beetle:`               |        :lady_beetle:        | Correção.                                   |
| `:ambulance:`                 |         :ambulance:         | Correção rápida.                            |
| `:art:`                       |            :art:            | Estilo.                                     |
| `:arrows_counterclockwise:`   |  :arrows_counterclockwise:  | Refatoração.                                |
| `:wastebasket:`               |        :wastebasket:        | Limpeza.                                    |
| `:racing_car:`                |        :racing_car:         | Desempenho.                                 |
| `:test_tube:`                 |         :test_tube:         | Teste.                                      |
| `:book:`                      |           :book:            | Documentação.                               |
| `:lock:`                      |           :lock:            | Segurança.                                  |
| `:package:`                   |          :package:          | Construção.                                 |
| `:gear:`                      |           :gear:            | Configuração.                               |
| `:calendar:`                  |         :calendar:          | Reverter.                                   |
| `:label:`                     |           :label:           | Adicionar, atualizar ou remover tags.       |
| `:twisted_rightwards_arrows:` | :twisted_rightwards_arrows: | Mesclar ramificações.                       |
| `:alembic:`                   |          :alembic:          | Realizar experimentos.                      |
| `:construction:`              |       :construction:        | Trabalho em andamento.                      |
| `:jigsaw:`                    |          :jigsaw:           | Adicionar, atualizar ou remover componente. |
| `:pushpin:`                   |          :pushpin:          | Fixar dependência em versão especifica.     |
| `:clipboard:`                 |         :clipboard:         | Documentação em andamento.                  |
| `:pencil:`                    |          :pencil:           | Atualizar conteúdo da documentação.         |
| `:pencil2:`                   |          :pencil2:          | Corrigir erros de digitação.                |
| `:dart:`                      |           :dart:            | Metas concluídas.                           |
| `:tada:`                      |           :tada:            | Commit inicial.                             |

<!--  -->
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

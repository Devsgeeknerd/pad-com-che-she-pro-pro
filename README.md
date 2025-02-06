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
* :white_check_mark: Ajuste no arquivo `.gitignore`.
* :white_check_mark: Ajustes de ambiente de desenvolvimento.
* :white_check_mark: Ajustes nas configurações de deploy.
* :white_check_mark: Atualização de bibliotecas de análise estática de código.
* :white_check_mark: Atualização de dependências.
* :white_check_mark: Atualização de documentação interna.
* :white_check_mark: Atualização de versões.
* :white_check_mark: Atualização de versões de bibliotecas de testes.
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
* :white_check_mark: Revisão de testes.

:pushpin: **Exemplo de commit**:

> :hammer_and_wrench: chore(analysis): atualiza ferramentas de análise estática de código.

> :hammer_and_wrench: chore(build): melhora processo de build com novos scripts.

> :hammer_and_wrench: chore(cache): ajusta configurações de cache para melhorar o desempenho.

> :hammer_and_wrench: chore(cleanup): remove dependências não utilizadas do projeto.

> :hammer_and_wrench: chore(deploy): ajusta configurações de deploy para integração contínua.

> :hammer_and_wrench: chore(deps): atualiza dependências para a versão mais recente.

> :hammer_and_wrench: chore(dart): atualiza a versão do Dart para a versão estável mais recente.

> :hammer_and_wrench: chore(docs): atualiza documentação interna com novas práticas e procedimentos.

> :hammer_and_wrench: chore(env): revisa arquivos de configuração de ambiente para otimização.

> :hammer_and_wrench: chore(env-vars): adiciona novas variáveis de ambiente necessárias para o projeto.

> :hammer_and_wrench: chore(gitignore): ajusta o arquivo `.gitignore` para excluir novos arquivos temporários.

> :hammer_and_wrench: chore(hooks): adiciona e configura pre-commit hooks no projeto.

> :hammer_and_wrench: chore(logs): limpa logs antigos que não são mais necessários.

> :hammer_and_wrench: chore(security): atualiza configurações de segurança para reforçar TLS/SSL.

> :hammer_and_wrench: chore(structure): refatora estrutura de pastas para melhor organização.

> :hammer_and_wrench: chore(tests): atualiza bibliotecas de testes para versões mais recentes.

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

:pushpin: **Exemplo de commit**:

> :sparkles: feat(auth): adicionar sistema de autenticação JWT.

> :sparkles: feat(notifications): adicionar notificações push para novos conteúdos.

> :sparkles: feat(theme): permitir que usuários escolham temas personalizados no app.

> :sparkles: feat(sharing): integrar com Facebook e Twitter para compartilhamento.

> :sparkles: feat(performance): otimizar carregamento de imagens para melhor desempenho.

> :sparkles: feat(content): adicionar suporte para vídeos na seção de conteúdo interativo.

> :sparkles: feat(language): adicionar suporte ao idioma espanhol.

> :sparkles: feat(search): adicionar funcionalidade de busca por voz.

> :sparkles: feat(editing): adicionar filtro de imagem para edição de fotos.

---

### :lady_beetle: Fix

Correção de **bugs** que impactam o funcionamento esperado do sistema.

#### Exemplos de tarefas Fix

* :white_check_mark: Correção de erros de lógica.
* :white_check_mark: Ajustes em validações.
* :white_check_mark: Correção de falhas na interface.
* :white_check_mark: Ajustes em mensagens de erro.
* :white_check_mark: Correção de bugs na interface.
* :white_check_mark: Correção de bugs de segurança.
* :white_check_mark: Correção de bugs de performance.
* :white_check_mark: Correção de bugs em validações.

:pushpin: **Exemplo de commit**:
> :lady_beetle: fix(api): corrige validação de email.
> :lady_beetle: fix(auth): corrige erro de autenticação.
> :lady_beetle: fix(cache): corrige erro de cache.
> :lady_beetle: fix(dart): corrige versão do Dart.
> :lady_beetle: fix(docs): corrige erro de documentação.
> :lady_beetle: fix(env): corrige erro de configuração de ambiente.
> :lady_beetle: fix(hooks): corrige erro de pre-commit hooks.
> :lady_beetle: fix(logs): corrige erro de logs.
> :lady_beetle: fix(security): corrige erro de segurança.
> :lady_beetle: fix(structure): corrige erro de estrutura de pastas.
> :lady_beetle: fix(tests): corrige erro de testes.

---

### :ambulance: Hotfix

Correções **críticas e emergenciais** que precisam ser aplicadas imediatamente.

#### Exemplos de tarefas Hotfix

* :white_check_mark: Resolver erro crítico em produção.  
* :white_check_mark: Ajustes rápidos de segurança.
* :white_check_mark: Correção de bugs de segurança.
* :white_check_mark: Correção de bugs de performance.
* :white_check_mark: Correção de bugs em validações.
* :white_check_mark: Correção de bugs em testes.
* :white_check_mark: Correção de bugs em interfaces.
* :white_check_mark: Correção de bugs em arquivos de configuração.
* :white_check_mark: Correção de bugs em arquivos de log.
* :white_check_mark: Correção de bugs em arquivos de testes.
* :white_check_mark: Correção de bugs em arquivos de estilo.
* :white_check_mark: Correção de bugs em arquivos de tradução.
* :white_check_mark: Correção de bugs em arquivos de documentos.

:pushpin: **Exemplo de commit**:
> :ambulance: hotfix(login): corrige erro impedindo login de usuários.
> :ambulance: hotfix(api): corrige erro impedindo a execução de tarefas.
> :ambulance: hotfix(cache): corrige erro impedindo armazenamento de dados.
> :ambulance: hotfix(dart): corrige erro impedindo compilação do aplicativo.
> :ambulance: hotfix(docs): corrige erro impedindo documentação.
> :ambulance: hotfix(env): corrige erro impedindo configuração de ambiente.
> :ambulance: hotfix(hooks): corrige erro impedindo pre-commit hooks.
> :ambulance: hotfix(logs): corrige erro impedindo logs.
> :ambulance: hotfix(security): corrige erro impedindo segurança.
> :ambulance: hotfix(structure): corrige erro impedindo organização de pastas.
> :ambulance: hotfix(tests): corrige erro impedindo testes.
> :ambulance: hotfix(translations): corrige erro impedindo tradução.
> :ambulance: hotfix(ui): corrige erro impedindo interface.
> :ambulance: hotfix(utils): corrige erro impedindo utilidades.
> :ambulance: hotfix(videos): corrige erro impedindo reprodução de vídeos.
> :ambulance: hotfix(web): corrige erro impedindo acesso a Internet.
> :ambulance: hotfix(website): corrige erro impedindo acesso ao site.
> :ambulance: hotfix(workflow): corrige erro impedindo fluxo de trabalho.
> :ambulance: hotfix(zoom): corrige erro impedindo acesso ao Zoom.

---

### :art: Style

Mudanças **cosméticas** no código que não afetam a funcionalidade.

#### Exemplos de tarefas Style

* :white_check_mark: Ajustes de indentação e espaçamentos.
* :white_check_mark: Correção de formatação de código.
* :white_check_mark: Alterações em estilos.
* :white_check_mark: Ajustes de cores.
* :white_check_mark: Ajustes de tamanhos de fonte.
* :white_check_mark: Ajustes de layouts.
* :white_check_mark: Ajustes de tamanhos de tela.
* :white_check_mark: Ajustes de arquitetura.
* :white_check_mark: Ajustes de arquivos de configuração.
* :white_check_mark: Ajustes de arquivos de log.
* :white_check_mark: Ajustes de arquivos de testes.
* :white_check_mark: Ajustes de arquivos de estilo.
* :white_check_mark: Ajustes de arquivos de tradução.
* :white_check_mark: Ajustes de arquivos de documentos.

:pushpin: **Exemplo de commit**:
> :art: style(ui): ajusta espaçamento entre botões.
> :art: style(env): ajusta configurações de ambiente.
> :art: style(hooks): ajusta pre-commit hooks.
> :art: style(logs): ajusta logs.
> :art: style(security): ajusta configurações de segurança.
> :art: style(structure): ajusta estrutura de pastas.
> :art: style(tests): ajusta testes.
> :art: style(translations): ajusta tradução.
> :art: style(ui): ajusta interface.
> :art: style(utils): ajusta utilidades.
> :art: style(videos): ajusta reprodução de vídeos.
> :art: style(web): ajusta acesso a Internet.
> :art: style(website): ajusta acesso ao site.
> :art: style(workflow): ajusta fluxo de trabalho.
> :art: style(zoom): ajusta acesso ao Zoom.

---

### :arrows_counterclockwise: Refactor

Melhorias na **estrutura do código** sem alterar seu comportamento.

#### Exemplos de tarefas Refactor

* :white_check_mark: Melhor organização do código.
* :white_check_mark: Melhoria na modularização do código.
* :white_check_mark: Redução de complexidade de código.
* :white_check_mark: Redução de duplicação de código.
* :white_check_mark: Simplificação de funções complexas.
* :white_check_mark: Simplificação de funções complexas.
* :white_check_mark: Redução da repetição de código.

:pushpin: **Exemplo de commit**:
> :arrows_counterclockwise: refactor(user-service): melhora a modularização do código.

---

### :wastebasket: Cleanup

Limpeza de código desnecessário ou **removido**.

#### Exemplos de tarefas Cleanup

* :white_check_mark: Remoção de código obsoleto.
* :white_check_mark: Exclusão de arquivos não utilizados.
* :white_check_mark: Redução de complexidade de código.

:pushpin: **Exemplo de commit**:
> :wastebasket: cleanup(legacy): remove métodos não utilizados.
> :wastebasket: cleanup(legacy): remove funções obsoletas.
> :wastebasket: cleanup(legacy): remove arquivos não utilizados.
> :wastebasket: cleanup(legacy): remove pastas não utilizadas.
> :wastebasket: cleanup(legacy): remove dependências não utilizadas.
> :wastebasket: cleanup(legacy): remove arquivos temporários.

---

### :racing_car: Perf

Otimizações de **desempenho** para melhorar a eficiência do código.

### Exemplos de tarefas Perf

* :white_check_mark: Redução do tempo de execução de um algoritmo.
* :white_check_mark: Melhor uso de recursos do sistema.
* :white_check_mark: Redução de consumo de energia.

:pushpin: **Exemplo de commit**:
> :racing_car: perf(algoritmo): otimiza busca para reduzir tempo de execução.
> :racing_car: perf(sistema): melhora o uso de recursos.
> :racing_car: perf(energia): reduz o consumo de energia.
> :racing_car: perf(algoritmo): otimiza algoritmo para melhorar desempenho.
> :racing_car: perf(sistema): melhora o desempenho do sistema.

---

### :test_tube: Test

Adição, atualização e remoção de **testes automatizados**.

#### Exemplos de tarefas Test

* :white_check_mark: Criação de novos testes.
* :white_check_mark: Remoção de testes obsoletos.
* :white_check_mark: Correção de testes falhos.
* :white_check_mark: Melhoria na cobertura de testes.
* :white_check_mark: Melhoria na qualidade de testes.
* :white_check_mark: Melhoria na velocidade de testes.
* :white_check_mark: Melhoria na execução de testes.

:pushpin: **Exemplo de commit**:
> :test_tube: test(user-service): adiciona testes unitários para autenticação.
> :test_tube: test(user-service): adiciona testes unitários para autorização.
> :test_tube: test(user-service): adiciona testes unitários para cadastro de usuários.
> :test_tube: test(user-service): adiciona testes unitários para login de usuários.
> :test_tube: test(user-service): adiciona testes unitários para atualização de usuários.
> :test_tube: test(user-service): adiciona testes unitários para exclusão de usuários.

---

### :book: Docs

Alterações na **documentação** do projeto.

#### Exemplos de tarefas Docs

* :white_check_mark: Atualização do README.
* :white_check_mark: Atualização de documentação.
* :white_check_mark: Comentários no código.
* :white_check_mark: Documentação de APIs.

:pushpin: **Exemplo de commit**:
> :book: docs(README): atualiza guia de instalação.
> :book: docs(documentation): atualiza documentação.
> :book: docs(code-comments): adiciona comentários no código.
> :book: docs(api-documentation): documenta APIs.
> :book: docs(translation): adiciona documentação de tradução.

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

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

:pushpin: **Exemplo de commit**:
> :hammer_and_wrench: chore(deps): atualiza dependências para a versão mais recente.

---

### :sparkles: Feat

Adição de novas funcionalidades ou melhorias que agregam valor ao usuário.

#### Exemplos de tarefas Feat

:white_check_mark: Implementação de novas funcionalidades.
:white_check_mark: Melhorias na UI/UX.
:white_check_mark: Suporte a novos dispositivos ou plataformas.
:white_check_mark: Integração com APIs externas.

:pushpin: **Exemplo de commit**:
> :sparkles: feat(auth): adicionar sistema de autenticação JWT.

---

### :lady_beetle: Fix

Correção de **bugs** que impactam o funcionamento esperado do sistema.

#### Exemplos de tarefas Fix

:white_check_mark: Correção de erros de lógica.
:white_check_mark: Ajustes em validações.
:white_check_mark: Correção de falhas na interface.

:pushpin: **Exemplo de commit**:
> :lady_beetle: fix(api): corrige validação de email.

---

### :ambulance: Hotfix

Correções **críticas e emergenciais** que precisam ser aplicadas imediatamente.

#### Exemplos de tarefas Hotfix

:white_check_mark: Resolver erro crítico em produção.  
:white_check_mark: Ajustes rápidos de segurança.  

:pushpin: **Exemplo de commit**:
> :ambulance: hotfix(login): corrige erro impedindo login de usuários

---

### :art: Style

Mudanças **cosméticas** no código que não afetam a funcionalidade.

#### Exemplos de tarefas Style

:white_check_mark: Ajustes de indentação e espaçamentos.
:white_check_mark: Correção de formatação de código.
:white_check_mark: Alterações em estilos.

:pushpin: **Exemplo de commit**:
> :art: style(ui): ajusta espaçamento entre botões.

---

### :arrows_counterclockwise: Refactor

Melhorias na **estrutura do código** sem alterar seu comportamento.

#### Exemplos de tarefas Refactor

:white_check_mark: Melhor organização do código.
:white_check_mark: Simplificação de funções complexas.
:white_check_mark: Redução da repetição de código.

:pushpin: **Exemplo de commit**:
> :arrows_counterclockwise: refactor(user-service): melhora a modularização do código.

---

### :wastebasket: Cleanup

Limpeza de código desnecessário ou **removido**.

#### Exemplos de tarefas Cleanup

:white_check_mark: Remoção de código obsoleto.
:white_check_mark: Exclusão de arquivos não utilizados.

:pushpin: **Exemplo de commit**:
> :wastebasket: cleanup(legacy): remove métodos não utilizados.

---

### :racing_car: Perf

Otimizações de **desempenho** para melhorar a eficiência do código.

### Exemplos de tarefas Perf

:white_check_mark: Redução do tempo de execução de um algoritmo.
:white_check_mark: Melhor uso de recursos do sistema.

:pushpin: **Exemplo de commit**:
> :racing_car: perf(algoritmo): otimiza busca para reduzir tem de execução.

---

### :test_tube: Test

Adição, atualização e remoção de **testes automatizados**.

#### Exemplos de tarefas Test

:white_check_mark: Criação de novos testes.
:white_check_mark: Correção de testes falhos.
:white_check_mark: Melhoria na cobertura de testes.

:pushpin: **Exemplo de commit**:
> :test_tube: test(user-service): adiciona testes unitários para autenticação.

---

### :book: Docs

Alterações na **documentação** do projeto.

#### Exemplos de tarefas Docs

:white_check_mark: Atualização do README.
:white_check_mark: Comentários no código.
:white_check_mark: Documentação de APIs.

:pushpin: **Exemplo de commit**:
> :book: docs(README): atualiza guia de instalação.

---

### :lock: Security

Correções e melhorias à **segurança** do projeto.

#### Exemplos de tarefas Security

:white_check_mark: Correção de vulnerabilidade.
:white_check_mark: Melhorias na autenticação e autorização.

:pushpin: **Exemplo de commit**:
> :lock: security(auth): corrige vulnerabilidade no token JWT.

---

### :package: Build

Mudança no sistema de **build** do projeto.

#### Exemplos de tarefas Build

:white_check_mark: Ajuste em scripts de compilação.
:white_check_mark: Modificações em dependências.

:pushpin: **Exemplo de commit**:
> :package: build(webpack): ajusta configuração para otimizar bundle.

---

### :gear: Config

Alterações em **configurações** do projeto.

#### Exemplos de tarefas Config

:white_check_mark: Modificações em arquivos de configuração.
:white_check_mark: Ajustes de variáveis de ambiente.

:pushpin: **Exemplo de commit**:
> :gear: config(env): adiciona nova variável de ambiente para API.

---

### :calendar: Revert

Reversão de commits anteriores.

#### Exemplos de tarefas Revert

:white_check_mark: Reverter mudanças problemáticas.
:white_check_mark: Desfazer commits incorretos.

:pushpin: **Exemplo de commit**:
> :calendar: revert(user-service): reverte alteração que causava erro.

---
---

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

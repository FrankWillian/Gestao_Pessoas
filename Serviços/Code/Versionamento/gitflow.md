# Versionamento Semântico

O versionamento semântico, quando realizado de forma correta, ajuda os usuários a entenderem o estágio em que a aplicação está. Em desenvolvimento de software, nós versionamos aplicações seguindo o Versionamento Semântico (Semantic Versioning), o que nada mais é que um modelo geral em que todos usuários possam entender.

O versionamento semântico propõe um conjunto simples de regras de como os números das versões são atribuídos e incrementados.

Considere o formato de versão X.Y.Z (Major.Minor.Patch, ou seja, Maior, Menor, e Correção, respectivamente). X, Y, e Z são inteiros e não negativos. Cada elemento deve ser incrementado em 1. Por exemplo: 1.9.0 -> 1.10.0 -> 1.11.0.

Para cada lançamento do software, ele deve ter um número único da versão e, uma vez lançado, o código dessa versão não pode mais ser alterado. Qualquer necessidade de alteração no software, ele deverá ser lançado com um novo número de versão.

## Passo a passo do versionamento

1. Versões 0.Y.Z – desenvolvimento antes de lançar aplicação para produção
    1.1 Versão 0.Y.0 – novas funcionalidades
        Um time inicia o desenvolvimento de uma nova aplicação. Nessa fase inicial e embrionária, a versão da aplicação se inicia em 0.1.0. Após cada funcionalidade nova ser desenvolvida, o valor referente à Minor version é incrementado: 0.1.0 -> 0.2.0 -> 0.3.0 e assim sucessivamente.
    1.2 Versão 0.Y.Z – correção de bugs
        Caso exista algum bug em uma dessas versões (por exemplo: bug encontrado na versão 0.3.0), a correção desse bug deverá ser lançada juntamente com a versão 0.3.1. Seguinte a essa versão, se houver um novo bug, será gerada a versão 0.3.2.
    1.3 Versão 0.Y.0 – novas funcionalidades
        Com o software na versão 0.3.2, se o time lança uma nova funcionalidade, sua versão passa a ser 0.4.0.
2. Versões X.Y.Z – após lançar aplicação para produção
    2.1 Versão 1.0.0
        Sem quebra de compatibilidade
        Após uma versão ser disponibilizada como estável ou o software ser lançado em produção, a versão é alterada para 1.0.0.
    2.2 Versão x.Y.0 – novas funcionalidades
        Sem quebra de compatibilidade
        Para novas funcionalidades, caso não haja quebra de compatibilidade, o valor referente à Minor version é incrementado: 1.0.0 -> 1.1.0 -> 1.2.0 e assim sucessivamente.
    2.3 Versão 1.Y.Z – correção de bugs
        Caso exista algum bug em uma dessas versões (por exemplo: bug encontrado na versão 1.3.0), a correção desse bug deverá ser lançada juntamente com a versão 1.3.1. Seguindo a essa versão, se houver um novo bug, será gerada a versão 1.3.2.

## GitFlow

O Git Flow é um modelo, uma estratégia ou, ainda, um fluxo de trabalho muito utilizado por equipes de desenvolvimento de software. Ele se destaca por auxiliar na organização do versionamento de códigos.

Publicado em 2010, pelo engenheiro de software holandês, Vincent Driessen, o objetivo do Git Flow era melhorar as organizações das Branches (ramificações) dentro de repositórios e, desta forma, dar mais fluidez ao processo de desenvolvimento de novas funcionalidades, correções de bugs e lançamentos de versões.

🚀 Como funciona

O Git Flow trabalha com duas branches principais, a Develop e a Master, que duram para sempre; e três branches de suporte, Feature, Release e Hotfix, que são temporários e duram até realizar o merge com as branches principais.

Então, ao invés de uma única branch Master, esse fluxo de trabalho utiliza duas branches principais para registrar o histórico do projeto. A branch Master armazena o histórico do lançamento oficial, e a branch Develop serve como uma ramificação de integração para recursos.

### Estrutura de branches

- `master`
  - Descrição: Branch principal e mais importante, contém o código de produção.
  - Tipo: Principal
  - Tempo de vida: Infinito
  - Criada de: N/A
  - Pode ir para: develop

- `develop`
  - Descrição: Contém os códigos do próximo release. Quando a branch develop estiver pronta para entrar em produção, um merge pode ser feito para a branch master.
  - Tipo: Principal
  - Tempo de vida: Infinito
  - Criada de: master (uma única vez)
  - Pode ir para: master

- `hotfix`
  - Descrição: Os hotfixes surgem da necessidade de agir imediatamente sobre uma situação indesejada na versão de produção ativa. Pode ser criado a partir da branch master que indica a versão em produção.
  - Tipo: Suporte
  - Tempo de vida: Finito
  - Criada de: master
  - Pode ir para: master & develop

- `release`
  - Descrição: Auxilia a preparação de uma nova versão de produção e permite correções de bugs menores e a preparação de metadados de uma versão.
  - Tipo: Suporte
  - Tempo de vida: Finito
  - Criada de: develop
  - Pode ir para: develop & master

- `tag`
  - Descrição: Fixa um ponto (commit) na master que representa uma versão efetiva para produção.
  - Tipo: Principal
  - Tempo de vida: Finito
  - Criada de: develop
  - Pode ir para: develop & master

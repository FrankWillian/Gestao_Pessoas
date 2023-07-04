# Critérios de aceitação

## Sumário
- [Requisito: Monitoramento total das prescrições, separações e abastecimentos realizados nos equipamentos.](#requisito-monitoramento-total-das-prescrições-separações-e-abastecimentos-realizados-nos-equipamentos)
- [Requisito: Acesso 24 horas aos dados.](#requisito-acesso-24-horas-aos-dados)
- [Requisito: Acesso via mobile.](#requisito-acesso-via-mobile)
- [Requisito: Cadastro de usuários.](#requisito-cadastro-de-usuários)
- [Requisito: API de integração.](#requisito-api-de-integração)
- [Requisito: Acesso a relatórios.](#requisito-acesso-a-relatórios)
- [Requisito: Sincronização de dados em duas vias.](#requisito-sincronização-de-dados-em-duas-vias)
- [Requisito: Agendamento de abastecimento por equipamento.](#requisito-agendamento-de-abastecimento-por-equipamento)
- [Requisito: Controle de acesso centralizado por perfil de usuário.](#requisito-controle-de-acesso-centralizado-por-perfil-de-usuário)
- [Requisito: Possibilidade de propagação imediata de atualizações de dados.](#requisito-possibilidade-de-propagação-imediata-de-atualizações-de-dados)
- [Requisito: Envio de ordem de separação.](#requisito-envio-de-ordem-de-separação)
- [Requisito: Envio de ordem de reabastecimento.](#requisito-envio-de-ordem-de-reabastecimento)
- [Requisito: Bloqueio de usuário.](#requisito-bloqueio-de-usuário)
- [Requisito: Dashboard para acompanhamento geral dos equipamentos.](#requisito-dashboard-para-acompanhamento-geral-dos-equipamentos)
- [Requisito: Identificação de equipamentos com produtos abaixo do estoque mínimo.](#requisito-identificação-de-equipamentos-com-produtos-abaixo-do-estoque-mínimo)
- [Requisito: Identificação de equipamentos offline.](#requisito-identificação-de-equipamentos-offline)
- [Requisito: Transações seguras via HTTPS.](#requisito-transações-seguras-via-https)
- [Requisito: Backup de base de dados com retenção de 30 dias.](#requisito-backup-de-base-de-dados-com-retenção-de-30-dias)
- [Requisito: Compatibilidade com padrões web e conformidade com a plataforma Windows.](#requisito-compatibilidade-com-padrões-web-e-conformidade-com-a-plataforma-windows)
- [Requisito: Experiência do usuário aprimorada.](#requisito-experiência-do-usuário-aprimorada)

## Requisito: Monitoramento total das prescrições, separações e abastecimentos realizados nos equipamentos 📋
- **Critério de Aceitação 1:** O sistema deve registrar todas as prescrições realizadas nos equipamentos.
- **Critério de Aceitação 2:** O sistema deve registrar todas as separações de medicamentos realizadas nos equipamentos.
- **Critério de Aceitação 3:** O sistema deve registrar todos os abastecimentos realizados nos equipamentos.

## Requisito: Acesso 24 horas aos dados 🌐🕒
- **Critério de Aceitação 1:** Os usuários devem poder acessar os dados do sistema a qualquer momento, sem restrições de horário.

## Requisito: Acesso via mobile 📱
- **Critério de Aceitação 1:** O sistema deve ser acessível através de dispositivos móveis, como smartphones e tablets.
- **Critério de Aceitação 2:** A interface do sistema deve ser responsiva e adaptar-se adequadamente ao tamanho da tela do dispositivo móvel.

## Requisito: Cadastro de usuários 👥
- **Critério de Aceitação 1:** O sistema deve permitir o cadastro de usuários com todos os dados necessários.
- **Critério de Aceitação 2:** Os usuários devem poder editar, excluir e alterar as permissões dos usuários cadastrados.
- **Critério de Aceitação 3:** O sistema deve suportar diferentes níveis de usuário, incluindo Administrador (ADM), Farmacêutico e Operador.

## Requisito: API de integração 🔄🔌
- **Critério de Aceitação 1:** A API deve permitir o envio em tempo real de todos os dados de prescrição dos equipamentos.
- **Critério de Aceitação 2:** A API deve fornecer informações sobre o status da rede de comunicação.

## Requisito: Acesso a relatórios 📊
- **Critério de Aceitação 1:** O sistema deve fornecer relatórios contendo dados de usuários, produtividade, tempo de máquina disponível e inventário de produtos.
- **Critério de Aceitação 2:** Os relatórios devem ser gerados de forma precisa e apresentar informações relevantes de forma clara e organizada.

## Requisito: Sincronização de dados em duas vias 🔄🔃
- **Critério de Aceitação 1:** As informações cadastradas na central devem ser sincronizadas com cada equipamento.
- **Critério de Aceitação 2:** A sincronização deve permitir o cadastro de medicamentos, pacientes e outros dados em ambos os lados.

## Requisito: Agendamento de abastecimento por equipamento 🗓️
- **Critério de Aceitação 1:** O sistema deve permitir o agendamento de abastecimentos para cada equipamento, considerando suas necessidades individuais.

## Requisito: Controle de acesso centralizado por perfil de usuário 🔑👤
- **Critério de Aceitação 1:** O sistema deve oferecer um controle de acesso centralizado, onde as permissões de cada usuário são gerenciadas em um único local.

## Requisito: Possibilidade de propagação imediata de atualizações de dados 🔄🔃
- **Critério de Aceitação 1:** As atualizações de dados realizadas no sistema devem ser propagadas imediatamente para todos os equipamentos conectados.

## Requisito: Envio de ordem de separação 📤
- **Critério de Aceitação 1:** O sistema deve permitir o envio de ordens de separação para os equipamentos correspondentes.

## Requisito: Envio de ordem de reabastecimento 📤
- **Critério de Aceitação 1:** O sistema deve permitir o envio de ordens de reabastecimento para os equipamentos correspondentes.

## Requisito: Bloqueio de usuário 🔒👤
- **Critério de Aceitação 1:** Em caso de emergência, o sistema deve ser capaz de bloquear o acesso de um usuário a todos os equipamentos.

## Requisito: Dashboard para acompanhamento geral dos equipamentos 🖥️📊
- **Critério de Aceitação 1:** O sistema deve fornecer um painel de controle que permita o acompanhamento geral dos equipamentos, exibindo informações relevantes de forma resumida e visualmente atrativa.

## Requisito: Identificação de equipamentos com produtos abaixo do estoque mínimo 📉
- **Critério de Aceitação 1:** O sistema deve ser capaz de identificar e destacar os equipamentos que possuem produtos com quantidade abaixo do estoque mínimo definido.

## Requisito: Identificação de equipamentos offline ⚠️🔌
- **Critério de Aceitação 1:** O sistema deve ser capaz de identificar e sinalizar os equipamentos que estão offline, indicando uma possível falha na comunicação.

## Requisito: Transações seguras via HTTPS 🔒🌐
- **Critério de Aceitação 1:** Todas as transações realizadas no sistema devem ser seguras, utilizando o protocolo HTTPS para garantir a criptografia dos dados transmitidos.

## Requisito: Backup de base de dados com retenção de 30 dias 💾📅
- **Critério de Aceitação 1:** O sistema deve realizar backups automáticos da base de dados e manter esses backups por um período de 30 dias.

## Requisito: Compatibilidade com padrões web e conformidade com a plataforma Windows 🌐🖥️
- **Critério de Aceitação 1:** O sistema deve ser compatível com os padrões web, garantindo sua funcionalidade e usabilidade em diferentes navegadores.
- **Critério de Aceitação 2:** O sistema deve ser desenvolvido levando em consideração os requisitos e diretrizes da plataforma Windows.

## Requisito: Experiência do usuário aprimorada 😊👤
- **Critério de Aceitação 1:** As telas de prescrição, reabastecimento e movimentações devem oferecer uma experiência do usuário intuitiva e agradável.
- **Critério de Aceitação 2:** Todas as telas devem permitir a aplicação de filtros de busca por ID ou paciente, facilitando a localização e acesso aos dados específicos desejados.

Esses critérios de aceitação ajudam a definir os parâmetros que determinarão se os requisitos foram atendidos com sucesso durante o desenvolvimento do projeto. Eles servem como base para a validação e aceitação das funcionalidades implementadas, garantindo que o sistema atenda às necessidades e expectativas dos usuários.
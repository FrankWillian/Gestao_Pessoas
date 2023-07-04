### Requisitos do Projeto - Sistema de Gerenciamento de Estoque e Prescrições

📋 **Sumário**

- [Monitoramento](#monitoramento)
- [Acesso aos Dados](#acesso-aos-dados)
- [Acesso via Mobile](#acesso-via-mobile)
- [Cadastro de Usuários](#cadastro-de-usuários)
- [API de Integração](#api-de-integração)
- [Relatórios](#relatórios)
- [Sincronização de Dados em Duas Vias](#sincronização-de-dados-em-duas-vias)
- [Feed de Abastecimento](#feed-de-abastecimento)
- [Controle de Acesso Centralizado](#controle-de-acesso-centralizado)
- [Atualizações Imediatas de Dados](#atualizações-imediatas-de-dados)
- [Visualização de Ordem de Separação](#visualização-de-ordem-de-separação)
- [Envio de Ordem de Reabastecimento](#envio-de-ordem-de-reabastecimento)
- [Bloqueio de Usuário](#bloqueio-de-usuário)
- [Dashboard](#dashboard)
- [Identificação de Produtos com Estoque Mínimo](#identificação-de-produtos-com-estoque-mínimo)
- [Identificação de Equipamentos Offline](#identificação-de-equipamentos-offline)
- [Transações Seguras](#transações-seguras)
- [Backup de Base de Dados](#backup-de-base-de-dados)
- [Compatibilidade e Conformidade](#compatibilidade-e-conformidade)
- [Experiência do Usuário Aprimorada](#experiência-do-usuário-aprimorada)

🔍 **Monitoramento** <a name="monitoramento"></a>

- O sistema deve permitir o monitoramento completo das prescrições, separações e abastecimentos realizados nos equipamentos.
  
🔑 **Acesso aos Dados** <a name="acesso-aos-dados"></a>

- O sistema deve garantir o acesso contínuo aos dados, disponíveis 24 horas por dia, em um ambiente de nuvem.
  
📱 **Acesso via Mobile** <a name="acesso-via-mobile"></a>

- O sistema deve suportar o acesso aos dados por meio de dispositivos móveis.
  
👤 **Cadastro de Usuários** <a name="cadastro-de-usuários"></a>

- O sistema deve oferecer funcionalidades para o cadastro de usuários.
- O cadastro de usuários deve incluir todas as informações relevantes, exceto o cadastro da digital nos equipamentos com leitor de digital.
- O sistema deve permitir a edição, exclusão e alteração de permissões dos usuários.
- Deve haver diferentes níveis de usuário, como Administrador (ADM), Farmacêutico e Operador.
  
🔌 **API de Integração** <a name="api-de-integração"></a>

- O sistema deve disponibilizar uma API de integração.
- A API deve permitir o envio em tempo real de todos os dados de prescrição dos equipamentos.
- A API deve fornecer informações sobre o status da rede de comunicação.
  
📊 **Relatórios** <a name="relatórios"></a>

- O sistema deve fornecer funcionalidades para o acesso a relatórios.
- Os relatórios devem abranger dados de usuários, produtividade e inventário de produtos.
  
🔄 **Sincronização de Dados em Duas Vias** <a name="sincronização-de-dados-em-duas-vias"></a>

- O sistema deve garantir a sincronização bidirecional de dados.
- O cadastro de usuários realizado na central deve ser sincronizado com cada equipamento.
- Deve ser possível sincronizar dados relacionados ao cadastro de medicamentos, pacientes e outros dados.
  
📦 **Feed de Abastecimento** <a name="feed-de-abastecimento"></a>

- O sistema deve disponibilizar um feed de abastecimento específico para cada equipamento.
  
🔒 **Controle de Acesso Centralizado** <a name="controle-de-acesso-centralizado"></a>

- O sistema deve oferecer um controle de acesso centralizado com base nos perfis de usuário e equipamento.
  
🔄 **Atualizações Imediatas de Dados** <a name="atualizações-imediatas-de-dados"></a>

- O sistema deve permitir a propagação imediata de atualizações de dados.
  
👀 **Visualização de Ordem de Separação** <a name="visualização-de-ordem-de-separação"></a>

- O sistema deve fornecer uma interface para visualizar as ordens de separação.
  
✉️ **Envio de Ordem de Reabastecimento** <a name="envio-de-ordem-de-reabastecimento"></a>

- O sistema deve permitir o envio de ordens de reabastecimento.
  
🔒 **Bloqueio de Usuário** <a name="bloqueio-de-usuário"></a>

- Em casos de emergência, o sistema deve ser capaz de bloquear o acesso do usuário a todos os equipamentos.
  
📊 **Dashboard** <a name="dashboard"></a>

- O sistema deve fornecer um dashboard abrangente para o acompanhamento dos equipamentos.
  
📉 **Identificação de Produtos com Estoque Mínimo** <a name="identificação-de-produtos-com-estoque-mínimo"></a>

- O sistema deve ser capaz de identificar os equipamentos que possuam produtos abaixo do estoque mínimo.
  
⚠️ **Identificação de Equipamentos Offline** <a name="identificação-de-equipamentos-offline"></a>

- O sistema deve ser capaz de identificar os equipamentos que estejam offline.
  
🔒 **Transações Seguras** <a name="transações-seguras"></a>

- Todas as transações realizadas pelo sistema devem ser seguras, utilizando HTTPS para garantir a segurança na comunicação.
  
💾 **Backup de Base de Dados** <a name="backup-de-base-de-dados"></a>

- O sistema deve realizar backups da base de dados, com uma retenção de 30 dias.
  
💻 **Compatibilidade e Conformidade** <a name="compatibilidade-e-conformidade"></a>

- O sistema deve ser compatível com os padrões web e estar em conformidade com a plataforma Windows.
  
🖥️ **Experiência do Usuário Aprimorada** <a name="experiência-do-usuário-aprimorada"></a>

- O sistema deve oferecer uma experiência do usuário aprimorada, incluindo telas de prescrição, reabastecimento e movimentação.
- Deve ser possível realizar filtros de busca por ID ou paciente em todas as telas.

Estes requisitos foram elaborados para fornecer uma visão abrangente das funcionalidades e recursos necessários para o sistema de gerenciamento de estoque e prescrições na área da saúde.

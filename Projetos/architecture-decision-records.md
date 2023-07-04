# Architecture Decision Records  🏛️

## Sumário
- [Contexto](#contexto)
- [ADR: 001 - Utilização do .NET para o Backend](#adr-001---utilização-do-net-para-o-backend)
- [ADR: 002 - Utilização do ExtJS para o Frontend](#adr-002---utilização-do-extjs-para-o-frontend)
- [ADR: 003 - Utilização do PostgreSQL como Banco de Dados](#adr-003---utilização-do-postgresql-como-banco-de-dados)
- [ADR: 004 - Utilização do RabbitMQ para Mensageria](#adr-004---utilização-do-rabbitmq-para-mensageria)
- [ADR: 005 - Utilização do Zabbix para Monitoramento](#adr-005---utilização-do-zabbix-para-monitoramento)
- [ADR: 006 - Utilização do Docker para Implantação](#adr-006---utilização-do-docker-para-implantação)

## Contexto  📚
O contexto do documento de ADR (Architecture Decision Records) é fornecer um registro claro e documentado das decisões arquitetônicas tomadas durante o desenvolvimento do projeto de software. Essas decisões são cruciais para orientar o processo de desenvolvimento, garantir a consistência e a compreensão das escolhas tecnológicas e justificar as decisões tomadas ao longo do projeto.

O documento de ADR serve como uma fonte de informação para a equipe de desenvolvimento e outras partes interessadas, como arquitetos, gerentes de projeto e stakeholders. Ele documenta as decisões tomadas, as justificativas por trás delas e o status atual de cada decisão, garantindo transparência e facilitando a comunicação entre os membros da equipe.

## ADR: 001 - Utilização do .NET para o Backend  💻
### Status: Aceito

#### Decisão
Utilizar a plataforma .NET, mais especificamente o framework ASP.NET com a linguagem de programação C#, para o desenvolvimento do backend do sistema.

#### Justificativa
A escolha do .NET se baseia em diversos fatores, como a ampla adoção dessa tecnologia no mercado, a disponibilidade de recursos e bibliotecas robustas, a maturidade do framework e a experiência da equipe de desenvolvimento. Além disso, o .NET oferece suporte para o desenvolvimento de APIs e integração com outros componentes do sistema, tornando-o uma escolha adequada para o desenvolvimento do backend.

## ADR: 002 - Utilização do ExtJS para o Frontend  🌐
### Status: Aceito

#### Decisão
Utilizar o framework ExtJS para o desenvolvimento do frontend do sistema.

#### Justificativa
O ExtJS é uma escolha apropriada para o desenvolvimento do frontend devido à sua ampla gama de componentes e recursos, que facilitam a criação de interfaces de usuário ricas e responsivas. O framework também possui uma comunidade ativa e fornece suporte para a criação de uma experiência de usuário moderna e intuitiva.

## ADR: 003 - Utilização do PostgreSQL como Banco de Dados  🐘
### Status: Aceito

#### Decisão
Utilizar o PostgreSQL como o banco de dados para o sistema.

#### Justificativa
O PostgreSQL é um sistema gerenciador de banco de dados relacional de código aberto conhecido por sua confiabilidade, desempenho e recursos avançados. Ele suporta consultas complexas, integridade de dados, transações e escalabilidade, o que o torna uma escolha adequada para armazenar e recuperar dados críticos do sistema de gerenciamento de estoque e prescrições.

## ADR: 004 - Utilização do RabbitMQ para Mensageria  🐰
### Status: Aceito

#### Decisão
Utilizar o RabbitMQ como sistema de mensageria no projeto.

#### Justificativa
O RabbitMQ é uma escolha adequada para a implementação de troca de mensagens assíncronas entre os componentes do sistema. Ele implementa o protocolo AMQP e fornece recursos avançados para garantir a entrega confiável das mensagens, o que é essencial para a comunicação eficiente entre os diferentes módulos do sistema.

## ADR: 005 - Utilização do Zabbix para Monitoramento  📊
### Status: Aceito

#### Decisão
Utilizar o Zabbix para o monitoramento do sistema.

#### Justificativa
O Zabbix é uma ferramenta de monitoramento de infraestrutura de código aberto amplamente utilizada, que oferece recursos para monitorar o desempenho, a disponibilidade e a integridade dos componentes do sistema. Com o Zabbix, é possível obter informações em tempo real, gerar alertas e analisar métricas, permitindo uma gestão eficaz e proativa do ambiente de software.

## ADR: 006 - Utilização do Docker para Implantação  🐳
### Status: Aceito

#### Decisão
Utilizar o Docker para a implantação dos componentes do sistema de forma isolada e escalável.

#### Justificativa
O Docker é uma plataforma de virtualização de contêineres que proporciona maior agilidade no processo de desenvolvimento e implantação. Com o Docker, é possível empacotar os componentes do sistema juntamente com suas dependências e configurações, garantindo a consistência e portabilidade entre diferentes ambientes. Além disso, o uso do Docker facilita o gerenciamento e a escalabilidade dos componentes, permitindo implantações independentes e atualizações simplificadas.

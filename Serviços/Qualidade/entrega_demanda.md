# Relatório Técnico de Entrega de Demanda - Novembro 🚀

## Sumário 📑
1. [Desenvolvimento Inicial da Arquitetura do ViBlue](#1-desenvolvimento-inicial-da-arquitetura-do-viblue)
2. [Criação de Entidades Iniciais de Movimentação de Estoque](#2-criação-de-entidades-iniciais-de-movimentação-de-estoque)
3. [Desenvolvimento do Domínio da Aplicação no Ambiente de Máquina](#3-desenvolvimento-do-domínio-da-aplicação-no-ambiente-de-máquina)
4. [Criação do Serviço de Autenticação](#4-criação-do-serviço-de-autenticação)
5. [Atuações do Time de Produto](#5-atuações-do-time-de-produto)
6. [Monitoração](#6-monitoração)
7. [Entregas de Dezembro](#7-entregas-de-dezembro)

## 1. Desenvolvimento Inicial da Arquitetura do ViBlue 🏗️
   - **Implementação:**
     - Desenvolvimento seguindo a arquitetura DDD.
   - **Tecnologias Utilizadas:**
      - C#
         - MediatR (Padrão de mediação de resolução de problemas)
         - FluentValidator (Validação de bibliotecas)
         - Entity Framework (ORM para acesso ao banco)
         - Dapper (Biblioteca de acesso a banco de dados)
         - MassTransit (Biblioteca agnóstica para envio de fila)
         - AutoRegisterDi (Registro de injeção de dependência)
         - HealthChecks
            - NpgSql (Verificação de disponibilidade do banco de dados)
            - Rabbitmq (Verificação de disponibilidade da Mensageria Rabbitmq)
            - System (Verificação de uso de Memória, Uso do processador)
      - Banco de dados: PostgreSQL.
      - Docker.

## 2. Criação de Entidades Iniciais de Movimentação de Estoque 📦
   - **Entidades Criadas:**
      - KitProductItem
      - Location
      - Manufactory
      - Product
      - Separation
      - SeparationHistory
      - SeparationItem
      - SeparationItemMovement
      - StockPlace
      - StockPlaceItem
      - StockPlaceItemProduct
      - StockPlaceItemProductCategoryGrant
      - StockPlaceItemProductGrant
      - StockPlaceItemProductGrantPosition
      - StockPlaceProduct
      - StockProduct
      - StockTemplate
      - StockTemplateItem
      - TenantProduct

## 3. Desenvolvimento do Domínio da Aplicação no Ambiente de Máquina 🔄
   - Implementação bem-sucedida do MOC para otimizar a integração com o OPUS5.

## 4. Criação do Serviço de Autenticação 🔒
   - Desenvolvimento e implementação do serviço de autenticação para fortalecer a segurança do sistema.
   - Desenvolvimento do Frontend da Aplicação.
   - Desenvolvimento da API de Autenticação em Identity.

## 5. Atuações do Time de Produto 🛠️
   - Sessão de treinamento realizada com sucesso, capacitando a equipe para efetuar operações eficientes com as novas implementações.
   - **Criação do Mockup para Todas as Telas de Ordem de Serviço:**
     - Desenvolvimento de mockups visuais para representar todas as telas do processo de ordem de serviço.
   - **Criação das Histórias de Usuário:**
     - Elaboração detalhada das histórias de usuário para orientar o desenvolvimento.
   - **Desenvolvimento do Fluxograma para a Ordem de Serviço:**
     - Criação de um fluxograma visual para mapear o fluxo completo da ordem de serviço.


## 6. Monitoração 📊
-  ![image.png](/.attachments/image-657ca90c-4fb5-4238-b55b-9cc78c37e872.png)

## 7. Entregas de Dezembro 🎁
   - **Cadastro de Equipamento:**
     - Concluída a implementação do cadastro de equipamento com sucesso.
   - **Criação de Ordens de Serviço:**
     - O sistema agora permite a criação eficiente de ordens de serviço.
   - **Envio de Ordens de Serviço para os Equipamentos:**
     - Desenvolvimento finalizado para enviar ordens de serviço de maneira eficaz aos equipamentos.
   - **Novas Entidades Implementadas:**
      - Produto
      - Demanda
      - Pedido


**Autor:** Frank Willian
   - *Cargo:* Gerente de Software


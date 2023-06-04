# 1. OBJETIVO
Aceitação é uma fase do processo de engenharia que tem como objetivo verificar se o escopo de uma aplicação está sendo executado com sucesso antes da disponibilização de uma nova versão (release). Os testes nessa fase são executados num ambiente que simula o ambiente real do usuário. Os testes de aceitação auxiliam o dono do produto a priorizar quais defeitos (bugs) devem ser corrigidos, já que, quando executados com frequência, apontam para o time quais defeitos ou falhas foram inseridos durante o desenvolvimento.

# 2. CONSTRUÇÃO DO TESTE
Como regra uma vez gerado que o backlog de atividades com as suas respectivas histórias, cabe ao profissional da qualidade ou qualquer outro responsável por especificar os requisitos, escrever na descrição do card da história as condições mais importantes da funcionalidade. Essa técnica evita o retrabalho muitas vezes encontrado em modelos tradicionais de desenvolvimento de software, onde o engenheiro de requisitos transcreve toda a especificação e, só depois, os testes são criados para essa especificação, havendo uma redundância de informações.
Os testes de aceitação concentram-se nas regras de negócio e não precisam ser exaustivos — com milhares de cenários, mas devem, sim, conter a representação do fluxo que o usuário faria em produção, garantindo a qualidade aceitável determinada pelo time.

## 2.1. DESENVOLVENDO O TESTE
A escrita de um cenário de teste deve sempre responder as seguintes perguntas:
1. É de fácil entendimento?
2. Demanda muito tempo para leitura?
3. É abrangente sem ser exaustivo?
4. Você sabe o que está construindo nesse teste?
5. Qual o valor que esse teste agrega?

# 3. APLICAÇÃO DO TESTE
Ao receber o release notes de validação da implementação do código o profissional da qualidade ou qualquer outro responsável pela realização do teste identifica no tópico 4 da documentação de release os casos de teste descritos. Ao finalizar o teste de aceitação o testador deve descrever seus resultados na documentação.
Periodicamente, os testes precisam ser revisados, já que funcionalidades tendem a ser removidas ou alteradas.
Usando testes de aceitação, não apenas o time de desenvolvimento, mas também os clientes se sentem mais confiantes no produto entregue, uma vez que testes foram executados para as funcionalidades solicitadas.

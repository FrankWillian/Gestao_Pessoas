## Análise de Viabilidade de Projeto 💼

## Sumário

- [Análise de Viabilidade de Projeto](#análise-de-viabilidade-de-projeto)
- [Pontos de Função](#pontos-de-função)
- [Esforço (E)](#esforço-e)
- [Tempo de Desenvolvimento Ótimo](#tempo-de-desenvolvimento-ótimo)
- [Tamanho da Equipe](#tamanho-da-equipe)


### Pontos de Função 📊

Vou calcular os pontos de função para os requisitos adicionais que você mencionou. Usarei o método de contagem rápida para realizar essa estimativa. Considerarei a complexidade de cada requisito para determinar o número de pontos de função.

- Monitoramento total das prescrições, separações e abastecimentos realizados nos equipamentos: Requisito de média complexidade - 3 pontos de função.
- Acesso 24 horas aos dados: Requisito de baixa complexidade - 2 pontos de função.
- Acesso via mobile: Requisito de baixa complexidade - 2 pontos de função.
- Cadastro de usuários:
  - Cadastro de todos os dados, com exceção do cadastro da digital nos equipamentos com leitor de digital: Requisito de alta complexidade - 6 pontos de função.
  - Possibilidade de edição, exclusão e alteração de permissão do usuário: Requisito de média complexidade - 3 pontos de função.
  - Níveis de usuário: Administrador (ADM), Farmacêutico e Operador: Requisito de média complexidade - 3 pontos de função.
- API de integração:
  - Envio em tempo real de todos os dados de prescrição dos equipamentos: Requisito de alta complexidade - 6 pontos de função.
  - Status da rede de comunicação: Requisito de baixa complexidade - 2 pontos de função.
- Acesso a relatórios:
  - Dados de usuários: Requisito de média complexidade - 3 pontos de função.
  - Produtividade: Requisito de baixa complexidade - 2 pontos de função.
  - Inventário de todos os produtos: Requisito de média complexidade - 3 pontos de função.
- Sincronização de dados em duas vias:
  - O cadastro de usuários realizado na central deve ser sincronizado com cada equipamento: Requisito de média complexidade - 3 pontos de função.
  - Sincronização para cadastro de medicamentos, pacientes e outros dados: Requisito de média complexidade - 3 pontos de função.
- Agendamento de abastecimento por equipamento: Requisito de baixa complexidade - 2 pontos de função.
- Controle de acesso centralizado por perfil de usuário: Requisito de média complexidade - 3 pontos de função.
- Possibilidade de propagação imediata de atualizações de dados: Requisito de média complexidade - 3 pontos de função.
- Envio de ordem de separação: Requisito de média complexidade - 3 pontos de função.
- Envio de ordem de reabastecimento: Requisito de média complexidade - 3 pontos de função.
- Bloqueio de usuário: em caso de emergência, o usuário perderá o acesso a todos os equipamentos: Requisito de média complexidade - 3 pontos de função.
- Dashboard para acompanhamento geral dos equipamentos: Requisito de baixa complexidade - 2 pontos de função.
- Identificação de equipamentos com produtos abaixo do estoque mínimo: Requisito de baixa complexidade - 2 pontos de função.
- Identificação de equipamentos offline: Requisito de baixa complexidade - 2 pontos de função.
- Transações seguras via HTTPS, garantindo

 segurança na comunicação: Requisito de baixa complexidade - 2 pontos de função.
- Backup de base de dados com retenção de 30 dias: Requisito de média complexidade - 3 pontos de função.
- Compatibilidade com padrões web e conformidade com a plataforma Windows: Requisito de média complexidade - 3 pontos de função.
- Experiência do usuário aprimorada:
  - Telas de prescrição, reabastecimento e movimentação: Requisito de média complexidade - 3 pontos de função.
  - Filtros de busca por ID ou paciente em todas as telas: Requisito de média complexidade - 3 pontos de função.

Total de pontos de função = 70 pontos de função.

### Esforço (E) ⌛

Antes de tudo, precisamos identificar o tipo de aplicativo com o qual estamos trabalhando. Neste projeto, estaremos utilizando o conceito de cliente-servidor, com um expoente de 0,37 para o cálculo do esforço. A linguagem de programação JavaScript utiliza o valor de 10 para o cálculo de homem-hora (hh).

Para calcular o esforço necessário em horas para um projeto de 70 pontos de função, considerando uma taxa de homem-hora de 10, podemos usar a fórmula:

```
Esforço (em horas) = PF * HHT
```

Substituindo os valores na fórmula, temos:

```
Esforço (em horas) = 70 * 10
Esforço (em horas) = 700 horas
```

Portanto, o esforço necessário para um projeto de 70 pontos de função, considerando uma taxa de homem-hora de 10, seria de 700 horas.

### Tempo de Desenvolvimento Ótimo ⏳

O tempo de desenvolvimento ótimo para uma aplicação de 700 pontos de função e um expoente de 0,37 pode ser calculado utilizando a fórmula:

```
Tempo de Desenvolvimento (em meses) = 2,5 x (PF/100) ^ 0,37
```

Substituindo o valor de 700 pontos de função na fórmula, temos:

```
Tempo de Desenvolvimento ≈ 2,5 x (700/100) ^ 0,37
Tempo de Desenvolvimento ≈ 2,5 x 7 ^ 0,37
Tempo de Desenvolvimento ≈ 2,5 x 2,063
Tempo de Desenvolvimento ≈ 5,157 meses
```

Portanto, o tempo de desenvolvimento ótimo para uma aplicação de 700 pontos de função e um expoente de 0,37 é aproximadamente 5,157 meses.

### Tamanho da Equipe 👥

Para determinar o tamanho da equipe necessário para um esforço de 700 pessoas-hora, considerando um tempo de desenvolvimento de 5,1 meses, 22 dias de trabalho por mês e 6 horas efetivas de trabalho por dia, podemos utilizar a fórmula:

```
Tamanho da equipe = Esforço Total / (Tempo de Desenvolvimento x TD x TE)
```

Onde:
- Esforço Total é igual a 700 pessoas-hora.
- O tempo de desenvolvimento é igual a 5,1 meses.
- TD é igual a 22 dias/mês.
- TE é

 igual a 6 horas/dia.

Substituindo os valores na fórmula, temos:

```
Tamanho da equipe = 700 / (5,1 x 22 x 6)
Tamanho da equipe ≈ 700 / 673,2
Tamanho da equipe ≈ 1,04
```

Portanto, considerando os valores fornecidos, seria necessário uma equipe de aproximadamente 1 pessoa para realizar o projeto em 5,1 meses.
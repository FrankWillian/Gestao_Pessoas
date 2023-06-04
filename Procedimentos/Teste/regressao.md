# Objetivo

O teste de regressão é um certo tipo teste de software para determinar se uma alteração recente no software ou nas configurações do programa não afeta adversamente as funções existentes. O teste de regressão é uma técnica do teste de software que consiste na aplicação de versões mais recente do software, para garantir que não surgiram novos defeitos em componentes já analisados. Se, ao juntar o novo componente ou as suas alterações com os componentes restantes do sistema surgirem novos defeitos em componentes inalterados, então considera-se que o sistema regrediu.

## Técnicas de Testes de Regressão

A manutenção do software se refere a melhorias, correções de erros, otimização e remoção de recursos existentes do software. Essas mudanças podem fazer com que o software inadvertidamente e despercebido não funciona mais corretamente. Para determinar isso, o teste de regressão é necessário. Podemos realizar testes de regressão usando as seguintes técnicas:

### 2.1. TESTE TUDO NOVAMENTE
Este é um dos métodos de teste de regressão em que temos que executar novamente todos os casos de teste no conjunto de teste existente. Isso é muito caro porque requer muito tempo e recursos. Se houver um projeto, o tempo e o dinheiro provavelmente nem estão orçados.

### 2.2. SELEÇÃO DE TESTE DE REGRESSÃO
#### 2.2.1. Em vez de executar todo o conjunto de testes novamente, é melhor selecionar uma parte do conjunto de Testes que precisamos executar.
#### 2.2.2. Os casos de teste selecionados podem ser categorizados como casos de teste reutilizáveis, ou casos de teste obsoletos.
#### 2.2.3. Também podemos usar casos de teste reutilizáveis, em ciclos de regressão sucessivos.
#### 2.2.4. Não podemos usar casos de teste desatualizados em ciclos sucessivos.

### 2.3. PRIORIZAÇÃO DE CASOS DE TESTE
Priorize certos casos de teste. Dependendo do impacto nos processos de negócio, optamos pelas funções críticas e frequentemente utilizadas. A seleção de casos de teste com base na prioridade reduzirá muito o impacto do teste de regressão no projeto.

## 3. SELEÇÃO DE CASOS DE TESTE
Na prática, parece que um grande número de erros de software relatados se deve a correções de última hora. Essas correções também causam efeitos colaterais indesejados. Portanto, selecionar os casos de teste certos para o teste de regressão é uma arte e não tão fácil. No entanto, podemos fazer testes de regressão eficazes, selecionando os seguintes casos de teste:
### 3.1.  Casos de teste que frequentemente revelaram erros no passado.
### 3.2.  Funcionalidade mais visível para os usuários.
### 3.3. Casos de teste que representam os recursos mais importantes do software.
### 3.4. Teste casos de funcionalidade que é frequentemente e recentemente ajustada.
### 3.5. Tudo casos de teste de integração.
### 3.6. Todos os casos de teste complexos.
### 3.7. Casos de teste de valor limite.
### 3.8. Exemplo de casos de teste bem-sucedidos.
### 3.9. Exemplo de casos de teste para falhas anteriores

## 4. APLICAÇÃO DO TESTE

Claro, vou adicionar uma menção ao autor da Lei de Little no documento Markdown:

```markdown
# Lei de Little 📈

A Lei de Little é um princípio fundamental na teoria das filas, que estabelece uma relação importante entre as métricas de sistemas de filas. Ela é representada pela fórmula: L = λW

## Sumário

1. [O que é a Lei de Little?](#o-que-é-a-lei-de-little)
2. [Autor da Lei de Little](#autor-da-lei-de-little)
3. [Componentes da Lei de Little](#componentes-da-lei-de-little)
4. [Explicação](#explicação)
5. [Exemplo de Cálculo no Desenvolvimento de Software](#exemplo-de-cálculo-no-desenvolvimento-de-software)

## O que é a Lei de Little?

A Lei de Little, nomeada em homenagem ao matemático John D. C. Little, é um princípio fundamental na teoria das filas. Ela descreve uma relação importante entre três métricas cruciais em sistemas de filas ou sistemas de espera:

- **L** 📊: Representa o número médio de entidades no sistema. Em um contexto de desenvolvimento de software, isso pode ser o número médio de tarefas na fila de processamento de um servidor.

- **λ** 📈: Indica a taxa média de chegada de entidades ao sistema. Isso se refere à taxa média com que novas entidades (por exemplo, requisições de clientes) entram no sistema.

- **W** ⏳: Representa o tempo médio que uma entidade passa no sistema. Isso inclui o tempo que a entidade passa na fila de espera e o tempo que a entidade passa sendo atendida ou processada.

A fórmula L = λW é a representação matemática da Lei de Little. Ela afirma que o número médio de entidades no sistema (L) é igual à taxa média de chegada de entidades (λ) multiplicada pelo tempo médio que uma entidade passa no sistema (W). Essa relação é especialmente útil em sistemas de filas, como servidores de aplicação, para entender e dimensionar o desempenho do sistema.

## Autor da Lei de Little
A Lei de Little foi formulada por John D. C. Little, um matemático norte-americano conhecido por suas contribuições para a pesquisa operacional e a teoria das filas. Sua descoberta desempenhou um papel fundamental na compreensão e otimização de sistemas de filas em diversas áreas, incluindo o desenvolvimento de software.

## Componentes da Lei de Little
- **L** 📊: Representa o número médio de entidades no sistema (por exemplo, tarefas na fila de processamento em um servidor de software).

- **λ** 📈: Indica a taxa média de chegada de entidades ao sistema (por exemplo, a taxa média de chegada de requisições de clientes a um servidor de aplicação).

- **W** ⏳: Representa o tempo médio que uma entidade passa no sistema (por exemplo, o tempo médio que uma requisição de cliente passa no servidor, incluindo o tempo na fila e o tempo de processamento).

## Explicação
A Lei de Little sugere que o número médio de entidades em um sistema é igual à taxa média de chegada de entidades multiplicada pelo tempo médio que uma entidade passa no sistema. Isso é útil para entender o comportamento de sistemas de filas, como servidores de aplicação, e dimensioná-los adequadamente para garantir um bom desempenho.

## Exemplo de Cálculo no Desenvolvimento de Software
Suponha um servidor de aplicação em que as requisições dos clientes chegam a uma taxa de 100 requisições por segundo (λ = 100 req/s) e o tempo médio de processamento de uma requisição é de 20 milissegundos (W = 0.02 segundos). Usando a Lei de Little, podemos calcular o número médio de requisições no servidor (L):

L = λW
L = 100 req/s * 0.02 s = 2 requisições

Isso significa que, em média, o servidor terá 2 requisições em processamento a qualquer momento. Esse cálculo pode ajudar os desenvolvedores a dimensionar adequadamente a capacidade do servidor para atender às demandas dos clientes.
```

Agora o documento inclui uma seção que menciona o autor da Lei de Little, John D. C. Little. Você pode copiar e colar este código Markdown em seu documento conforme necessário.


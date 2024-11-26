# Resumo do Laboratório: DIO Azure Lab 2

## Disponibilidade
Todos os recursos da nuvem têm uma porcentagem de disponibilidade, que é a quantidade de tempo que o serviço vai estar no ar e disponível para o uso. Quanto maior a porcentagem de disponibilidade, menor o tempo de **down-time** (indisponibilidade do serviço).

### Tabela de Disponibilidade e Down-time

| Disponibilidade | Down-time Semanal  | Down-time Mensal   | Down-time Anual  |
|-----------------|--------------------|--------------------|------------------|
| 99%             | 1.68 horas         | 7.2  horas         | 3.65 dias        |
| 99.9%           | 10.1 minutos       | 43.2 minutos       | 8.76 horas       |
| 99.95%          | 5 minutos          | 21.6 minutos       | 4.68 horas       |
| 99.99%          | 1.01 minutos       | 4.32 minutos       | 52.56 minutos    |
| 99.999%         | 6 segundos         | 25.9 segundos      | 5.26 minutos     |

### Estratégia de Alta Disponibilidade
A disponibilidade de um serviço pode ser alcançada dependendo da **estratégia** utilizada durante a criação do serviço. Isso envolve o uso de redundâncias, failover e outras práticas de resiliência para minimizar o tempo de inatividade.

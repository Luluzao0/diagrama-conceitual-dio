# Sistema de Controle e Gerenciamento de Execução de Ordens de Serviço em uma Oficina Mecânica

## Entidades

- **Cliente**: Aquele que traz o veículo para a oficina. Atributos podem incluir ID do cliente, nome, endereço, etc.
- **Veículo**: O objeto que é trazido para a oficina para reparos ou revisões. Atributos podem incluir ID do veículo, tipo de veículo, modelo, ano, etc.
- **Ordem de Serviço (OS)**: Documento que detalha os serviços a serem realizados no veículo. Atributos podem incluir número da OS, data de emissão, valor total, status e data de conclusão.
- **Serviço**: O trabalho específico a ser realizado no veículo. Atributos podem incluir ID do serviço, descrição do serviço, valor da mão-de-obra, etc.
- **Peça**: Qualquer peça que possa ser necessária para o serviço. Atributos podem incluir ID da peça, descrição da peça, custo da peça, etc.
- **Mecânico**: O indivíduo ou equipe responsável pela execução do serviço. Atributos podem incluir código do mecânico, nome, endereço e especialidade.

## Relacionamentos

- **Cliente - Veículo**: Um cliente pode possuir um ou mais veículos.
- **Veículo - OS**: Um veículo pode ter uma ou mais ordens de serviço.
- **OS - Serviço**: Uma ordem de serviço pode ter um ou mais serviços.
- **Serviço - Peça**: Um serviço pode exigir zero ou mais peças.
- **Mecânico - OS**: Um mecânico pode trabalhar em uma ou mais ordens de serviço.

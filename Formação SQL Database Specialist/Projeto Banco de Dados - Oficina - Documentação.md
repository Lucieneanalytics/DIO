# Esquema Conceitual - Oficina Mecânica

## Objetivo
Criar o esquema conceitual para o contexto de oficina.

## Pontos Principais

- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica.
- Clientes levam veículos à oficina mecânica para consertos ou revisões periódicas.
- Cada veículo é designado a uma equipe de mecânicos, que identifica os serviços a serem executados e preenche uma Ordem de Serviço (OS) com data de entrega.
- A partir da OS, calcula-se o valor de cada serviço, consultando uma tabela de referência de mão-de-obra.
- O valor de cada peça também compõe a OS.
- O cliente autoriza a execução dos serviços.
- A mesma equipe avalia e executa os serviços.
- Os mecânicos possuem os seguintes atributos:
    - Código
    - Nome
    - Endereço
    - Especialidade
- Cada OS possui os seguintes atributos:
    - Número (n°)
    - Data de emissão
    - Valor total
    - Status
    - Data para conclusão do trabalho

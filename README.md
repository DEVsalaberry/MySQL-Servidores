# Projeto de Gerenciamento de Servidores MySQL

Este repositório contém um script MySQL para criar uma tabela de servidores e inserir dados de exemplo. O script modela informações como nome do servidor, espaço em disco e status de ligação.

## Estrutura da Tabela

A tabela 'servidores' possui os seguintes campos:

- `nome`: Nome do servidor (VARCHAR, até 100 caracteres).
- `espaco_disco`: Espaço em disco do servidor (INT, até 10 dígitos).
- `ligado`: Status de ligação do servidor (BOOL, 0 para desligado, 1 para ligado).

## Dados de Exemplo

O script inclui dados de exemplo para quatro servidores:

1. Servidor 1: Espaço - 32,563,456 | Ligado - Não
2. Servidor 2: Espaço - 32,565,466 | Ligado - Sim
3. Servidor 3: Espaço - 45,698,745 | Ligado - Não
4. Servidor 4: Espaço - 0 | Ligado - Sim

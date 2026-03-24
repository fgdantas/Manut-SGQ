# Telas do Sistema - ManutSGQ

## 1. Dashboard
Objetivo: mostrar rapidamente a situação das manutenções.

Informações principais:
- manutenções preventivas vencidas
- manutenções programadas para hoje
- máquinas paradas
- moldes em manutenção
- ordens abertas
- últimas ocorrências registradas

## 2. Máquinas
Objetivo: cadastrar e consultar todas as máquinas.

Campos:
- código
- nome
- setor
- tonelagem
- fabricante
- modelo
- status
- data da última manutenção
- data da próxima manutenção

## 3. Moldes
Objetivo: cadastrar e consultar todos os moldes.

Campos:
- código
- descrição
- cliente
- produto
- número de cavidades
- status
- local atual
- máquina atual ou última máquina utilizada
- data da última manutenção
- data da próxima manutenção

## 4. Preventivas
Objetivo: controlar os planos de manutenção preventiva.

Campos:
- tipo do ativo (máquina ou molde)
- ativo relacionado
- descrição da atividade
- frequência
- responsável
- última execução
- próxima execução
- status

## 5. Corretivas
Objetivo: registrar falhas e ações corretivas.

Campos:
- tipo do ativo (máquina ou molde)
- ativo relacionado
- data da ocorrência
- problema relatado
- causa
- ação executada
- peças trocadas
- tempo de parada
- responsável
- status

## 6. Histórico
Objetivo: visualizar todo o histórico de manutenções por máquina ou molde.

Filtros:
- por máquina
- por molde
- por período
- por tipo de manutenção
- por responsável

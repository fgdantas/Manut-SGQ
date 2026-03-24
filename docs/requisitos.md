# Requisitos do Sistema - ManutSGQ

## Objetivo
Controlar manutenções preventivas e corretivas dos equipamentos da empresa, com rastreabilidade e apoio ao SGQ.

## Funcionalidades da versão 1

### Cadastro de equipamentos
Cada equipamento deve conter:
- Código
- Nome
- Setor
- Fabricante
- Modelo
- Número de patrimônio ou identificação
- Status (ativo, parado, manutenção, inativo)

### Plano de manutenção preventiva
Cada plano deve conter:
- Equipamento
- Descrição da atividade
- Frequência
- Responsável
- Data da última execução
- Data da próxima execução

### Manutenção corretiva
Cada registro deve conter:
- Equipamento
- Data da ocorrência
- Problema relatado
- Causa
- Ação executada
- Responsável
- Tempo de parada
- Peças trocadas

### Histórico
O sistema deve permitir consultar todo o histórico de manutenção de cada equipamento.

### Indicadores futuros
- Preventivas vencidas
- Corretivas por equipamento
- Tempo parado por equipamento
- MTBF
- MTTR

## Perfis de usuário
- Operador
- Técnico de manutenção
- Líder/Gestor
- Qualidade/SGQ
- Administrador

# Modelo de Dados Inicial

## Máquina
- id
- codigo
- nome
- setor
- tonelagem
- fabricante
- modelo
- status

## Molde
- id
- codigo
- descricao
- cliente
- produto
- cavidades
- status
- local_atual
- maquina_atual

## Preventiva
- id
- tipo_ativo
- ativo_id
- descricao
- frequencia
- ultima_execucao
- proxima_execucao
- responsavel
- status

## Corretiva
- id
- tipo_ativo
- ativo_id
- data_ocorrencia
- problema
- causa
- acao_executada
- responsavel
- tempo_parada
- pecas_trocadas
- status

# Modelo de Dados

Este documento descreve as principais entidades do sistema e suas informações.

## Usuário
- Nome
- País de origem
- Idiomas
- Tipo de viagem
- Reputação
- Histórico de encontros

## Viagem
- Usuário associado
- Cidade e país de destino
- Datas de início e fim
- Aeroporto
- Status da viagem

## Match
- Usuários envolvidos
- Motivo do match (datas, local, interesses)
- Score de compatibilidade
- Status (ativo, recusado, aceito)

## Encontro
- Match associado
- Data e horário
- Local público
- Status (agendado, realizado, cancelado)

## Reputação
- Usuário avaliado
- Feedback pós-encontro
- Data da avaliação
- Validade temporal

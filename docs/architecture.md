# Arquitetura do Sistema

Este documento descreve, de forma simples, como a plataforma é organizada
internamente e como suas partes se comunicam.

## Visão Geral

O sistema é dividido em três partes principais:
- Frontend
- Backend
- Banco de Dados

Cada parte tem uma responsabilidade clara para manter o sistema organizado,
seguro e fácil de evoluir.

## Frontend
- Interface usada pelo usuário
- Responsável por:
  - Cadastro
  - Visualização de viagens
  - Recebimento de matches
  - Agendamento de encontros
- Comunicação com o backend via API

## Backend
- Coração da aplicação
- Responsável por:
  - Regras de negócio
  - Cálculo de matches
  - Verificações de segurança
  - Gestão de usuários e viagens
- Exposição de endpoints (API)

## Banco de Dados
- Armazena informações de forma segura
- Principais dados:
  - Usuários
  - Viagens
  - Matches
  - Encontros
  - Reputação

## Segurança
- Autenticação de usuários
- Controle de acesso
- Proteção de dados sensíveis

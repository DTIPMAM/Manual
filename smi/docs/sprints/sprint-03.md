# Sprint 03 - Painel de Inteligência do Acervo de Armamentos

**Projeto:** Sistema Modular Integrado (SMI)  
**Módulo:** Relatórios / Dashboard  
**Versão:** 3.11.0  
**Status:** Em andamento  
**Início:** 21/07/2026

---

# Objetivo

Transformar o Dashboard Executivo em um Painel de Inteligência, permitindo análises dinâmicas do acervo de armamentos através de filtros e visualizações interativas.

---

# Motivação

O dashboard atual apresenta informações estáticas.

A nova implementação permitirá consultas dinâmicas, reutilização da API e expansão para futuras análises sem necessidade de criação de novos endpoints.

---

# Escopo

## Backend

- Criar endpoint `/dashboard-api/analise`
- Implementar filtros dinâmicos
- Centralizar regras no `DashboardService`
- Garantir performance das consultas

## Frontend

- Criar painel de filtros
- Criar componente de gráfico dinâmico
- Atualizar cards automaticamente
- Melhorar a experiência do usuário

---

# Arquitetura

Frontend (Angular)

↓

Dashboard Service

↓

DashboardApiController

↓

DashboardService

↓

PostgreSQL

---

# Tarefas

## Backend

- [ ] Criar endpoint
- [ ] Implementar filtros
- [ ] Retornar JSON padronizado
- [ ] Testar consultas

## Frontend

- [ ] Criar Dashboard Inteligência
- [ ] Criar componente de filtros
- [ ] Criar componente do gráfico
- [ ] Integrar API

## Documentação

- [ ] Documentar API
- [ ] Criar ADR
- [ ] Atualizar Arquitetura

---

# Critérios de Aceite

- Endpoint funcionando
- Filtros funcionando
- Frontend integrado
- Documentação atualizada
- Testes concluídos

---

# Histórico

| Data | Alteração | Responsável |
|------|-----------|-------------|
|21/07/2026|Criação da Sprint|Equipe SMI|

# Dashboard de Armamentos — Sprint 1

## Data

23 de julho de 2026.

## Branch

`feature/dashboard-armamentos`

## Objetivo

Criar uma nova página inicial para o módulo de Armamentos, transformando o card existente no Painel Administrador em uma porta de entrada para funcionalidades operacionais e futuras ferramentas de inteligência gerencial.

## Implementações realizadas

### 1. Nova Home do módulo

Foi criado o componente:

`ArmamentoHomeComponent`

A nova Home passou a ser acessada pela rota:

`/home/admin/armamento`

### 2. Preservação da tela de gerenciamento

O componente existente:

`ArmamentoAdminComponent`

foi mantido sem alterações funcionais e passou a ser acessado pela rota:

`/home/admin/armamento/gerenciar`

### 3. Atualização das rotas

A estrutura de navegação do módulo passou a seguir o fluxo:

/home/admin/armamento
    ├── gerenciar
    ├── editar
    ├── armas-excluidas
    └── historico/:id


# Melhorias identificadas

## Para Sprint 2

### Dashboard

- Tornar os cards clicáveis.
- Abrir Gerenciar Armamentos já filtrado.
- Drill-down dos gráficos.
- Navegação por fabricante.
- Navegação por lotação.

**Motivo**

Melhoria identificada durante a homologação da Sprint 1.
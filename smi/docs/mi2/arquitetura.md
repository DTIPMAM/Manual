
# MI² — Módulo de Integridade e Inteligência

## 1. Visão geral

O MI² é um módulo interno do Sistema Modular Integrado — SMI, criado para apoiar:

- integridade dos dados;
- qualidade da informação;
- identificação de inconsistências;
- produção de indicadores;
- inteligência organizacional;
- apoio à tomada de decisão.

O módulo será desenvolvido inicialmente sobre os dados de armamentos, utilizando a infraestrutura existente do SMI.

A arquitetura deverá permanecer reutilizável para futuras expansões, sem antecipar módulos que ainda não existem ou que ainda não foram integrados ao MI².

---

## 2. Objetivo arquitetural

O principal objetivo da arquitetura é permitir a criação de novas regras de auditoria sem exigir alterações na infraestrutura central do MI².

Cada nova regra deverá ser independente, testável e descoberta automaticamente pelo sistema.

Princípio central:

> Nenhuma nova regra de negócio deverá exigir alteração no IntegridadeService.

---

## 3. Escopo atual

Nesta etapa, o MI² atua exclusivamente sobre o domínio de armamentos.

Estrutura atual:

```text
rules/
└── armamento/
    └── ArmasSemModeloRule.php
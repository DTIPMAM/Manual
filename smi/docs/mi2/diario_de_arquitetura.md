# Diário de Arquitetura do MI²

## 22/07/2026

### Decisão 001

Toda auditoria deverá implementar RuleInterface.

---

### Decisão 002

Toda Rule retornará obrigatoriamente ResultadoAuditoria.

---

### Decisão 003

O IntegridadeService será responsável exclusivamente pela execução das Rules.

---

### Decisão 004

O módulo será compatível com PHP 7.2 até futura atualização do ambiente.

---

### Decisão 005

Toda auditoria possuirá:

- código
- categoria
- gravidade
- impacto
- mensagem
- quantidade
- dados

---

### Decisão 006

As auditorias poderão ser executadas independentemente da interface gráfica através do comando:

php yii integridade/testar


# 24/07/2026

## Dashboard de Armamentos

### Decisão:

Os cards permanecerão apenas informativos na versão 1.

Motivo:

Priorizar homologação.

Próxima evolução:

Implementar Drill Down utilizando filtros automáticos na tela
Gerenciar Armamentos.
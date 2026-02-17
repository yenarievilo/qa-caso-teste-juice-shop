# TC-SEC-001 — SQL Injection no fluxo de autenticação

## Objetivo
Verificar se o sistema é resiliente a ataques de SQL Injection
no campo de autenticação.

## Tipo
Teste de segurança – Input validation

## Severidade
Crítica

## OWASP Category
Injection (A03:2021)

## Ambiente
OWASP Juice Shop – Localhost

## Pré-condições
Aplicação em execução
Tela de login acessível

---

## Passos

1. Acessar a página de login
2. Inserir payload malicioso no campo email
3. Inserir senha arbitrária
4. Submeter autenticação

---

## Payload utilizado

OR 1=1 
---

## Resultado esperado

- Sistema rejeita autenticação
- Nenhum acesso não autorizado
- Erro tratado sem stack trace
- Sem exposição de informações internas
- Evento registrado em logs de segurança

---

## Resultado obtido


---

## Evidências
- Screenshot do comportamento
- Logs capturados 

---

## Risco caso falhe

Permite bypass de autenticação,
comprometendo contas de usuários.

---

## Status
-

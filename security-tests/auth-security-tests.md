# TC-SEC-001 — Tentativa de SQL Injection

## Tipo
Teste de segurança

## Passos
1. Inserir payload no campo email
2. Tentar autenticar

## Payload
' OR 1=1 --

## Resultado esperado
Login negado e erro tratado com segurança

## Status
Pending

# TP - 001 - Plano de teste - lançamento - Besouro Sistemas

---

# 1. Objetivo

Garantir que as funiconalidades críticas do sistema estejam funcoinando corretamente antes da implantação do primeiro cliente, assegurando estabilidade, confiabilidade e integridade.

---

# 2. Escopo

## Funcionalidades incluídas

- Autenticação de usuários
- Cadastro de usuários
- Convite de funcionários
- Dashboard principal
- Gestão financeira
- fluxo de venda

## Funcionalidades não incluídas

- Testes de Performance
- Testes mobile
- Testes de carga
- Integração com IA

---

# 3. Estratégia de Testes

serão realizados os seguintes tipos de testes:

- Funcionais(para validar regras de negócios)
- Regressão(para validar funcionalidades relacionadas a novas features)
- Exploratório(para procurar erros não previstos)
- API 
- UI 
- Smoke

---

# 4. Ambiente de testes

## Frontend
- React

## Backend
- Node.js
- Express

## Banco de dados
- PostgreSQL

---

# 5. Critérios de entrada

Os testes poderão ser iniciados quando: 

- Ambiente de produção e homologação no ar
- Requisitos definidos
- Integração front-back-banco estabilizada e finalizada

---

# 6. Critérios de saída

Os testes serão encerrados quando: 

- Todos os casos críticos forem executados
- Nenhum bug bloqueante estiver aberto
- Fluxos principais estiverem estáveis

---

# 7. Suítes de teste relacionados

suite de autenticacao
suite da dashboard
suite do financeiro
suite de vendas

---

# 8. Casos de teste críticos

 - Login com credenciais válidas
 - Login com credenciais inválidas
 - login sem convite
 - login com convite
 - lançamento de venda
 - abertura e fechamento de caixa

---

# 9. Responsáveis

Davi -> QA
Davi -> Automação
Davi -> Execução de testes manuais

--- 

# 10. Evidências

As evidências serão armazenadas em:

```text
/evidences/screenshoots
/evidences/videos
```

---

# 11. Ferramentas utilizadas

- Postman
- Cypress

---

# 12. Observações

Todos os bugs encontrados deverão possuir:

- Evidência em foto ou vídeo
- Passos para reprodução
- Resultado esperado
- Resultado atual
- Severidade 
- Prioridade
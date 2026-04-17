# 📋 Plano de Teste

## 1. Identificação

| Campo            | Descrição                         |
|------------------|-----------------------------------|
| **Projeto**      | [Nome do Projeto]                 |
| **Versão**       | [ex: 1.0.0]                       |
| **Responsável**  | [Nome do QA]                      |
| **Data**         | [DD/MM/AAAA]                      |
| **Status**       | [ ] Em elaboração / [ ] Aprovado  |

---

## 2. Objetivo

Descrever o objetivo geral dos testes, o que será validado e qual o escopo da execução.

> Exemplo: Validar o fluxo de login, cadastro e recuperação de senha da aplicação X na versão Y.

---

## 3. Escopo

### ✅ O que será testado
- Funcionalidade A
- Funcionalidade B
- Funcionalidade C

### ❌ O que NÃO será testado
- Funcionalidade D (fora do escopo desta sprint)
- Integrações com sistemas externos

---

## 4. Tipos de Teste

| Tipo                  | Aplicável? | Observação              |
|-----------------------|------------|-------------------------|
| Teste Funcional       | ✅ Sim      |                         |
| Teste de Regressão    | ✅ Sim      | Após correção de bugs   |
| Teste de Usabilidade  | ⬜ Não      |                         |
| Teste de Performance  | ⬜ Não      |                         |
| Teste de Segurança    | ⬜ Não      |                         |

---

## 5. Critérios de Entrada

> Os testes só iniciam quando:
- [ ] Build disponível no ambiente de homologação
- [ ] Requisitos documentados e aprovados
- [ ] Dados de teste preparados

---

## 6. Critérios de Saída

> Os testes são encerrados quando:
- [ ] 100% dos casos de teste executados
- [ ] Todos os bugs críticos corrigidos e retestados
- [ ] Taxa de aprovação ≥ 95%

---

## 7. Ambiente de Teste

| Item           | Descrição                  |
|----------------|----------------------------|
| **Ambiente**   | Homologação / Staging       |
| **URL**        | [https://...]               |
| **Navegadores**| Chrome, Firefox, Edge       |
| **Dispositivos**| Desktop, Mobile (Android/iOS)|

---

## 8. Riscos e Mitigações

| Risco                              | Probabilidade | Impacto | Mitigação                         |
|------------------------------------|---------------|---------|-----------------------------------|
| Ambiente instável                  | Média         | Alto    | Comunicar equipe de infra         |
| Mudança de requisito em execução   | Alta          | Alto    | Reavaliar escopo e prazo          |
| Falta de dados de teste            | Baixa         | Médio   | Preparar massa de dados com antecedência |

---

## 9. Cronograma

| Atividade              | Início       | Fim          | Responsável  |
|------------------------|--------------|--------------|--------------|
| Elaboração do plano    | DD/MM/AAAA   | DD/MM/AAAA   | [Nome]       |
| Criação dos casos      | DD/MM/AAAA   | DD/MM/AAAA   | [Nome]       |
| Execução dos testes    | DD/MM/AAAA   | DD/MM/AAAA   | [Nome]       |
| Reporte de resultados  | DD/MM/AAAA   | DD/MM/AAAA   | [Nome]       |

---

## 10. Aprovação

| Nome       | Cargo         | Assinatura | Data       |
|------------|---------------|------------|------------|
| [Nome]     | QA Lead       |            |            |
| [Nome]     | Dev Lead      |            |            |
| [Nome]     | Product Owner |            |            |

# ✅ Checklist de Regressão

**Projeto:** [Nome do Projeto]  
**Versão testada:** [ex: 2.4.0]  
**Responsável:** [Nome do QA]  
**Data de execução:** [DD/MM/AAAA]  
**Ambiente:** Homologação / Staging

---

## Como usar este checklist

- Marque ✅ quando o item estiver **OK**
- Marque ❌ quando houver **falha** (abra um bug report)
- Marque ⚠️ quando estiver **bloqueado** ou com comportamento inesperado
- Deixe ⬜ quando **não aplicável** ou **não testado** nesta rodada

---

## 1. Autenticação

| # | Item                                                       | Status | Observação |
|---|------------------------------------------------------------|--------|------------|
| 1 | Login com credenciais válidas                              | ⬜     |            |
| 2 | Login com e-mail inválido exibe mensagem de erro           | ⬜     |            |
| 3 | Login com senha incorreta exibe mensagem de erro           | ⬜     |            |
| 4 | Logout encerra a sessão corretamente                       | ⬜     |            |
| 5 | Sessão expira após tempo de inatividade                    | ⬜     |            |
| 6 | Recuperação de senha envia e-mail corretamente             | ⬜     |            |
| 7 | Redefinição de senha funciona com token válido             | ⬜     |            |

---

## 2. Cadastro / Criação de Conta

| # | Item                                                       | Status | Observação |
|---|------------------------------------------------------------|--------|------------|
| 1 | Cadastro com dados válidos é concluído com sucesso         | ⬜     |            |
| 2 | Campo obrigatório vazio exibe mensagem de erro             | ⬜     |            |
| 3 | E-mail duplicado exibe mensagem de erro                    | ⬜     |            |
| 4 | Validação de formato de e-mail funciona                    | ⬜     |            |
| 5 | Confirmação de senha valida campos iguais                  | ⬜     |            |
| 6 | E-mail de confirmação é enviado após cadastro              | ⬜     |            |

---

## 3. Navegação e Layout

| # | Item                                                       | Status | Observação |
|---|------------------------------------------------------------|--------|------------|
| 1 | Menu principal está funcional e todos os links redirecionam corretamente | ⬜ | |
| 2 | Página carrega sem erros no console (F12)                  | ⬜     |            |
| 3 | Layout responsivo em mobile (360px)                        | ⬜     |            |
| 4 | Layout responsivo em tablet (768px)                        | ⬜     |            |
| 5 | Botão "Voltar" do navegador não quebra o fluxo             | ⬜     |            |
| 6 | Links de rodapé funcionam corretamente                     | ⬜     |            |
| 7 | Favicon e título da aba estão corretos                     | ⬜     |            |

---

## 4. Formulários Gerais

| # | Item                                                       | Status | Observação |
|---|------------------------------------------------------------|--------|------------|
| 1 | Campos obrigatórios são validados antes de enviar          | ⬜     |            |
| 2 | Mensagens de erro são claras e exibidas próximas ao campo  | ⬜     |            |
| 3 | Formulário não envia com dados inválidos                   | ⬜     |            |
| 4 | Formulário envia com dados válidos                         | ⬜     |            |
| 5 | Botão de envio desabilita após clique (evita duplo envio)  | ⬜     |            |
| 6 | Mensagem de sucesso é exibida após envio                   | ⬜     |            |

---

## 5. [Módulo Específico — ex: Carrinho / Dashboard / Perfil]

| # | Item                                                       | Status | Observação |
|---|------------------------------------------------------------|--------|------------|
| 1 | [Descrever item de teste]                                  | ⬜     |            |
| 2 | [Descrever item de teste]                                  | ⬜     |            |
| 3 | [Descrever item de teste]                                  | ⬜     |            |
| 4 | [Descrever item de teste]                                  | ⬜     |            |

---

## 6. Fluxos Críticos (Smoke Test)

> Estes itens devem ser verificados **antes de qualquer outra coisa** quando uma nova versão é entregue.

| # | Item                                                       | Status | Observação |
|---|------------------------------------------------------------|--------|------------|
| 1 | Aplicação sobe sem erros                                   | ⬜     |            |
| 2 | Página inicial carrega                                     | ⬜     |            |
| 3 | Login funciona                                             | ⬜     |            |
| 4 | Fluxo principal do sistema é executável                    | ⬜     |            |
| 5 | Não há erros críticos no console                           | ⬜     |            |

---

## Resultado da Rodada

| Total de itens | ✅ OK | ❌ Falhou | ⚠️ Bloqueado | ⬜ Não testado |
|----------------|-------|-----------|--------------|----------------|
|                |       |           |              |                |

**Conclusão:**
> [ ] ✅ Aprovado para release  
> [ ] ❌ Reprovado — há bugs críticos em aberto  
> [ ] ⚠️ Aprovado com ressalvas — bugs não críticos registrados

**Observações gerais:**
>

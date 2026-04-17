# 🧪 Casos de Teste — [Nome da Funcionalidade]

**Projeto:** [Nome do Projeto]  
**Módulo:** [ex: Login / Cadastro / Checkout]  
**Responsável:** [Nome do QA]  
**Data:** [DD/MM/AAAA]  
**Versão:** [1.0]

---

## Legenda de Status

| Símbolo | Status       |
|---------|--------------|
| ✅      | Passou        |
| ❌      | Falhou        |
| ⏳      | Não executado |
| ⚠️      | Bloqueado     |

---

## CT-001 — [Nome do Caso de Teste]

| Campo               | Descrição                                      |
|---------------------|------------------------------------------------|
| **ID**              | CT-001                                         |
| **Funcionalidade**  | [ex: Login com credenciais válidas]            |
| **Prioridade**      | Alta / Média / Baixa                           |
| **Tipo**            | Funcional / Regressão / Fumaça                 |
| **Status**          | ⏳ Não executado                               |

### Pré-condições
- [ ] Usuário cadastrado no sistema
- [ ] Ambiente de homologação disponível
- [ ] Navegador atualizado

### Dados de Teste
| Campo  | Valor              |
|--------|--------------------|
| E-mail | usuario@teste.com  |
| Senha  | Senha@123          |

### Passos
1. Acessar a página de login
2. Inserir e-mail válido no campo "E-mail"
3. Inserir senha válida no campo "Senha"
4. Clicar no botão "Entrar"

### Resultado Esperado
- Usuário é redirecionado para a página inicial
- Nome do usuário é exibido no cabeçalho
- Sessão é iniciada com sucesso

### Resultado Obtido
> _(preencher durante a execução)_

### Evidência
> _(anexar print ou link do vídeo)_

---

## CT-002 — [Nome do Caso de Teste]

| Campo               | Descrição                                      |
|---------------------|------------------------------------------------|
| **ID**              | CT-002                                         |
| **Funcionalidade**  | [ex: Login com senha incorreta]                |
| **Prioridade**      | Alta / Média / Baixa                           |
| **Tipo**            | Funcional / Negativo                           |
| **Status**          | ⏳ Não executado                               |

### Pré-condições
- [ ] Usuário cadastrado no sistema
- [ ] Ambiente de homologação disponível

### Dados de Teste
| Campo  | Valor              |
|--------|--------------------|
| E-mail | usuario@teste.com  |
| Senha  | senhaerrada        |

### Passos
1. Acessar a página de login
2. Inserir e-mail válido no campo "E-mail"
3. Inserir senha **incorreta** no campo "Senha"
4. Clicar no botão "Entrar"

### Resultado Esperado
- Sistema exibe mensagem de erro: _"E-mail ou senha inválidos"_
- Usuário permanece na página de login
- Nenhuma sessão é iniciada

### Resultado Obtido
> _(preencher durante a execução)_

### Evidência
> _(anexar print ou link do vídeo)_

---

## CT-003 — [Nome do Caso de Teste]

| Campo               | Descrição                                      |
|---------------------|------------------------------------------------|
| **ID**              | CT-003                                         |
| **Funcionalidade**  | [descrever aqui]                               |
| **Prioridade**      | Alta / Média / Baixa                           |
| **Tipo**            | Funcional / Regressão / Fumaça                 |
| **Status**          | ⏳ Não executado                               |

### Pré-condições
- [ ] [Condição 1]
- [ ] [Condição 2]

### Dados de Teste
| Campo   | Valor    |
|---------|----------|
| [Campo] | [Valor]  |

### Passos
1. [Passo 1]
2. [Passo 2]
3. [Passo 3]

### Resultado Esperado
- [Descrever o comportamento esperado]

### Resultado Obtido
> _(preencher durante a execução)_

### Evidência
> _(anexar print ou link do vídeo)_

---

## Resumo de Execução

| Total | ✅ Passou | ❌ Falhou | ⏳ Não executado | ⚠️ Bloqueado |
|-------|-----------|-----------|-----------------|--------------|
| 3     | 0         | 0         | 3               | 0            |

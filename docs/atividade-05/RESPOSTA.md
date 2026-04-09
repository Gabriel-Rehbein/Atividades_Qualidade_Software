# 🧩 Atividade PBL – Aula 6  
## Planejamento e Execução de Testes – LocalEats

---

## 📌 1. Plano de Testes

### 🎯 Objetivo
Validar o funcionamento correto das principais funcionalidades do sistema LocalEats, garantindo estabilidade, consistência e confiabilidade.

### 📦 Escopo

**Incluído:**
- Login de usuário  
- Busca de restaurantes  
- Realização de pedidos  
- Avaliação de restaurantes  

**Não incluído:**
- Testes de performance  
- Testes de segurança avançados  
- Integrações externas  

### ⚙️ Funcionalidades testadas
- Login  
- Busca  
- Pedido  
- Avaliação  

### 🧪 Estratégia de Testes
- Testes funcionais (caixa-preta)  
- Testes exploratórios  
- Testes baseados em cenários  

### 👥 Responsáveis
- Planejamento: Equipe QA  
- Execução: Equipe QA  
- Análise: Equipe QA  

---

## 📝 2. Casos de Teste

### ✅ CT01 - Login com sucesso
**Pré-condição:** Usuário cadastrado  
**Passos:**
1. Acessar login  
2. Inserir usuário válido  
3. Inserir senha válida  
4. Clicar em login  

**Resultado esperado:**  
Usuário é redirecionado para a tela principal  

---

### ❌ CT02 - Login com senha inválida
**Pré-condição:** Usuário cadastrado  
**Passos:**
1. Acessar login  
2. Inserir usuário válido  
3. Inserir senha inválida  
4. Clicar em login  

**Resultado esperado:**  
Mensagem de erro exibida  

---

### ✅ CT03 - Busca de restaurante
**Pré-condição:** Sistema ativo  
**Passos:**
1. Acessar campo de busca  
2. Digitar nome do restaurante  
3. Confirmar busca  

**Resultado esperado:**  
Lista de restaurantes correspondente  

---

### ❌ CT04 - Busca inexistente
**Pré-condição:** Sistema ativo  
**Passos:**
1. Buscar restaurante inexistente  

**Resultado esperado:**  
Mensagem "nenhum resultado encontrado"  

---

### ✅ CT05 - Realizar pedido
**Pré-condição:** Usuário logado  
**Passos:**
1. Selecionar restaurante  
2. Escolher produto  
3. Confirmar pedido  

**Resultado esperado:**  
Pedido registrado com sucesso  

---

## ▶️ 3. Execução dos Testes

| Caso | Resultado | Evidência |
|------|----------|----------|
| CT01 | ✅ Passou | Login redirecionou corretamente |
| CT02 | ❌ Falhou | Não exibiu mensagem clara |
| CT03 | ✅ Passou | Busca retornou resultados |
| CT04 | ❌ Falhou | Não mostrou mensagem adequada |
| CT05 | ✅ Passou | Pedido realizado |

---

## 📊 4. Análise dos Resultados

- Testes executados: 5  
- Passaram: 3  
- Falharam: 2  

### 🔍 Problemas encontrados:
- Falta de mensagens de erro claras  
- Tratamento ruim de busca sem resultado  
- Feedback insuficiente ao usuário  

---

## 💡 5. Reflexão

### O plano ajudou?
Sim, trouxe organização e clareza na execução.

### Problemas surgiram só na execução?
Sim, principalmente na interface e feedback ao usuário.

### Melhorias:
- Melhorar mensagens de erro  
- Padronizar feedback visual  
- Adicionar validações  

---

## 🏁 Conclusão

O uso de um plano estruturado permitiu identificar falhas relevantes no sistema, demonstrando a importância de um processo profissional de QA.
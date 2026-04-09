# 🧩 Atividade PBL – Aula 6  
## Planejamento e Execução de Testes – LocalEats

**Centro Universitário Senac-RS**  
ADS - Análise e Desenvolvimento de Sistemas / SPI - Sistemas para Internet  
Unidade Curricular: Qualidade de Software  
Prof.: Luciano Zanuz :contentReference[oaicite:0]{index=0}  

---

## 📌 Contexto

Após compreender diferentes perspectivas de testes (caixa-preta e caixa-branca), a equipe de Qualidade do sistema **LocalEats** precisa avançar:

👉 Organizar e executar testes de forma estruturada e profissional  

Problemas atuais:
- Funcionalidades inconsistentes  
- Comportamentos inesperados  
- Falhas em cenários específicos  
- Dificuldade em reproduzir erros  

Objetivo:
> Garantir que os testes sejam planejados, documentados e executados de forma controlada.

🔗 Sistema: https://local-eats-unisenac.vercel.app/

---

## 🎯 Objetivo

Aplicar de forma prática:
- Planejamento de testes  
- Criação de casos de teste  
- Execução e análise  

⚠️ Não precisa implementar código

---

## 📝 Tarefas

### 🔹 1. Plano de Testes

Definir:
- Objetivo  
- Escopo (o que será / não será testado)  
- Funcionalidades (ex: login, busca, pedido)  
- Estratégia (tipos de teste)  
- Responsáveis  

---

### 🔹 2. Casos de Teste

Criar **mínimo 5 casos**

Cada caso deve ter:
- ID  
- Título  
- Pré-condição  
- Passos  
- Dados de entrada  
- Resultado esperado  

Requisitos:
- 3 cenários de sucesso  
- 2 cenários de erro  

#### Exemplo (Gherkin)

**CT01 - Login com sucesso**
```gherkin
Dado que estou na página de login
E que informei o username standard_user
E que informei o password secret_sauce
Quando eu clicar em Login
Então o sistema apresenta a página de produtos
# Diagnóstico de Qualidade – Startup Local Eats

## 1. Diagnóstico da Situação Atual

### Cenário Provável
Atualmente, a startup deve contar apenas com desenvolvedores (fullstack) e talvez um Product Owner (PO).  
A qualidade provavelmente é testada pelos próprios desenvolvedores ou pelos clientes após o lançamento.

### Problemas da falta de clareza nas responsabilidades

- **Custo de Correção:** Bugs encontrados em produção custam até 100x mais do que na fase de design.
- **Baixa Produtividade:** Desenvolvedores perdem tempo corrigindo erros antigos.
- **Desgaste de Marca:** Pedidos duplicados geram prejuízo financeiro e perda de clientes.

### Responsabilidade Compartilhada

A qualidade deve ser responsabilidade de toda a equipe:

- Desenvolvedor → garante funcionamento (testes unitários)
- PO → garante requisitos corretos
- QA → garante experiência do usuário

Sem isso, o QA vira gargalo ou "culpado".

---

## 2. Papéis da Equipe

| Papel | Responsabilidade Principal | Relação com a Qualidade |
|------|--------------------------|-------------------------|
| Product Owner (PO) | Definir backlog | Garante requisitos claros |
| Desenvolvedor | Criar funcionalidades | Testes unitários + code review |
| QA | Planejar testes | Valida experiência do usuário |
| DevOps | Infraestrutura e deploy | Garante ambiente estável |

---

## 3. Práticas de QA Sugeridas

### Definição de Pronto (DoD)
Nenhuma funcionalidade é finalizada sem:
- Teste básico
- Revisão de código

### Testes Exploratórios
Equipe tenta "quebrar" o sistema antes do deploy.

### Gestão de Bugs
Usar:
- Jira
- Trello
- GitHub Issues

### Revisão de Requisitos
QA revisa tarefas antes do desenvolvimento.

---

## 4. Anúncios de Contratação

### Vaga 1: Analista de QA

**Sobre a vaga:**  
Garantir qualidade e confiabilidade da plataforma.

**Responsabilidades:**
- Criar planos de teste
- Executar testes
- Reportar bugs

**Requisitos:**
- Testes Web/Mobile
- Boa documentação

**Diferenciais:**
- Selenium / Cypress
- ISTQB

---

### Vaga 2: Desenvolvedor Fullstack

**Sobre a vaga:**  
Desenvolver com foco em qualidade e boas práticas.

**Responsabilidades:**
- Criar APIs e telas
- Testes unitários
- Code review

**Requisitos:**
- Node.js ou React
- Git

**Diferenciais:**
- Testes de integração
- Scrum / Kanban

---

## 5. Próximos Passos

1. Criar repositório: `local-eats-qa`
2. Criar arquivo: `aula-03-diagnostico-qa.md`
3. Subir no GitHub
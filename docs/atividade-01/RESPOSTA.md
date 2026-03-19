## 📌 Análise do Sistema

### 1. Qual é o propósito do sistema?

Conectar pessoas (moradores e turistas) a restaurantes locais através de um guia digital (site e app) para facilitar a busca por comida e fortalecer o comércio da cidade.

---

### 2. Quem são seus usuários?

- Moradores da cidade.  
- Turistas visitando a região.  
- Donos de restaurantes locais (que cadastram seus estabelecimentos).  

---

### 3. Quais problemas estão sendo enfrentados?

- Lentidão: O sistema trava quando muita gente acessa ao mesmo tempo.  
- Erros de busca: O app mostra resultados que o usuário não pediu.  
- Falhas visuais: Telas difíceis de entender e botões que não funcionam bem.  
- Instabilidade: O app fecha sozinho em alguns celulares e apaga avaliações.  
- Diferenças: O site funciona de um jeito e o aplicativo de outro.  

---

## 📊 Características de Qualidade Afetadas

### 1. Eficiência de Desempenho

**O que é:** A capacidade do software de responder rápido e lidar com muitos usuários.  

**Problema afetado:** O sistema fica lento em horários de pico.  

**Impacto:** O usuário desiste de usar o app porque ele demora a carregar.  

---

### 2. Usabilidade

**O que é:** A facilidade de aprender, usar e entender o sistema.  

**Problemas afetados:** Telas confusas, dificuldade para concluir ações simples e falta de padrão entre site e celular.  

**Impacto:** O usuário fica perdido e comete erros ao tentar usar a plataforma.  

---

### 3. Adequação Funcional

**O que é:** Se o sistema faz o que prometeu fazer de forma correta.  

**Problema afetado:** Buscas que retornam resultados incorretos.  

**Impacto:** O sistema perde sua utilidade principal (encontrar restaurantes).  

---

### 4. Compatibilidade

**O que é:** A capacidade de funcionar em diferentes aparelhos ou sistemas.  

**Problema afetado:** Falhas em determinados modelos de smartphone.  

**Impacto:** Pessoas com celulares de marcas específicas não conseguem usar o serviço.  

---

### 5. Confiabilidade

**O que é:** A capacidade do sistema de manter seu nível de desempenho e integridade dos dados.  

**Problema afetado:** Avaliações que desaparecem após a atualização da página.  

**Impacto:** O usuário perde a confiança nas informações que vê ou insere no app.  

---

## 🧠 Justificativa Técnica Geral

Por que esse problema afeta esse atributo de qualidade?  

Porque o software falha em cumprir requisitos técnicos básicos de desempenho, lógica de dados e interface, impedindo que o sistema funcione como deveria em diferentes condições e aparelhos.

---

## 📉 Impacto para o Usuário e Negócio

Qual o impacto para o usuário ou para o negócio?  

Gera frustração e abandono do app pelos usuários, resultando em perda de vendas para os comerciantes e destruição da reputação da plataforma antes mesmo do grande evento.

---

## 🧩 Tabela de Análise

| Problema Identificado | Atributo Afetado (ISO 25010) | Justificativa Técnica |
|----------------------|------------------------------|----------------------|
| Lentidão em horários de pico | Eficiência de Desempenho | O sistema não suporta acessos simultâneos, gerando desistência e perda de vendas. |
| Telas confusas e pouco intuitivas | Usabilidade | Interface mal projetada que aumenta o esforço do usuário e causa erros de navegação. |
| Buscas com resultados incorretos | Adequação Funcional | Falha na lógica do software que impede a realização da tarefa principal (achar comida). |
| Falhas em modelos de smartphone | Compatibilidade | Falta de adaptação técnica para diferentes aparelhos, excluindo parte dos clientes. |
| Dificuldade em ações simples | Usabilidade | Fluxos de uso ineficientes que geram frustração e abandono da plataforma. |
| Avaliações que desaparecem | Confiabilidade | Falha crítica na gravação de dados que destrói a credibilidade da plataforma. |
| Diferença entre Web e Mobile | Compatibilidade | A falta de padrão entre as versões confunde o usuário e exige retrabalho. |

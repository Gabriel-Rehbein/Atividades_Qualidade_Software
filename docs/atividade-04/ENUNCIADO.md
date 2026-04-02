# Centro Universitário Senac-RS
**ADS - Análise e Desenvolvimento de Sistemas / SPI - Sistemas para Internet**  
**Unidade Curricular:** Qualidade de Software  
**Prof.:** Luciano Zanuz  

# Atividade PBL – Aula 5
## Testes Funcionais vs Estruturais – LocalEats

## Contexto
Após definir uma estratégia inicial de testes para o sistema **LocalEats**, a equipe de Qualidade agora precisa evoluir sua abordagem.

O desafio não é mais apenas **o que testar**, mas sim:  
> “Como pensar os testes considerando diferentes perspectivas?”

O sistema continua apresentando problemas como:
- Resultados incorretos nas buscas
- Comportamentos inesperados
- Falhas específicas em algumas situações
- Inconsistências entre funcionalidades

A equipe precisa entender melhor como diferentes tipos de testes ajudam a encontrar diferentes tipos de problemas.

## Objetivo da Atividade
Compreender e aplicar, de forma conceitual, as diferenças entre:
- **Testes caixa-preta (funcionais)**
- **Testes caixa-branca (estruturais)**

> ⚠ **Importante:**  
> - Não usar técnicas específicas (ainda)  
> - Não escrever código  
> - Foco em raciocínio e compreensão  

## Tarefas
Elaborem um documento contendo:

### 1. Escolha da funcionalidade
Selecionem **1 funcionalidade** do sistema:
- Busca de restaurantes
- Login/cadastro
- Avaliação
- Favoritos
- Recomendações

👉 Descrevam:
- O que a funcionalidade faz
- O que o usuário espera dela

### 2. Testes Caixa-Preta (Visão do Usuário)
Pensando sem conhecer o código:

- Quais testes vocês fariam para verificar se a funcionalidade funciona corretamente?
- Quais tipos de erro poderiam ser encontrados?

👉 Descrever:
- Entradas possíveis
- Comportamentos esperados
- Situações de erro

### 3. Testes Caixa-Branca (Visão do Sistema)
Agora imaginem que vocês têm acesso ao código:

- Como essa funcionalidade poderia estar implementada?
- Quais decisões ou regras internas podem existir?

👉 Descrever:
- Possíveis estruturas lógicas (`if`, validações, regras)
- Situações que precisam ser testadas no código

### 4. Comparação entre as abordagens
Responder:

- Qual a principal diferença entre testar sem ver o código e com acesso ao código?
- Que tipo de problema cada abordagem ajuda a encontrar?

### 5. Reflexão no contexto do LocalEats
- Qual abordagem parece mais útil para os problemas atuais do sistema?
- Apenas uma abordagem seria suficiente?

👉 Justifiquem com base no cenário apresentado

## Entregável
- **Formato:** arquivo Markdown (`.md`)
- **Entrega:** repositório do grupo no GitHub  
  `/aula-05-testes-funcionais-estruturais.md`
- **Trabalho:** individual ou em grupo (até 4 integrantes)

## Exemplo
<https://github.com/lucianozanuz/pbl-qualidade-software-2026-1/blob/main/pbl/aula-05-testes-funcionais-estruturais.md>

## Avaliação (Rubrica – Unisenac-RS)

### D — Não atingiu as competências mínimas
- Não diferencia caixa-preta e caixa-branca
- Respostas genéricas ou desconectadas do sistema
- Não apresenta cenários de teste
- Não demonstra entendimento do problema

👉 Indica falta de compreensão básica

### C — Atingiu parcialmente as competências
- Identifica parcialmente as diferenças
- Propõe alguns testes, mas de forma superficial
- Explicações pouco claras ou incompletas
- Justificativas fracas

👉 Compreensão inicial, mas limitada

### B — Atingiu plenamente as competências
- Diferencia corretamente as abordagens
- Propõe testes coerentes com a funcionalidade
- Identifica possíveis falhas do sistema
- Apresenta comparação clara entre as abordagens
- Justifica suas decisões

👉 Bom domínio conceitual

### A — Atingiu as competências com excelência
- Demonstra entendimento claro e estruturado
- Propõe testes relevantes e bem pensados
- Conecta testes com problemas reais do sistema
- Explica com precisão as diferenças entre abordagens
- Apresenta reflexão crítica sobre uso das técnicas
- Justificativas consistentes e bem elaboradas

👉 Demonstra pensamento profissional de QA

## 💡 Dica final
Para obter conceito **A**, vocês devem:
- Pensar como usuário e como desenvolvedor
- Explicar o raciocínio, não apenas listar testes
- Conectar com os problemas reais do LocalEats
- Mostrar claramente a diferença entre as abordagens
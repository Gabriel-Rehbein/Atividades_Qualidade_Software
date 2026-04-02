
## Testes Funcionais vs Estruturais – LocalEats

---

## 1. Escolha da funcionalidade

### Funcionalidade escolhida: Busca de restaurantes

### O que a funcionalidade faz
Permite que o usuário pesquise restaurantes com base em nome, categoria (ex: pizza, japonês), localização ou filtros.

### O que o usuário espera
- Resultados corretos e relevantes
- Rapidez na busca
- Filtros funcionando corretamente
- Nenhum erro ou travamento

---

## 2. Testes Caixa-Preta (Visão do Usuário)

### Entradas possíveis
- Nome do restaurante (ex: "Pizza")
- Categoria (ex: "Japonesa")
- Campo vazio
- Caracteres especiais (ex: "@#%")
- Busca com letras maiúsculas/minúsculas

### Comportamentos esperados
- Retornar restaurantes relacionados ao termo digitado
- Não quebrar com entrada inválida
- Mostrar mensagem quando não houver resultados
- Aplicar filtros corretamente

### Situações de erro
- Resultados incorretos
- Nenhum resultado quando deveria ter
- Lentidão ou travamento
- Erro ao aplicar filtros
- Inconsistência entre resultados

---

## 3. Testes Caixa-Branca (Visão do Sistema)

### Possível implementação
- Uso de `if` para verificar se o campo está vazio
- Filtros por categoria e localização
- Busca no banco de dados usando query (SQL)
- Tratamento de strings (lowercase/uppercase)

### Estruturas lógicas possíveis
- `if (campo == vazio)`
- `if (categoria selecionada)`
- `if (resultado encontrado)`
- `else (nenhum resultado)`

### Situações que precisam ser testadas no código
- Validação de entrada (evitar erro ou SQL Injection)
- Tratamento de caracteres especiais
- Condições de filtro
- Retorno correto do banco de dados
- Performance da busca

---

## 4. Comparação entre as abordagens

### Diferença principal
- Caixa-preta: testa o sistema sem ver o código (visão do usuário)
- Caixa-branca: testa com acesso ao código (visão do desenvolvedor)

### Tipos de problemas encontrados

**Caixa-preta:**
- Erros de funcionamento
- Problemas de interface
- Resultados incorretos

**Caixa-branca:**
- Erros de lógica
- Falhas em condições (`if`)
- Problemas internos no código

---

## 5. Reflexão no contexto do LocalEats

### Qual abordagem é mais útil?
As duas são importantes, mas:
- Caixa-preta ajuda a identificar os problemas relatados pelos usuários
- Caixa-branca ajuda a entender a causa dos erros

### Apenas uma abordagem seria suficiente?
Não.

### Justificativa
O sistema apresenta:
- Resultados incorretos → detectado com caixa-preta
- Comportamentos inesperados → analisado com caixa-branca
- Inconsistências → precisam das duas abordagens

👉 Portanto, o uso combinado garante melhor qualidade e identificação completa dos problemas.

---

## ✅ Conclusão
Para garantir a qualidade do sistema LocalEats, é necessário utilizar tanto testes funcionais quanto estruturais, pois cada um cobre uma perspectiva diferente e essencial do sistema.
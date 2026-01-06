# 04 – Técnicas de Teste 🧠🧪

Técnicas de teste ajudam o QA a **criar testes eficientes**, mesmo quando o tempo é curto, os requisitos são limitados ou o sistema é complexo.

Elas orientam **como pensar os testes**, reduzindo esforço desnecessário e aumentando a chance de encontrar defeitos relevantes.

---

## 🎯 Objetivo deste módulo

- Entender o que são técnicas de teste
- Conhecer as principais técnicas de caixa preta e caixa branca
- Aprender quando aplicar cada técnica
- Melhorar a eficiência e a cobertura dos testes

---

## 🧩 O que são Técnicas de Teste

Técnicas de teste são métodos sistemáticos usados para:
- Definir condições de teste
- Criar casos de teste
- Priorizar cenários

📌 Elas ajudam o QA a testar melhor, não apenas testar mais.

---

## 🎭 Técnicas de Teste Caixa Preta

Nas técnicas de caixa preta, o QA **não precisa conhecer o código interno** do sistema.

O foco está:
- Entradas
- Saídas
- Regras de negócio
- Comportamento esperado

---

### 📦 Partição por Equivalência

Divide os dados de entrada em grupos (partições) onde o sistema deve se comportar da mesma forma.

Exemplo:
- Idade válida: 18 a 65
- Idade inválida: < 18 ou > 65

Testar um valor de cada partição costuma ser suficiente.

---

### 📏 Análise de Valor Limite

Foca nos limites das partições, onde erros são mais comuns.

Exemplo:
- Limite inferior: 18
- Limite superior: 65

Testes próximos aos limites aumentam a chance de encontrar defeitos.

---

### 📊 Tabela de Decisão

Usada quando existem múltiplas condições e regras de negócio.

Ajuda a:
- Visualizar combinações possíveis
- Evitar cenários esquecidos
- Criar testes mais completos

---

### 🔄 Transição de Estado

Valida o comportamento do sistema conforme ele muda de estado.

Exemplo:
- Pedido: criado → pago → enviado → entregue

Erros costumam ocorrer em transições inválidas.

---

## 🔍 Técnicas de Teste Caixa Branca

Nas técnicas de caixa branca, o QA conhece a **estrutura interna do código**.

O foco está:
- Fluxos de decisão
- Condições
- Caminhos lógicos

Normalmente aplicadas em testes unitários.

---

### 🧾 Cobertura de Instrução

Garante que todas as instruções do código sejam executadas ao menos uma vez.

📌 Não garante que todas as decisões foram testadas.

---

### 🔀 Cobertura de Decisão

Garante que todas as decisões (if/else, switch, etc.) sejam avaliadas como:
- Verdadeiras
- Falsas

Oferece maior confiança que apenas a cobertura de instrução.

---

## 🧠 Quando usar cada técnica

- Caixa preta: valida comportamento e regras de negócio
- Caixa branca: valida lógica e fluxo do código
- Projetos complexos: combinar técnicas
- Tempo curto: focar em risco e impacto

---

## 🚀 Próximo módulo

Após dominar as técnicas de teste, o próximo passo é entender **como avaliar a qualidade do software com base em modelos reconhecidos**.

👉 Continue para: **05-modelo-qualidade-iso-25010**

---

📌 *Boas técnicas de teste aumentam a chance de encontrar defeitos importantes.*

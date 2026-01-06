# 03 – Design de Testes 🧩🧪

Design de testes é a etapa onde o QA define **como os testes serão pensados, estruturados e organizados**, garantindo uma cobertura eficiente sem desperdício de esforço.

Mais do que escrever casos de teste, o design de testes ajuda o time a **testar melhor**, focando no que realmente importa.

---

## 🎯 Objetivo deste módulo

- Entender o que é design de testes
- Conhecer os diferentes níveis de teste
- Aprender como distribuir testes ao longo do sistema
- Compreender estratégias de teste modernas
- Ajudar o QA a tomar decisões mais assertivas

---

## 🧠 O que é Design de Testes

Design de testes é o processo de:
- Planejar testes
- Definir abordagens
- Escolher tipos de testes
- Determinar níveis de cobertura

Tudo isso considerando **risco, prioridade e contexto** do projeto.

---

## 🔺 Pirâmide de Testes

A pirâmide de testes ajuda a distribuir os testes em diferentes níveis:

- **Base:** Testes unitários (rápidos e baratos)
- **Meio:** Testes de integração
- **Topo:** Testes end-to-end (mais lentos e caros)

📌 Quanto mais testes na base, mais estável e confiável é o sistema.

---

## 🔗 Testes de Integração

Validam a comunicação entre componentes, serviços ou módulos.

São importantes para garantir que:
- Sistemas se comuniquem corretamente
- Contratos de API sejam respeitados
- Integrações externas funcionem como esperado

---

## 🌐 Testes End-to-End (E2E)

Simulam o fluxo completo do usuário no sistema.

Exemplos:
- Login
- Compra
- Cadastro

📌 Devem ser usados com cautela, pois são mais lentos e frágeis.

---

## 🧪 Adicionando Testes em Todos os Níveis

Um bom design de testes:
- Distribui testes entre unitário, integração e E2E
- Evita depender apenas de testes manuais
- Reduz retrabalho e flakiness

---

## 🔁 Testes de Regressão

Garantem que funcionalidades existentes continuem funcionando após mudanças.

Podem ser:
- Manuais
- Automatizados

📌 Essenciais em sistemas com evolução constante.

---

## ✅ Testes Funcionais

Validam se o sistema:
- Faz o que foi especificado
- Atende aos requisitos funcionais

Foco no comportamento esperado.

---

## ⚙️ Testes Não Funcionais

Avaliam atributos de qualidade como:
- Desempenho
- Segurança
- Usabilidade
- Confiabilidade

📌 Não testam *o que* o sistema faz, mas *como* ele faz.

---

## 🚦 Smoke Tests

Conjunto mínimo de testes para verificar se o sistema:
- Está estável
- Pode ser testado

Executados geralmente após deploys ou builds.

---

## 🧠 Estratégia de Testes

Uma boa estratégia de testes considera:
- Riscos do projeto
- Tempo disponível
- Ambiente
- Tipo de sistema
- Maturidade do time

Design de testes é sempre **contextual**.

---

## 🚀 Próximo módulo

Com o design de testes definido, o próximo passo é aprender **como criar testes eficientes utilizando técnicas específicas**.

👉 Continue para: **04-tecnicas-de-teste**

---

📌 *Testar bem é mais importante do que testar muito.*

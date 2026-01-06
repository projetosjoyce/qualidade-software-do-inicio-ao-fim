# 06 – Arquitetura de Software 🏗️🧪

Entender arquitetura de software permite que o QA **antecipe riscos**, **crie melhores estratégias de teste** e **se comunique melhor com o time técnico**.

O QA não precisa projetar arquiteturas, mas precisa entender **como elas impactam a qualidade do sistema**.

---

## 🎯 Objetivo deste módulo

- Compreender o conceito de arquitetura de software
- Entender como a arquitetura impacta os testes
- Conhecer arquiteturas comuns em sistemas web e APIs
- Identificar pontos de atenção para QA em diferentes arquiteturas

---

## 🧱 O que é Arquitetura de Software

Arquitetura de software define:
- Estrutura do sistema
- Componentes principais
- Comunicação entre componentes
- Decisões técnicas importantes

Ela influencia diretamente:
- Performance
- Segurança
- Escalabilidade
- Testabilidade

---

## 🧠 Por que QA deve entender Arquitetura

Quando o QA entende a arquitetura, ele consegue:
- Identificar riscos mais cedo
- Planejar testes mais eficazes
- Fazer perguntas melhores
- Evitar surpresas em produção

📌 Arquitetura mal definida gera testes frágeis e sistemas difíceis de manter.

---

## 🌐 Arquitetura Web

Arquitetura comum em aplicações web tradicionais.

### Componentes típicos:
- Front-end (interface do usuário)
- Back-end (regras de negócio)
- Banco de dados

### Pontos de atenção para QA:
- Comunicação entre front e back
- Validação de dados
- Performance de páginas
- Compatibilidade entre navegadores

---

## 🔌 Arquitetura de APIs

Arquitetura baseada em serviços que se comunicam por meio de APIs.

### Características:
- Comunicação via HTTP
- Uso de JSON ou XML
- Independência entre sistemas

### Pontos de atenção para QA:
- Contratos de API
- Status codes
- Validação de payloads
- Autenticação e autorização
- Versionamento

---

## 🧩 Arquiteturas Monolítica x Microsserviços

### Monolítica
- Sistema único
- Mais simples de iniciar
- Mais difícil de escalar

### Microsserviços
- Serviços independentes
- Maior complexidade
- Mais pontos de falha

📌 QA precisa adaptar sua estratégia conforme a arquitetura.

---

## 🔁 Impacto da Arquitetura nos Testes

A arquitetura influencia:
- Tipos de testes necessários
- Estratégia de automação
- Ambientes de teste
- Análise de falhas

Exemplo:
- Microsserviços exigem mais testes de integração
- Monólitos exigem atenção à regressão

---

## 🧠 QA como agente de qualidade técnica

Mesmo sem escrever código, o QA pode:
- Questionar decisões técnicas
- Alertar riscos arquiteturais
- Contribuir para sistemas mais testáveis

Qualidade técnica também é responsabilidade do QA.

---

## 🚀 Próximo módulo

Com o entendimento da arquitetura, o próximo passo é aprender **como identificar e gerenciar riscos no desenvolvimento de software**.

👉 Continue para: **07-riscos**

---

📌 *Quanto melhor o QA entende a arquitetura, melhor ele testa.*

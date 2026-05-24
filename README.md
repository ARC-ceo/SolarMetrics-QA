![Logo](banner.jpg)

# QA Test Case Repository

Este repositório tem como objetivo centralizar todos os artefatos relacionados ao processo de Qualidade (QA) e testes da aplicação.

Aqui estarão disponíveis os documentos necessários para execução, planejamento e evidências dos testes realizados durante o desenvolvimento do projeto.

---

# Conteúdo do Repositório

## 📄 Plano de Testes

O arquivo PDF disponível neste repositório contém o plano de testes completo, incluindo:

- Escopo dos testes
- Objetivos
- Estratégia de testes
- Critérios de entrada e saída
- Casos de teste
- Massa de dados
- Resultados esperados
- Evidências de execução
- Critérios de aprovação

---

## 🧪 Collection Insomnia

Também está disponível uma Collection do Insomnia contendo todas as requisições necessárias para execução dos testes da API.

A collection permite:

- Executar os cenários de teste
- Validar regras de negócio
- Verificar respostas da API
- Reproduzir os testes documentados no plano de testes

### Pré-requisito

Antes de iniciar a execução dos testes, é necessário realizar a criação de um cliente através do endpoint correspondente.

Os dados gerados serão utilizados durante diversos cenários descritos no plano de testes.

---

# Ferramentas Utilizadas

- Insomnia
- Azure Boards
- Azure Test Plans
- Swagger / OpenAPI
- GitHub

---

# Gestão dos Testes

## Azure Boards

Link do Board:

> 🔗 [SolarMetrics Azure](https://dev.azure.com/Challenge-SolarMetrics/SolarMetrics)

---

# Estrutura do Repositório

```text
📦 SolarMetrics-QA
 ┣ 📄 Plano_de_Testes_SolarMetrics.pdf
 ┣ 📄 CTs - Collection Insomnia.yaml
 ┗ 📄 README.md

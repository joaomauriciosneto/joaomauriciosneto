# 📊 Fluxograma do Processo de Compras no SAP MM

Este repositório apresenta um **fluxograma funcional** que representa o fluxo **AS-IS** (como é atualmente) do processo de compras no módulo **SAP MM (Materials Management)**. O objetivo é demonstrar o entendimento do ciclo operacional padrão do SAP, com foco nas principais transações do sistema.

---

## 🧭 Visão Geral do Processo

O fluxo simula uma cadeia completa de operações realizadas no SAP para execução de uma compra de materiais — desde a criação dos dados mestres até o lançamento da fatura. Este modelo serve como base para análise, entendimento ou até modelagem futura do processo **TO-BE** (como poderá ser).

> ⚠️ **Nota:** Este modelo segue a estrutura de um **fluxograma tradicional**, mas também pode ser adaptado para **notação BPMN (Business Process Model and Notation)**, caso se deseje uma modelagem mais formal e orientada a processos.

---

## 🛠️ Transações SAP Utilizadas

| Transação | Finalidade                          |
|-----------|--------------------------------------|
| **XK01**  | Criar Fornecedor                     |
| **MM01**  | Criar Material                       |
| **ME51N** | Criar Requisição de Compras          |
| **ME21N** | Criar Pedido de Compras              |
| **MIGO**  | Entrada de Mercadoria                |
| **MIRO**  | Lançamento da Fatura do Fornecedor   |

---

## 📌 Estrutura do Fluxograma (AS-IS)

O fluxograma descreve a sequência real das operações no SAP MM em um processo típico de compras:

- **Início** do processo com a criação dos dados mestres.
- **Requisição e formalização** da compra.
- **Recebimento físico** da mercadoria.
- **Registro da fatura** do fornecedor.
- **Fim** do processo após a contabilização.

### 🔄 Possível expansão futura:
Este fluxo pode ser utilizado como base para construção de um modelo **TO-BE**, com otimizações como:
- Aprovação automática de requisições (Workflow)
- Integração com gestão de contratos (ME31K)
- Automação de faturas via EDI

---

## 🧩 Notação e Legenda

| Símbolo        | Tipo de Ação                          | Cor         |
|----------------|----------------------------------------|--------------|
| ⭕ Elipse       | Início / Fim                           | Cinza claro  |
| 🟦 Retângulo    | Etapa de Processo / Transação SAP      | Azul médio   |
| 🟩 Paralelogramo| Entrada/Saída de dados (documentos)    | Verde claro  |
| 🔶 Losango      | Decisão (não utilizado neste modelo)   | Laranja      |

---

## 📄 Arquivo Incluso

- [`fluxo_sap_mm.pdf`](./fluxo_sap_mm.pdf) – Documento visual do modelo AS-IS do processo de compras no SAP MM.

---

## 🎯 Objetivo do Repositório

Este repositório é parte do meu portfólio como profissional em formação na área de **Consultoria SAP MM**, com foco em processos, documentação e mapeamento funcional.

---

## 📬 Contato

**João Maurício**  
📧 joaomauricio@email.com  
🔗 [LinkedIn](https://www.linkedin.com/in/joaomauriciosneto)  

---

> *Este projeto é de caráter educacional e não reflete dados de ambiente produtivo SAP real.*

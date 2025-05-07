# 🧾 Cadastro de Fornecedores no SAP MM – Transação XK01

Este repositório documenta o processo de **cadastro de fornecedores no SAP MM** utilizando a transação **XK01**. A finalidade é apresentar, de forma prática e objetiva, o fluxo funcional necessário para criar registros de fornecedor em ambientes SAP.

---

## 📌 Objetivo

Demonstrar o processo de **criação de dados mestres de fornecedores**, etapa essencial para a execução de processos de compras, recebimentos e pagamentos no módulo **SAP MM (Materials Management)**.

---

## 🛠️ Transação Utilizada

| Código | Função                          |
|--------|----------------------------------|
| XK01   | Criar Fornecedor (Dados Mestres) |

---

## 🧭 Etapas do Processo

1. **Acesso à transação XK01**
2. **Preenchimento dos dados principais:**
   - Código da empresa (`Company Code`)
   - Código do centro (`Purchasing Organization`)
   - Grupo de contas (`Account Group`)
3. **Inserção dos dados gerais do fornecedor:**
   - Nome, Endereço, País, Idioma
4. **Dados da empresa:**
   - Condições de pagamento
   - Informações bancárias
   - Grupo de ordenação
5. **Dados de compras:**
   - Grupo de compras
   - Pedido automático (se aplicável)
   - Prazo de entrega, termos de frete

---

## 🖼️ Arquivos Inclusos

- `tela_xk01_exemplo.png` – Screenshot real do formulário de cadastro
- `README.md` – Este arquivo de explicação

---

## ⚙️ Requisitos do Sistema

- SAP GUI instalado
- Permissão de acesso à transação **XK01**
- Código de empresa e organização de compras previamente criados

---

## 📌 Observações

- O campo **"Grupo de contas"** define se o fornecedor será de materiais, serviços ou outros.
- O número do fornecedor pode ser gerado automaticamente, dependendo da configuração da conta.
- Caso a tela não esteja editável ou apresente erro de centro/código, verifique se a **organização de compras** está vinculada corretamente ao fornecedor.

---

## 🎯 Propósito do Projeto

Este projeto faz parte do meu portfólio de aprendizado e prática como **futuro consultor SAP MM**, documentando etapas fundamentais do processo de compras e gestão de fornecedores.

---

## 📬 Contato

**João Maurício**  
📧 joaomauricio@email.com  
🔗 [LinkedIn](https://www.linkedin.com/in/joaomauriciosneto)

---

> *Este repositório é de uso educacional e não utiliza dados reais ou confidenciais de empresas.*



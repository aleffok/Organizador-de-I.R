# 📑 Organizador de Declaração de Imposto de Renda (IRPF)

Uma ferramenta desenvolvida em **Microsoft Excel** projetada para centralizar o controle de despesas dedutíveis, rendimentos e evolução patrimonial ao longo do ano, simplificando o processo de declaração do Imposto de Renda Pessoa Física (IRPF) e prevenindo retenções na malha fina.

O projeto une **boas práticas de gestão fiscal**, automação de consolidação e uma interface responsiva focada em **Spreadsheet UX**.

---

## 🚀 Funcionalidades Principais

* **Painel de Resumo Fiscal (Dashboard):** KPIs no topo da planilha que consolidam automaticamente o total de despesas com saúde, educação e rendimentos tributáveis.
* **Controle de Despesas Dedutíveis:** Tabela organizada para lançamento de comprovantes médicos, educacionais e previdenciários, incluindo CPF/CNPJ dos prestadores e histórico de pagamentos.
* **Validação & Status de Recibos:** Lista suspensa integrada com Formatação Condicional inteligente que destaca visualmente pendências (`Pendente` em vermelho / `Arquivado` em verde).
* **Aba de Rendimentos & Evolução Patrimonial:** Seção dedicada ao acompanhamento da variação de bens e direitos entre 31/12 do ano anterior e 31/12 do ano atual, além da separação de rendimentos tributáveis e isentos.

---

## 🛠️ Tecnologias e Recursos Aplicados

* **Fórmulas de Consolidação Dinâmica:** Aplicação extensiva da função `SOMASE` (`SUMIF`) para sumarizar lançamentos por categoria e status direto no painel superior.
* **Validação de Dados:** Uso de listas suspensas para padronização de categorias e status, evitando erros manuais de digitação.
* **Formatação Condicional Responsiva:** Destacamento automático de status de recibos e formatação de células.
* **Arquitetura Multi-Aba:** Separação lógica entre consolidação executiva e dados de lançamento (Despesas vs. Rendimentos/Bens).

---

## ⚙️ Como Utilizar

1. Baixe o arquivo `Organizador_IRPF.xlsx` presente neste repositório.
2. Abra no Microsoft Excel ou Google Planilhas.
3. Cadastre seus rendimentos e bens na aba de **Rendimentos e Bens**.
4. Lance seus recibos médicos e educacionais ao longo do ano na aba **Despesas Dedutíveis**.
5. Acompanhe a consolidação em tempo real no **Painel de Resumo**.

---

Projeto prático desenvolvido para solucionar a organização fiscal pessoal diária, aplicando conceitos avançados de estruturação de dados, fórmulas condicionais e design de planilhas operacionais no Excel.

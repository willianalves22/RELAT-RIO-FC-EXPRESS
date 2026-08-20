# 📊 Executive BI Analytics Dashboard

Uma aplicação web completa de Business Intelligence (BI) executada diretamente no navegador, projetada para analisar, visualizar e exportar relatórios a partir de planilhas Excel (`.xlsx`, `.xls`) e arquivos `.CSV`.

---

## 🚀 Funcionalidades

- **Múltiplos Formatos:** Leitura e interpretação automática de arquivos `.xlsx`, `.xls` e `.CSV`.
- **Análise Inteligente de Estrutura:** Identificação automática de cabeçalhos reais, métricas numéricas, datas e colunas categóricas (com remoção automática de artefatos como `__EMPTY`).
- **Dashboard Interativo:**
  - **KPIs Dinâmicos:** Cálculo automático de totais, médias e máximos.
  - **Análise Temporal:** Gráfico de evolução com agrupamento por **Dia, Mês, Trimestre ou Ano**.
  - **Comparativo de Períodos:** Análise de variação percentual e crescimento/queda.
  - **Rankings Personalizáveis:** Top 5 e Top 10 por dimensão categórica.
  - **Tabela Dinâmica:** Resumos agrupados com soma e média.
- **Tabela de Dados Reais:** Visualização detalhada com busca global, ordenação e paginação.
- **Diagnóstico da Estrutura:** Exibição do resumo de linhas válidas, colunas e métricas detectadas.
- **Exportação:** Suporte para exportação dos dados filtrados para **Excel** e relatórios em **PDF**.
- **Tema Escuro / Claro:** Alternância de tema com persistência de preferência via `localStorage`.
- **Zero Instalação:** Funciona como uma aplicação *single-file* (um único arquivo HTML) executado diretamente no navegador.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído sem o uso de frameworks pesados (como React, Vue ou Angular), utilizando apenas tecnologias nativas e bibliotecas via CDN:

- **HTML5 & JavaScript Vanilla**
- **[Tailwind CSS](https://tailwindcss.com/):** Estilização moderna e responsiva.
- **[SheetJS / XLSX](https://sheetjs.com/):** Leitura e manipulação de arquivos Excel.
- **[Chart.js](https://www.chartjs.org/):** Renderização de gráficos temporais.
- **[jsPDF](https://github.com/parallax/jsPDF) & AutoTable:** Geração e exportação de relatórios em PDF.
- **[FontAwesome](https://fontawesome.com/):** Ícones da interface.

---

## 📂 Como Executar o Projeto

Como a aplicação é contida em um único arquivo HTML, **não é necessário instalar o Node.js nem rodar comandos de build**.

1. **Clone este repositório:**
   ```bash

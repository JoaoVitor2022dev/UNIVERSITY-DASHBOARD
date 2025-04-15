# 📊 Projeto Power BI - Universidade

Este repositório contém o desenvolvimento de um relatório interativo em Power BI para análise de dados universitários. O objetivo é apresentar insights relevantes por meio de uma estrutura bem definida, seguindo boas práticas de modelagem e visualização de dados.

---

## 🛣️ Roadmap do Projeto

### 1. 📥 Extração de Dados

- Importação dos dados utilizando **Power Query**.

---

### 2. 🔄 Transformação de Dados (Power Query)

- Ajuste dos tipos de dados (ex: texto, número, data).
- Criação da dimensão `Tabela_Curso`:
  - Referência da coluna `Curso`
  - Remoção de duplicatas
  - Exclusão de colunas desnecessárias
- Criação de outras **dimensões** necessárias.
- Estruturação do modelo no formato **Fato-Dimensão**.

---

### 3. 🔗 Modelagem de Dados

- Análise das tabelas e suas relações.
- Criação e validação de relacionamentos entre **fatos** e **dimensões**.

---

### 4. 🧱 Construção do Relatório

#### 4.1 🎨 Layout e Design

- Inserção de imagens de fundo por área temática:
  - Aluno, Campus, Financeiro, etc.
- Aplicação de um visual limpo e padronizado.

#### 4.2 🧮 Medidas (DAX)

- Criação de medidas personalizadas para análise:
  - Exemplo: `FAT_INADIMPLENTE = SOMASE(Inadimplente)`

#### 4.3 📊 Visualizações

- Gráfico de barras: **Inadimplência por curso**
  - **Eixo Y**: Cursos  
  - **Eixo X**: FAT_INADIMPLENTE
- Estilo clean e focado na legibilidade.

---

### 5. 🔍 Revisão e Ajustes Finais

- Otimização da performance do relatório.
- Ajustes de filtros, interações e layout.

---

### 6. 🚀 Análises Avançadas e Recursos Interativos

- Conversão da coluna **Idade** para tipo numérico.
- Adição de visualizações avançadas:
  - Matriz com percentuais
  - Gráficos de colunas agrupadas
  - Gráficos de dispersão (pontos)
- Criação de **medidas e colunas calculadas** com fórmulas DAX otimizadas.
- Organização de elementos em **pastas temáticas** (ex: `Medidas`, `Acadêmico`, `Financeiro`).
- Implementação de **botões de navegação** entre páginas do relatório.

---

### 7. 🧭 Navegação e Indicadores Dinâmicos

- Construção e customização dos **botões de transição entre páginas**.
- Uso de segmentações específicas para cada tela do relatório.
- Criação de **indicadores visuais (KPIs)** para destacar métricas relevantes.


### 8. 🧭 Navegação e Indicadores Dinâmicos

- **Criação de Variáveis:**  
  Definição de variáveis que facilitam a navegação entre páginas e a personalização dos indicadores.

- **Uso de Variáveis Alternativas:**  
  Aplicação de diferentes variáveis de acordo com o contexto ou necessidade da análise.

- **Concatenação de Variáveis:**  
  Combinação de variáveis para gerar títulos, filtros ou visualizações dinâmicas de forma automatizada.

---

## 📁 Estrutura do Projeto

```plaintext
📊 PowerBI-Universidade
├── README.md
├── Relatorio.pbix
├── assets/
│   └── imagens/
├── medidas/
│   └── DAX_medidas.txt
└── dados/
    └── base_universidade.xlsx

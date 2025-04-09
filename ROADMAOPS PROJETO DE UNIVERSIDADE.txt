# 📊 Roadmap do Projeto de Power BI - Universidade

Este roadmap fornece uma visão clara das etapas do projeto, garantindo uma estrutura bem definida para a criação do relatório no Power BI em um contexto universitário.

---

## 1. 📥 Extração de Dados

- Extrair os dados da base utilizando **Power Query**.

---

## 2. 🔄 Transformação de Dados (Power Query)

- Ajustar os tipos de dados das colunas para o formato adequado  
  *(ex: converter para texto, número, data, etc.)*.

- Criar uma **referência para a coluna Curso** e gerar uma dimensão separada (`Tabela_Curso`):
  - Remover duplicatas
  - Excluir colunas desnecessárias

- Criar todas as referências de colunas para a estrutura **Fato-Dimensão**.

---

## 3. 🔗 Modelagem de Dados

- Analisar como as tabelas estão relacionadas.
- Criar e validar os relacionamentos entre **fatos** e **dimensões**.

---

## 4. 🧱 Construção do Relatório (Exibição)

### 4.1 🎨 Layout e Design

- Inserir imagens de fundo para diferentes áreas do relatório  
  *(Aluno, Campus, Financeiro, etc.)*.
- Aplicar estilos visuais consistentes ao relatório.

### 4.2 🧮 Criação de Medidas (DAX)

- Criar medidas para análise financeira:  
  `FAT_INADIMPLENTE = SOMASE(Inadimplente)`

### 4.3 📊 Construção de Gráficos

- Gráfico de barras para análise de **inadimplência por curso**:
  - **Eixo Y**: Cursos  
  - **Eixo X**: FAT_INADIMPLENTE

- Aplicar um estilo visual **clean** aos gráficos para melhor legibilidade e apresentação.

---

## 5. 🔍 Revisão e Ajustes Finais

- Revisar a exibição e a performance do relatório.
- Ajustar filtros, interações e layout conforme necessário.

---

## 6. 🚀 Análises Avançadas e Recursos Interativos

- Corrigir o tipo da coluna **Idade** (de texto para número).

- Criar gráficos adicionais:
  - Matriz com exibição percentual
  - Colunas agrupadas para comparações visuais
  - Gráficos de pontos para análise exploratória

- Criar **medidas e colunas calculadas** usando fórmulas DAX otimizadas.

- Organizar os elementos (gráficos, medidas, filtros) em **pastas apropriadas** (ex: `Medidas`, `Acadêmico`, `Financeiro`).

- Criar **botão de troca de tela** para navegação entre diferentes áreas do relatório.

---


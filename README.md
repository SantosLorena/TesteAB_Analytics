
# Análise de Teste A/B — Projeto de Segmentação para Cupom de Desconto

Este projeto realiza uma análise de Teste A/B com foco em avaliar os **impactos de cupons de desconto** sobre o comportamento dos usuários, como volume de pedidos e ticket médio, e propõe **possíveis melhorias na segmentação de clientes**. A análise busca entender se a aplicação de cupons foi efetiva e como estratégias futuras podem ser otimizadas com base em dados reais.

## Arquivo principal

- **`Analise Teste AB Cupom de Desconto - Lorena Diana Santos`**  
  Este notebook contém todo o processo de análise estatística, tratamento de dados, aplicação de testes de significância (t-test e Mann-Whitney), além de visualizações e sugestões de segmentação baseada em comportamento dos clientes.

---

## Como utilizar o projeto

1. **Faça o download do notebook:**
   - Baixe o arquivo `Analise Teste AB Cupom de Desconto - Lorena Diana Santos` deste repositório.

2. **Importe para o Databricks:**
   - Acesse seu workspace no Databricks.
   - Clique em "Import" e envie o notebook `.ipynb`.

3. **Permissões necessárias:**
   - Permissão para **criar tabelas** no cluster Databricks.
   - Permissão para **importar arquivos para o DBFS (Databricks File System)**, caso utilize arquivos auxiliares de dados.

4. **Execute o notebook:**
   - Certifique-se de que o cluster esteja ativo.
   - Execute célula por célula conforme a ordem lógica do notebook.
   - Os comentários guiam a interpretação dos resultados e os insights extraídos.

---

## Tecnologias e bibliotecas utilizadas

- PySpark (Databricks)
- SQL (Spark SQL)
- `pandas`, `matplotlib`, `seaborn`
- `scipy.stats` — testes estatísticos (t-test, Mann-Whitney)
- `sklearn.cluster` — agrupamento de clientes com KMeans (quando aplicável)

---

## Objetivos da análise

- Medir o impacto de cupons no comportamento de compra
- Calcular ROI estimado da campanha
- Avaliar crescimento diário por grupo (controle vs. target)
- Sugerir segmentações baseadas em métricas como:
  - Quantidade de pedidos
  - Ticket médio
  - Plataforma utilizada
  - Região de entrega

---

## Autoria

Este notebook foi desenvolvido por **Lorena Diana Santos** como parte de um estudo analítico voltado para performance de campanhas promocionais e segmentação estratégica de clientes.

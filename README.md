# Dashboard Comercial - Performance de Vendas

Este projeto apresenta um dashboard para análise da performance de vendas, com foco em influenciadores, segmentação, performance por região e outros insights relevantes.

## Descrição

O dashboard oferece uma visão abrangente das vendas, permitindo identificar tendências, gargalos e oportunidades de melhoria.

## Fontes de Dados

*   Dados de vendas extraídos do arquivo vendas.csvsistem

## Páginas do Dashboard

O dashboard é composto por 5 páginas:

*   **Página 1: Índice:** Visão geral da performance com links direto para narrativa inteligente, influenciadores de vendas, faixas de vendas e performance por região.
*   **Página 2: Análise por Segmento e Fabricante:** Detalhamento das vendas por segmento, fabricante e categoria, com narrativa inteligente.
*   **Página 3: Influenciadores e Média:** Análise aprofundada dos principais influenciadores de vendas, principais segmentos e média de valor de venda.
*   **Página 4: Vendas por Categoria e Loja:** Matriz mostrando o desempenho das vendas por categoria em cada loja.
*   **Página 5: Performance por Região:** Análise por meio de mapa da performance dos vendedores, com filtro por região.

![Indice](https://github.com/user-attachments/assets/c49bc286-2f96-44c9-93f9-e9eed4f43297)
![pag 2](https://github.com/user-attachments/assets/8ab68ff3-de08-4381-ae1e-93dcbb77a51d)
![pag 3](https://github.com/user-attachments/assets/567c98e7-d3cb-4950-9538-2e8b36e2a5eb)
![pag 4](https://github.com/user-attachments/assets/667d0e65-3e3b-49a7-bfae-1fe3439fe3c7)
![pag 5](https://github.com/user-attachments/assets/60d06320-6352-4442-b5ef-6684f4911e97)


## Métricas e Cálculos (Exemplos)

*   `Total de Vendas = SUM(Vendas[Valor])`
*   `Média de Vendas = AVERAGE(Vendas[Valor])`
*   `Vendas por Categoria = CALCULATE([Total de Vendas], VALUES(Produtos[Categoria]))`
// Adicione outras medidas relevantes.

## Como Utilizar

1.  Clone este repositório: `git clone <URL do repositório>`.
   
## Arquivo .pbix

O arquivo `Dashboard Comercial - Performance de Vendas.pbix` contém o projeto completo.

## Como visualizar

Para visualizar interativamente, é necessário o Power BI Desktop. Para visualização online, use o Power BI Service https://app.powerbi.com/groups/me/reports/5e0e108f-162b-46cf-8e37-f6dbf1c6f225?ctid=e5a2d57f-82e3-43da-af1c-1a2cc1b42330&pbi_source=linkShare&bookmarkGuid=275d0021-2233-4361-bccc-7ee7fe590cbb.

## Contato

Auriane F Sousa - aurianef8@gmail.com

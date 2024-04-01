# As 10 Regras Essenciais de Modelagem Dimensional para Data Warehouse
![data](https://github.com/CarlosJuncher03/DataWarehouse/assets/145303814/bd05e1bb-5b07-43e3-bfde-5c74a8dd3f9a)
Entender as regras de modelagem dimensional é crucial para quem deseja obter sucesso na concepção e implementação de um Data Warehouse eficaz. Apresentamos um guia simplificado das práticas recomendadas, originadas pelo Kimball Group, com exemplos práticos para cada regra.

## Resumo das Regras e Exemplos

### 1. Carregar Dados Atômicos Detalhados
Dados granulares permitem análises profundas. 

**Exemplo:** Detalhar vendas por transação individual.

### 2. Modelar em Torno de Processos de Negócios
O esquema deve refletir eventos do mundo real. 

**Exemplo:** Um modelo centrado no processo de pedidos.

### 3. Associar Tabelas Fato a Dimensões de Data
Cada evento deve ser mapeado no tempo. 

**Exemplo:** Associar cada venda a uma data específica.

### 4. Manter a Granularidade Consistente na Tabela Fato
Todos os registros devem estar no mesmo nível de detalhe. 

**Exemplo:** Evitar a mistura de dados diários com mensais na mesma tabela.

### 5. Resolver Relacionamentos Muitos-para-Muitos
Utilizar tabelas de junção para cenários complexos. 

**Exemplo:** Produtos vendidos em múltiplas lojas.

### 6. Resolver Relacionamentos Muitos-Para-Um em Dimensões
Relacionamentos hierárquicos devem ser simplificados. 

**Exemplo:** Agrupar categorias de produtos em uma tabela de dimensão.

### 7. Armazenar Rótulos de Relatórios e Valores de Domínio em Dimensões
Informações descritivas devem estar nas dimensões. 

**Exemplo:** Descrições de produtos armazenadas nas dimensões, não nas tabelas fato.

### 8. Usar Chaves Substitutas nas Tabelas de Dimensão
Mantenha a consistência e facilite mudanças futuras. 

**Exemplo:** Utilizar um ID de cliente como chave substituta.

### 9. Criar Dimensões Conformadas para Integração de Dados
Garantir a uniformidade nos relatórios. 

**Exemplo:** Usar uma dimensão de cliente única para todas as análises.

### 10. Equilibrar Requisitos e Realidades
Ajustar os modelos às necessidades dos negócios. 

**Exemplo:** Colaborar com stakeholders para criar modelos úteis.

### Conclusão 

Este resumo oferece uma visão geral das práticas de modelagem dimensional essenciais. Para mais informações e exemplos detalhados, visite o [site do Kimball Group](https://www.kimballgroup.com/2009/05/the-10-essential-rules-of-dimensional-modeling/).

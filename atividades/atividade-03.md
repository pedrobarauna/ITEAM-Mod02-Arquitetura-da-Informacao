# 🛠️ Atividade 03 — Prática: Aplicando Conceitos de Arquitetura da Informação

Esta atividade é dividida em duas etapas: a análise crítica de um sistema de busca existente e o design de uma solução de navegação para um e-commerce.

---

## Parte 1: Análise Crítica (Sistema de Busca)

**Portal Escolhido:** G1 (Portal de Notícias da Globo)
**Objetivo:** Analisar a eficiência do sistema de busca do portal com base em três critérios fundamentais de usabilidade.

### 1. Relevância dos Resultados
*   **Análise:** O algoritmo de busca do G1 apresenta alta precisão e relevância. Ao buscar por um termo específico (ex: nomes de figuras públicas ou eventos), o sistema prioriza as notícias mais recentes e factuais no topo da lista. O sistema não polui os resultados com links patrocinados excessivos disfarçados de conteúdo, garantindo que o usuário encontre rapidamente o núcleo da informação desejada.

### 2. Filtros Disponíveis
*   **Análise:** O G1 possui uma excelente aplicação de filtros facetados após a pesquisa. O usuário não fica preso a uma lista estática; ele possui o controle para refinar os dados através de:
    *   **Formato de Mídia:** Notícias, Vídeos, Blogs, Fotos.
    *   **Filtro Temporal:** Em qualquer data, Última hora, Últimas 24 horas, Última semana, Último mês, ou um *Período Personalizado* (calendário).
    *   **Ordenação:** Mais Recentes vs. Mais Relevantes.
*   **Impacto:** Reduz drasticamente a carga cognitiva e o tempo de busca, permitindo que o usuário cruze o tipo de arquivo com a data exata do acontecimento.

### 3. Autocompletar (Autocomplete / Sugestões)
*   **Análise:** Ao começar a digitar no campo de busca (`input`), o sistema oferece sugestões em tempo real baseadas em *Trending Topics* (assuntos em alta no momento) e em correspondência exata de palavras. 
*   **Impacto:** Isso previne erros de digitação (*typos*) e acelera a jornada do usuário, cumprindo a heurística de "Reconhecimento em vez de memorização".

---

## Parte 2: Design de Solução (E-commerce)

**Cenário:** Design de Arquitetura da Informação para um E-commerce de Grande Porte no segmento de **Tecnologia e Informática**.

### 1. Fluxo de Navegação Lógico (User Flow)
O fluxo abaixo descreve o caminho ideal de um usuário que entra na loja em busca de um componente específico (ex: uma Placa de Vídeo) até a conversão.

`Home` ➔ `Menu Global (Categorias)` ➔ `Hardware` ➔ `Placas de Vídeo (Listing Page)` ➔ `Uso de Filtros Facetados` ➔ `Página de Detalhe do Produto (PDP)` ➔ `Adicionar ao Carrinho` ➔ `Checkout`

**Estrutura do Menu Global (Exemplo de Categorização Árvore):**
*   Departamentos
    *   Hardware
        *   Processadores
        *   Placas de Vídeo
        *   Placas-Mãe
    *   Periféricos
        *   Mouses
        *   Teclados
    *   Monitores
    *   Smartphones

### 2. Definição de Filtros Facetados
Para um e-commerce de grande porte, especialmente no nicho de tecnologia onde as especificações técnicas são o fator decisivo de compra, os filtros facetados devem permitir múltiplas seleções simultâneas. 

Na página de listagem de produtos (*Product Listing Page*), a barra lateral esquerda (ou um botão de *Filtros* expansível no Mobile) deve conter:

*   **Disponibilidade:**
    *   [ ] Apenas produtos em estoque
    *   [ ] Incluir produtos sob encomenda
*   **Marca (Fabricante):**
    *   [ ] Asus (45)
    *   [ ] Gigabyte (32)
    *   [ ] MSI (18)
*   **Faixa de Preço:**
    *   Slider duplo de seleção (ex: R$ 1.000,00 ──●──────●── R$ 5.000,00)
*   **Especificação Técnica Primária (Ex: para Placas de Vídeo):**
    *   [ ] 8 GB VRAM
    *   [ ] 12 GB VRAM
    *   [ ] 16 GB VRAM ou superior
*   **Avaliação dos Consumidores:**
    *   [ ] 4 estrelas ou mais ★★★★☆
    *   [ ] 3 estrelas ou mais ★★★☆☆
*   **Condição / Vendedor:**
    *   [ ] Vendido e entregue pela loja principal
    *   [ ] Vendedores parceiros (Marketplace)
    *   [ ] Produtos Reembalados/Open Box

**Justificativa de UX:** A combinação de *Sliders* (para valores contínuos como preço) e *Checkboxes* (para valores discretos e seleções múltiplas como marca e memória) garante que o usuário consiga "esculpir" a lista de milhares de produtos até chegar nos 3 ou 4 itens que realmente atendem à sua necessidade técnica e orçamentária.
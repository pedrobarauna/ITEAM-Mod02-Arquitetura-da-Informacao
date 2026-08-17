# 📊 Atividade 02 — Análise Comparativa: G1 vs. R7

## 1. Objetivo da Análise
Realizar uma análise comparativa de usabilidade, Arquitetura da Informação e Design de Interação entre os portais de notícias **G1** e **R7**. A avaliação considera layout, hierarquia estrutural, eficiência dos sistemas de busca, poluição visual e adaptação responsiva (Desktop e Mobile).

---

## 2. Layout, Estrutura e Organização Visual

### O Modelo G1 (Foco na Leitura e Respiro)
*   **Web e Mobile:** O G1 utiliza um design minimalista (*Clean Design*). A estrutura baseia-se em um fundo branco predominante com alto uso de "espaço em branco" (*white space*).
*   **Hierarquia:** Ditada estritamente pela tipografia. A notícia principal ganha fontes maiores e o uso estratégico da cor vermelha guia o olhar para as editorias ou alertas.
*   **Poluição Visual:** Baixa. Banners de publicidade existem, mas estão bem delimitados em blocos horizontais que não se misturam com o conteúdo jornalístico.

> **Evidências — Primeira Dobra (Home Web e Mobile):**
> ![Home G1 e R7 Web](evidencias/atividade02/01-home-g1-r7.png)


### O Modelo R7 (Foco em Módulos e Retenção)
*   **Web e Mobile:** O R7 opta por um layout modular denso. A forte presença das cores da marca (azul e amarelo) em fundos e faixas concorre diretamente com a atenção das fotos das notícias.
*   **Hierarquia:** A página é dividida por "programas" da emissora (ecossistema Record). A hierarquia visual foca mais no tamanho das imagens do que na tipografia.
*   **Poluição Visual:** Alta. A carga cognitiva é maior devido à grande quantidade de *thumbnails* (miniaturas), blocos coloridos e divisão excessiva de seções.

> **Evidências — Alta densidade de informações (Home Web e Mobile):**
> ![Home R7 Web](evidencias/atividade02/02-home-r7-web.jpg)
> ![Home R7 Mobile](evidencias/atividade02/04-home-r7-mobile.jpg)

---

## 3. Arquitetura da Informação e Navegação Global

Neste ponto, encontra-se a diferença estrutural mais crítica entre os dois portais.

### G1: Previsibilidade e Controle
*   **Menu Global:** O menu principal (hambúrguer) e a busca estão **sempre visíveis** na página inicial (Web e Mobile), garantindo a heurística de "Controle e Liberdade do Usuário".
*   **Rotulagem:** Clara e categorizada exclusivamente por editorias jornalísticas (letras minúsculas).

> **Evidências — Menu bem estruturado e visível:**
> ![Menu G1 Web](evidencias/atividade02/07-menu-g1-web.jpg)
> ![Menu G1 Mobile](evidencias/atividade02/05-menu-g1-mobile.jpg)

### R7: Quebra de Padrão e Fricção ("Menu Fantasma")
*   Uma falha grave de usabilidade foi identificada na página inicial: **não há botão de menu e nem campo de busca visíveis**.
*   **Erro de Arquitetura:** Eles só aparecem quando o usuário clica e abre uma notícia específica. Isso quebra o modelo mental do usuário, que espera encontrar a navegação principal no cabeçalho (*header*) da Home. Além disso, a rotulagem mistura jornalismo factual com entretenimento (ex: novelas e podcasts no mesmo nível hierárquico).

> **Evidências — Menu que só aparece dentro da matéria (Web e Mobile):**
> ![Menu R7 Web](evidencias/atividade02/08-menu-r7-web-noticia.jpg)
> ![Menu R7 Mobile](evidencias/atividade02/06-menu-r7-mobile-noticia.jpg)

---

## 4. Sistema de Busca e Recuperação de Informação

### A Excelência do G1
O G1 apresenta um sistema de busca robusto e de fácil localização.
*   **Filtros Avançados:** O portal não apenas entrega resultados precisos, mas oferece refinamento por formato (Notícias, Vídeos, Fotos) e período temporal. A página de resultados foca em títulos claros e resumos curtos.

> **Evidências — Fluxo de Pesquisa e Filtros no G1:**
> ![Busca G1 Web](evidencias/atividade02/09-busca-g1-web.jpg)
> ![Filtros Mobile G1](evidencias/atividade02/10-busca-g1-mobile.jpg)
> ![Resultados Mobile G1](evidencias/atividade02/11-resultado-g1-mobile.jpg)

### O Fracasso do R7
*   **Impossibilidade de Teste Direto:** Devido ao "sumiço" do cabeçalho na página inicial, acessar o campo de busca exige um esforço desnecessário (entrar em uma notícia qualquer primeiro), frustrando o fluxo de usuários que já chegam ao portal com o objetivo de pesquisar.

---

## 5. Experiência de Leitura e Design da Notícia (Páginas Internas)

### G1: Leitura Fluida
*   **Layout:** Organizado. Texto, fotos e vídeos respeitam as margens e oferecem conforto visual.
*   **Ecossistema:** Integração suave de links correlatos, palavras-chave e sugestões de matérias.
*   **Publicidade:** Banners bem distribuídos, sem quebrar bruscamente a jornada de leitura.

> **Evidência — Estrutura de matéria no G1:**
> ![Página da Notícia G1](evidencias/atividade02/12-noticia-g1-web.jpg)

### R7: Poluição Visual e "Dark Patterns"
*   **Carga Cognitiva e Ads:** A página é agressivamente poluída. Banners imensos e pop-ups interrompem a leitura. Na versão mobile, a navegação torna-se frustrante pois a publicidade domina e empurra o conteúdo útil.
*   **Botão limitador:** O portal corta o texto da notícia pela metade, exigindo que o usuário clique em um botão **"Veja mais"** para continuar lendo o mesmo assunto. Isso causa estranheza e induz ao erro.
*   **Ponto Positivo (Acessibilidade):** Traz uma barra nativa no topo da matéria para ajuste de tamanho da fonte e contraste da tela.

> **Evidência — Poluição e botão de interrupção de texto no R7:**
> ![Página da Notícia R7](evidencias/atividade02/13-noticia-r7-web.jpg)

---

## 6. Quadro Comparativo Consolidado

| Critério de UX/UI | G1 (Globo) | R7 (Record) |
| :--- | :--- | :--- |
| **Navegação (Home)** | 🟢 Excelente. Menu e Busca sempre acessíveis. | 🔴 Péssima. Menu e Busca desaparecem da página inicial. |
| **Pesquisa e Filtros** | 🟢 Robusta. Ótimos filtros de data, tipo e relevância. | 🔴 Inviável na Home por falha estrutural. |
| **Leitura da Notícia** | 🟢 Limpa, centralizada e confortável. | 🔴 Confusa, interrompida pelo botão "Veja mais". |
| **Publicidade (Ads)** | 🟡 Equilibrada. Não quebra o fluxo de leitura. | 🔴 Agressiva. Banners gigantes sobrecarregam a tela. |
| **Design Responsivo** | 🟢 Organização lógica em blocos com destaques essenciais. | 🔴 Layout pesado, com rolagem excessiva devido aos anúncios. |
| **Acessibilidade** | 🟡 Padrão (depende do navegador). | 🟢 Positivo. Conta com botões de tamanho de fonte e contraste nativos na página. |

---

## 7. Conclusão Final

A análise revela duas estratégias de produto digital completamente distintas:

O **G1** adota uma postura **"User-Centric" (centrada no usuário)**. Sua arquitetura de informação prioriza a eficiência: o usuário encontra a notícia de forma previsível e a interface limpa protege a escaneabilidade.

O **R7** adota uma postura focada puramente em **Exposição e Retenção Forçada**. A página funciona como uma "vitrine de shopping" para todo o ecossistema da Record. A ausência de menu e busca na *Home*, somada ao limitador de texto ("Veja mais") nas matérias e à extrema poluição de anúncios publicitários, elevam a carga cognitiva ao limite. Isso sacrifica a usabilidade básica em prol da monetização agressiva, resultando em uma jornada confusa, especialmente em dispositivos móveis.

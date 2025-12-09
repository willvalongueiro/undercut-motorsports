UnderCut Motorsports – estatísticas para publicar

### Tese do projeto

Traduzir corrida em números com narrativa. Não é só “tabela de tempos”, é “como a corrida se distorceu taticamente”.

### Primeira entrega

Um post com **1 estatística principal bem explicada** + **1 gráfico/tabela**, sobre uma corrida específica ou recorte (ex: evolução de ritmo de um piloto, comparativo de stints, etc.).

### Micro-passos

> Definir estratégia para capturar e armazenar os dados da API de dados sobre a Fórmula 1.

1. **Escolher recorte**

[EDITAR]
   * Ex.: “última corrida”, ou “temporada 2025 do piloto X”.
   * Definir em uma linha:

[EDITAR]
     > “Quero mostrar como [piloto/equipe] ganhou/perdeu corrida por causa de [fator tático Y].”

2. **Listar métricas relevantes**

   * Ex.: tempo médio por stint, diferença média para o líder, evolução da posição volta a volta, etc.
   * 3–5 métricas, sem exagero.

3. **Montar base de dados (mesmo que na mão, no começo)**

   * Arquivo CSV simples com colunas tipo: `volta`, `piloto`, `tempo_volta`, `pneu`, `posição`.
   * Se ainda não tiver automação, pode ser um recorte pequeno (10–20 voltas chave).

4. **Explorar em notebook**

   * criar `undercut_stats.ipynb`:

     * ler CSV,
     * calcular as métricas,
     * gerar 1–2 gráficos simples.

5. **Transformar em narrativa**

   * Pegar o gráfico mais expressivo e escrever:

     * 1 parágrafo de contexto da corrida,
     * 1 parágrafo explicando o gráfico,
     * 1 parágrafo fechando com “o que isso mostra sobre estratégia”.

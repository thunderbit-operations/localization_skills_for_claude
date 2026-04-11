# Avaliação de Qualidade — Português (Brasil)

## Dimensões de Avaliação (4 × 2.5 = 10 pontos)

### D1: Naturalidade Linguística (2.5 pontos)

| Pontuação | Critério |
|-----------|----------|
| 2.5 | Leitura completamente natural, impossível distinguir de conteúdo escrito originalmente em PT-BR |
| 2.0 | Algumas frases soam levemente traduzidas, mas não comprometem a leitura |
| 1.5 | Estruturas frasais visivelmente influenciadas pelo inglês em múltiplos pontos |
| 1.0 | Parece tradução automática com edição superficial |
| 0.5 | Tradução literal óbvia, leitura desconfortável |

Verificar:
- Ordem das palavras natural em PT-BR (não calque do inglês)
- Uso correto de preposições e regência verbal
- Contrações e expressões naturais ("pra", "a gente" vs "nós" em contexto informal)
- Ausência de gerundismo excessivo ("estar fazendo" quando "fazer" basta)
- Termos tech em inglês usados corretamente (não traduzidos quando não devem)

### D2: Adaptação Cultural (2.5 pontos)

| Pontuação | Critério |
|-----------|----------|
| 2.5 | Referências, exemplos e tom perfeitamente adaptados ao público brasileiro |
| 2.0 | A maioria das referências adaptadas, uma ou duas ainda americanizadas |
| 1.5 | Mistura de referências adaptadas e não adaptadas |
| 1.0 | Poucas adaptações culturais, ainda parece conteúdo americano traduzido |
| 0.5 | Nenhuma adaptação cultural |

Verificar:
- Metáforas e analogias relevantes para o público brasileiro
- Moeda em R$ quando aplicável
- Exemplos de mercado/empresas brasileiras quando possível
- Tom adequado para profissionais de negócios brasileiros

### D3: Integridade Técnica (2.5 pontos)

| Pontuação | Critério |
|-----------|----------|
| 2.5 | Todos os componentes, links, imagens e formatação perfeitamente preservados |
| 2.0 | Um erro menor (espaço extra, formatação inconsistente) |
| 1.5 | 2-3 erros técnicos menores |
| 1.0 | Componente quebrado ou link incorreto |
| 0.5 | Múltiplos componentes quebrados |

Verificar:
- `<SideCard>`, `<TryButton>`, `<BottomCard>` intactos com title traduzido
- `<VideoPlayer>`, `<Table>` com content inalterado
- URLs de imagens preservadas
- Markdown válido (headers, listas, links, bold/italic)
- Links internos com prefixo `/pt/`

### D4: Valor de Conteúdo e SEO (2.5 pontos)

| Pontuação | Critério |
|-----------|----------|
| 2.5 | Conteúdo agrega valor equivalente ou superior ao original, keywords naturalmente integradas |
| 2.0 | Bom valor de conteúdo, keywords presentes mas levemente forçadas |
| 1.5 | Conteúdo adequado mas com perda parcial de nuance ou impacto |
| 1.0 | Informação preservada mas sem engajamento |
| 0.5 | Perda significativa de valor informativo |

Verificar:
- Estrutura H1 > H2 > H3 preservada
- Keywords adaptadas para termos de busca em PT-BR
- CTAs eficazes e naturais
- Fluxo lógico mantido ou melhorado

## Formato de Saída do Relatório

```
## 📊 Relatório de Qualidade — Português (Brasil)

| Dimensão | Pontuação | Detalhes |
|----------|-----------|----------|
| D1 Naturalidade | X.X/2.5 | ... |
| D2 Cultura | X.X/2.5 | ... |
| D3 Técnica | X.X/2.5 | ... |
| D4 Conteúdo/SEO | X.X/2.5 | ... |
| **Total** | **X.X/10** | |

### Deduções detalhadas
- Linha XX: "texto problemático" → sugestão (−0.X, DX)
...

### Resumo
[1-2 frases sobre qualidade geral e principais pontos de melhoria]
```

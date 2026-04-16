# Emilia-Romagna — Gastronomia & Erbazzone

Apresentação para a disciplina **AEP Profissional II — Gastronomia Italiana**.

## Estrutura

```
index.html          — apresentação completa (engine JS próprio, sem frameworks)
images/             — fotografias usadas nos slides
  fig1.png          — Arcadas de Bolonha (hero)
  fig5.png          — Armazém de Parmigiano Reggiano
  fig6.png          — Mapa da Emilia-Romagna
  fig7.png          — Erbazzone cortado em quadrados
2026-04-13 *.pdf    — páginas da receita de erbazzone (fonte)
```

## Slides

| # | Título | Conteúdo |
|---|--------|----------|
| 1 | Hero | Emilia-Romagna · Prazeres Suínos e Delícias Epicuristas |
| 2 | A Região | Via Emília, mapa, estatísticas (Parmigiano, Prosciutto, Aceto) |
| 3 | Gastronomia | Bolonha, Modena, Parma/Reggio, Romagna |
| 4 | O Prato | Erbazzone — origem, descrição, ingredientes |
| 5 | Preparação | 4 etapas: fuiada, pancetta, acelga, montagem e forno |
| 6 | Harmonização | Lambrusco di Sorbara · Sangiovese di Romagna · Colli di Scandiano |
| 7 | Análise Estrutural | Avaliação estrutural das 3 harmonizações: regras, riscos e veredictos |

## Engine de apresentação

Implementação própria (~40 linhas JS) substituindo Reveal.js, que conflituava com o layout flex.  
Funcionalidades: transição por opacidade, escala por `transform:scale()`, teclado e botões de navegação, barra de progresso.

## Harmonização — método aplicado

A análise estrutural do slide 7 aplica a **Pirâmide Sensorial de Harrington** em três camadas:

| Camada | Comida | Vinho |
|--------|--------|-------|
| Base | SAUDA — Salinidade · Acidez · Umami · Doçura · Amargor | ADE — Acidez · Doçura · Efervescência |
| Textura | GMPC — Gordura · Método · Proteína · Corpo | CATA — Corpo · Álcool · Taninos · cArvalho |
| Sabores | AIP — Tipo de Aroma · Intensidade · Persistência | AIP |

Perfil do erbazzone: salinidade alta · acidez baixa · umami alto · doçura baixa · amargor médio · gordura alta · proteína moderada · método forno.

Os três vinhos são regionais e estruturalmente sólidos. Risco principal: taninos do Sangiovese com gordura láctea e umami alto — mitigado pela salinidade alta da pancetta e do Parmigiano.

Documentação completa do framework: `AEP Profissional III\Maridagem\doc\`

## Como ver

Abrir `index.html` num servidor local (ex: `npx http-server`) ou directamente no browser.  
Navegar com ← → ou clicando nas setas laterais.

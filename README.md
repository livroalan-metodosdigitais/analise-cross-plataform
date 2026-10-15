# Análise _cross-platform_ sobre buscas em redes sociais

## Sobre a pesquisa

Este repositório reúne os materiais metodológicos da pesquisa comparativa sobre resultados de busca relacionados a “TDAH adulto” no TikTok, Instagram e X/Twitter.

A pesquisa examina como as diferenças entre plataformas afetam a coleta e a comparabilidade dos dados. O foco está nas condições de busca, nas affordances, nas formas de acesso e nos limites técnicos de cada ambiente e não na análise isolada do conteúdo das publicações.

A investigação parte da seguinte pergunta: De que modo a busca cross-platform permite identificar assimetrias estruturais entre plataformas e como o desenho das consultas e as diferenças entre os objetos digitais condicionam sua comparabilidade?

O estudo adota uma perspectiva meta-analítica: o desenho das consultas e as dificuldades encontradas durante a coleta também são tratados como objetos de análise. A pesquisa se fundamenta nos métodos digitais e na análise _cross-platform_ (Rogers, 2009, 2013, 2025).

## Estratégia de coleta

As coletas foram realizadas com o 4CAT: Capture and Analysis Toolkit e a extensão de navegador Zeeschuimer, disponível para Firefox. O 4CAT é uma ferramenta de pesquisa de código aberto baseada na Web (Peeters e Hagen, 2022). Foram realizadas duas etapas de coleta:

### Primeira etapa: 12 de novembro de 2025

- **TikTok:** busca por `tdah adulto`, na aba “Vídeos”. Foram capturados 330 itens, até a plataforma apresentar a mensagem “Você chegou ao fim”.
- **X/Twitter:** busca por `tdah adulto`, na aba “Latest”. Foram capturados 334 itens. A quantidade foi definida para se aproximar do total obtido no TikTok; portanto, não corresponde necessariamente ao total disponível na plataforma.
- **Instagram:** busca por `#tdahadulto`. A versão Web utilizada exigia o símbolo `#` para localizar hashtags. Foram capturados 52 itens. A interface indicava mais de 305 mil publicações, mas foram observadas repetições nos resultados.

### Segunda etapa: 30 de novembro de 2025

Foram repetidos os procedimentos da primeira etapa, com as seguintes observações:

- **TikTok:** busca por `tdah adulto`, na aba “Vídeos”. A página foi atualizada três vezes após a mensagem “Você chegou ao fim”, seguindo orientação da documentação do 4CAT. O Zeeschuimer registrou 369 itens.
- **Instagram:** busca por `#tdahadulto`. Mesmo após atualizar a página, foram capturados 55 itens e persistiram resultados repetidos.
- **X/Twitter:** foram realizadas duas buscas: `tdah adulto`, na aba “Latest”, que resultou em 353 itens; e `#tdahadulto`, que resultou em 321 itens.

As coletas foram realizadas com uma conta recém-criada, vinculada a um endereço de e-mail novo, com o objetivo de reduzir possíveis interferências de históricos de navegação e perfis antigos. Os procedimentos foram executados em dois sistemas operacionais: macOS e Windows.

## Consultas utilizadas

| Plataforma | Data | Consulta | Área ou modo de busca | Itens capturados |
|---|---|---|---|---:|
| TikTok | 12/11/2025 | `tdah adulto` | Aba “Vídeos” | 330 |
| Instagram | 12/11/2025 | `#tdahadulto` | Busca por hashtag na versão Web | 52 |
| X/Twitter | 12/11/2025 | `tdah adulto` | Aba “Latest” | 334 |
| TikTok | 30/11/2025 | `tdah adulto` | Aba “Vídeos”; página atualizada três vezes após “Você chegou ao fim” | 369 |
| Instagram | 30/11/2025 | `#tdahadulto` | Busca por hashtag na versão Web | 55 |
| X/Twitter | 30/11/2025 | `tdah adulto` | Aba “Latest” | 353 |
| X/Twitter | 30/11/2025 | `#tdahadulto` | Busca com hashtag | 321 |

As consultas não são idênticas em todas as plataformas: a busca do Instagram exigiu o caractere `#`, enquanto TikTok e X/Twitter também foram consultados com a expressão sem o símbolo.

## Ferramentas e ambiente

| Ferramenta ou ambiente | Uso | Versão |
|---|---|---|
| 4CAT: Capture and Analysis Toolkit | Captura e organização dos dados | v1.51 |
| Zeeschuimer | Captura de resultados por meio do navegador | v1.13.4 |
| Firefox | Navegador usado com a extensão Zeeschuimer | v140.5.0 |

## Tratamento dos dados

As bases capturadas pelo Zeeschuimer e armanezadas em arquivos .csv na base de dados do 4CAT. Os arquivos .csv foram organizadas em planilhas. A análise comparou os itens coletados em cada plataforma e nas duas datas.

Foram observados:

- o número de itens capturados por plataforma e consulta;
- a presença de publicações idênticas entre as coletas;
- a composição linguística dos resultados do X/Twitter;
- métricas de engajamento disponíveis nas publicações do Instagram e do TikTok;
- registros no campo `stickers` do TikTok em publicações sem menção visível à hashtag;
- respostas da interface e limites percebidos durante a coleta, como repetição de resultados e a mensagem “Você chegou ao fim”.
- Critério para identificar publicações idênticas foi a partir da coluna "ID", presente em todas as bases coletadas. 

## Fluxo da análise

1. Definição do problema de pesquisa e da abordagem cross-platform.
2. Seleção de TikTok, Instagram e X/Twitter para observar diferenças entre ambientes digitais.
3. Definição da expressão de busca relacionada a “TDAH adulto” e adaptação das consultas às possibilidades de cada plataforma.
4. Captura dos resultados em 12 e 30 de novembro de 2025 com 4CAT e Zeeschuimer.
5. Organização das bases capturadas em planilhas.
6. Comparação do volume de itens por plataforma, consulta e data.
7. Análise dos indicadores de engajamento e dos campos de metadados pertinentes.
8. Interpretação das diferenças e dificuldades de coleta como evidências das condições e limitações de comparação entre plataformas.

## Organização do repositório

/data: Bases de dados originais

/docs: Base de dados disponíveis em planilhas

README.md: Apresentação do projeto e instruções metodológicas

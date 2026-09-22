# 12 — Produção PPTX

## Requisito principal

Defina se o arquivo final precisa ser:
- apenas visual;
- totalmente editável;
- compatível com PowerPoint desktop;
- compatível com Google Slides;
- exportável para PDF;
- automatizado por código.

## Slide master

Quando possível, crie masters para:
- capa;
- conteúdo;
- seção;
- dados;
- fechamento.

## Componentes reutilizáveis

Padronize:
- título;
- subtítulo;
- footer;
- número de página;
- tag;
- KPI;
- callout;
- chart title;
- source line.

## PptxGenJS

Ao gerar programaticamente:
- trabalhe em coordenadas consistentes;
- crie helpers para tipografia e componentes;
- valide overflow de texto;
- mantenha imagens com aspect ratio correto;
- use charts nativos quando editabilidade for prioridade;
- use SVG para ícones e diagramas quando compatível;
- evite rasterizar texto.

## QA técnico

Cheque:
- clipping;
- objetos fora do slide;
- fontes substituídas;
- links quebrados;
- imagens pixeladas;
- charts sem labels;
- elementos não editáveis quando deveriam ser;
- diferenças entre PPTX e PDF.

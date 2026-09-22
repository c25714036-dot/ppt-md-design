# PPT MD Design

Biblioteca modular em Markdown para planejar, dirigir, desenhar, revisar e produzir apresentações profissionais em PowerPoint, Google Slides, Keynote ou por geração programática.

A proposta não é fornecer um único template. A biblioteca funciona como um **sistema de decisão de design**: briefing → narrativa → DNA visual → composição → dados e imagens → produção → QA.

## Objetivos

- transformar conteúdo bruto em narrativa visual;
- reduzir apresentações genéricas ou com “cara de IA”;
- criar consistência visual sem repetir o mesmo layout;
- orientar hierarquia, grid, tipografia, cor, imagens, ícones e dados;
- facilitar produção de `.pptx` editável;
- servir como referência para ChatGPT, Claude, Copilot, Codex e outros agentes.

## Fluxo recomendado

1. Leia `SKILL.md`.
2. Preencha `templates/presentation-brief.md`.
3. Defina a arquitetura em `docs/02-storytelling-architecture.md`.
4. Construa o DNA visual em `docs/03-design-dna.md`.
5. Use `docs/10-slide-patterns.md` para variar composições.
6. Escolha o playbook do tipo de apresentação.
7. Produza o arquivo usando `docs/12-pptx-production.md`.
8. Valide com `docs/14-visual-qa.md`.

## Estrutura

```text
ppt-md-design/
├── README.md
├── SKILL.md
├── DESIGN.md
├── AGENTS.md
├── docs/
├── playbooks/
├── templates/
├── prompts/
└── references/
```

## Regra principal

> Um bom deck não é uma sequência de páginas bonitas. É uma sequência de decisões visuais que conduz a audiência de uma ideia para a próxima.

## Licença

MIT. A biblioteca é original e usa repositórios públicos apenas como referências conceituais listadas em `references/SOURCES.md`.

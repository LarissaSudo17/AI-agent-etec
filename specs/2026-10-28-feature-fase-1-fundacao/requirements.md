# Requisitos do recurso

## Contexto
Este recurso corresponde à Fase 1 do roadmap e representa a fundação do site institucional da escola técnica.

A estrutura inicial deve apoiar a missão do projeto: apresentar a escola com credibilidade, divulgar notícias e expor um catálogo funcional de cursos técnicos.

## Escopo
- Página inicial institucional com apresentação da escola.
- Catálogo inicial de cursos técnicos.
- Estrutura mínima de matrizes curriculares.
- Área de login para cadastro de notícias.
- Persistência inicial usando SQLite.
- Implementação responsiva para navegadores modernos e mobile.

## Decisão de arquitetura
- Usar React + TypeScript como base para a interface.
- Usar SQLite no início para reduzir complexidade do projeto.
- Priorizar uma estrutura simples, clara e segura para a primeira entrega.
- Manter o conteúdo dos cursos alinhado ao site antigo da Etec Sales Gomes.

## Contexto operacional
- O catálogo deve refletir os cursos do ensino técnico previstos.
- As matrizes curriculares podem usar dados mockados temporariamente.
- As matérias podem ser inspiradas na internet ou definidas provisoriamente.
- A área administrativa deve permitir publicar notícias na página principal.

## Fora do escopo desta fase
- Personalização avançada de tema visual.
- Sistema de autenticação completo e multiusuário.
- CMS sofisticado com múltiplos módulos.
- Integrações externas de grande porte.

## Referência
- Mission: [specifications/mission.md](../../specifications/mission.md)
- Stack: [specifications/tech-stack.md](../../specifications/tech-stack.md)
- Roadmap: [specifications/roadmap.md](../../specifications/roadmap.md)

# CLAUDE.md

## Projeto

Este projeto gera uma apresentação profissional em PDF para um serviço
de aulas particulares de surf.

## Fonte de verdade

As informações oficiais do serviço estão em:

- docs/service-spec.md

O briefing específico do PDF está em:

- docs/pdf-brief.md

As diretrizes visuais estão em:

- docs/design-guidelines.md

Nunca alterar preços, duração, políticas ou regras sem autorização.

## Estrutura

- docs/ = documentação e conteúdo
- assets/ = imagens e elementos visuais
- src/ = código-fonte do documento
- dist/ = arquivos finais gerados

## Desenvolvimento

O PDF deve ser pensado principalmente para:

1. visualização em celular;
2. envio por WhatsApp;
3. visualização em computador;
4. impressão.

Priorizar design limpo, profissional e responsivo.

## Regra importante

Não colocar informações novas no PDF que não estejam documentadas
em docs/service-spec.md.

Antes de gerar a versão final, revisar textos, valores e regras.
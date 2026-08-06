# Prontidão do domínio raiz — vitrine ROTINA ACS

Estado-base: `61e1dd44e27e63848158be249a2cd9953b4a19fa` (`main`).

- URL histórica: `https://leothaylor.github.io/FerramentasparaACSTiktok/`
- URL oficial pretendida: `https://rotinaacs.com.br/`
- `CNAME` atual: `rotinaacs.com.br`
- Branch local de preparação: `prep/domain-migration-20260806`

## Preparação incluída

- Canonical e Open Graph do domínio raiz.
- CTA do SuperKit atualizado localmente para a landing oficial validada.
- Links de APS 360 e Radar permanecem nas URLs históricas até autorização específica dos subdomínios.

## Go/no-go

Publicar somente quando o domínio raiz resolver para os quatro IPs do GitHub Pages e o GitHub indicar DNS válido. Antes do merge, testar todos os links com UTMs e confirmar que nenhuma URL antiga será desativada.

## Rollback

1. Reverter o commit de preparação da vitrine.
2. Se necessário, remover o domínio personalizado no GitHub Pages somente dentro de uma janela autorizada.
3. Confirmar que a URL histórica voltou a responder sem redirecionamento.

O `fbclid` é removido pela implementação atual da vitrine; essa decisão deve ser revista antes de campanhas Meta, sem mudança automática nesta preparação.

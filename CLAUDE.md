# Política de Privacidade — Extensão Exportador

## 1. Visão geral

Página estática de política de privacidade da extensão Chrome [IA Assist Exportador](../CLAUDE.md), publicada via GitHub Pages para atender à exigência de URL pública da Chrome Web Store.

## 2. Estado atual

Publicada e ativa: repositório GitHub `eletonsantos/ia-assist-exportador`. Documenta, entre outros pontos, a captura de mensagens do WhatsApp Web introduzida na v2.0 da extensão (adicionado nesta migração, 11/09/2026 — conteúdo já existia localmente, sem commit).

## 3-8. Arquitetura / Tecnologias / Como executar / Variáveis / Integrações / Banco

HTML estático puro (`privacy-policy/index.html`). Sem build, sem dependências, sem backend.

## 9. Decisões importantes do projeto

**Este repositório é intencionalmente público** — GitHub Pages exige repositório público (no plano gratuito), e a Chrome Web Store exige URL pública de política de privacidade.

## 10. Regras para futuros desenvolvimentos

Sempre que o comportamento do [Exportador](../CLAUDE.md) mudar (novos domínios acessados, novos dados lidos/armazenados), esta política precisa ser atualizada junto.

## 11. Histórico importante

2 commits até esta migração: página inicial + documentação da captura de mensagens do WhatsApp Web (v2.0).

## 12-14. Próximas etapas / Arquivos críticos / Deploy

Nenhuma pendência conhecida. `privacy-policy/index.html` é o único arquivo relevante. Deploy automático via GitHub Pages.

## 15. Migração Windows → macOS

Nenhuma dependência — HTML estático. Nada a ajustar.

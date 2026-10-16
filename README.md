# Despertar na Prática – 21 Dias

Landing page independente da Muuna Luz em HTML e CSS, sem dependências de aplicação ou etapa de build.

## Desenvolvimento

No checkout existente, execute:

```sh
python3 -m http.server 4173 --bind 0.0.0.0
```

O servidor serve a página e os arquivos estáticos pela porta 4173. Nenhuma conexão com Supabase, autenticação, banco de dados ou aplicativo em produção é necessária. Os botões de compra apontam para o checkout Zuptos fornecido no briefing.

## Materiais

Os arquivos originais permanecem na raiz. A pasta `assets/` contém versões WebP otimizadas derivadas desses arquivos, sem imagens geradas ou de banco genérico.

## Pendência para a versão final

Ainda faltam capturas reais do aplicativo (registros pessoais, Meu Mapa e práticas diárias). A seção de experiência contém um aviso de revisão até que sejam fornecidas. Não substituir por interfaces fictícias.

## Revisão

Verificada em Chromium nas larguras 1440, 390 e 320 px: cinco seções, imagens carregadas, sem transbordamento horizontal, FAQ funcional e todos os CTAs de compra com o destino informado. Revisar conteúdo e aparência com a responsável antes de qualquer publicação.

Não publicar sem aprovação explícita. O desenvolvimento desta página não exige alterações no aplicativo existente, Supabase, checkout ou infraestrutura.

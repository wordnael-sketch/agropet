# Agropet Pets — Loja online

Site da Agropet Pets (Taguatinga Sul e Vereda da Cruz, Brasília/DF). O cliente monta o pedido no site e finaliza pelo WhatsApp (61) 99902-2443. A loja confirma pelo WhatsApp se entrega no bairro e qual é a taxa.

## Estrutura

- `index.html` — página única, sem build (HTML, CSS e JS puros)
- `img/` — imagens
  - `ai-*` — fotos geradas por IA (Canva)
  - `ig-*` — fotos do Instagram @agropet.pets
  - `p-*` — embalagens recortadas do encarte da loja

## Como editar

- **Produtos e preços:** lista `PRODUCTS` no `<script>` do fim do `index.html`. `price: 0` mostra "Consulte na loja".
- **WhatsApp:** constante `PHONE`.
- **Mensagens prontas do WhatsApp:** objeto `WA_TEXT`.

## Publicar

É um site estático. Funciona em GitHub Pages (Settings › Pages › branch `main`), na Vercel ou na Netlify sem nenhuma configuração.

## Pendências

- Confirmar os preços (tirados do encarte e da fachada) e o preço do Quali Day e dos animais
- Bairros atendidos e taxas de entrega
- Imagens de IA em 550 px: trocar por versões em alta resolução

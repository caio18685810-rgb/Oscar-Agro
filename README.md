# Oscar Agro
Prévia institucional demonstrativa em React, TypeScript, Vite, Tailwind CSS e Lucide React.

## Executar
Requer Node.js 22.12+ (validado com Node 24).

```sh
npm ci
npm run dev
```

```sh
npm run build
npm run preview
```

A navegação usa âncoras; categorias filtram os produtos de exemplo e Consultar abre a área de contato demonstrativa. Não há backend, pagamentos ou envio de mensagens. Telefone e Instagram aguardam confirmação oficial.

## Imagens
Fotografias via Unsplash, sob a [licença Unsplash](https://unsplash.com/license), identificadas pelo ID na URL em `src/main.tsx`. Os URLs originais de distribuição completos estão no código. Hero: https://images.unsplash.com/photo-1500595046743-cd271d694d30. As imagens requerem conexão ao domínio images.unsplash.com. Fundos em verde/creme preservam a leitura caso não carreguem. Embalagens são ilustrações SVG próprias, sem marcas comerciais ou especificações confirmadas.

Esta prévia não confirma catálogo, disponibilidade, condições comerciais ou canais oficiais. Publicação autorizada no GitHub Pages. A branch main aciona o workflow .github/workflows/pages.yml.

## GitHub Pages
O workflow publica o build com `VITE_BASE_PATH=/Oscar-Agro/`. Localmente o caminho base continua `/`.

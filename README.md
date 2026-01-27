#  LinkTreeLoja

Este projeto foi criado para servir como uma página de links personalizada (similar ao Linktree), voltada para uma loja de informática que oferece serviços de conserto de computadores, impressoras, celulares e televisores.

---

## Como foi criado

1. **Configuração inicial**
   - O projeto foi iniciado com [Vite](https://vitejs.dev/) e [React](https://react.dev/).
   - Foi configurado o `vite.config.js` para ajustar o build e permitir acesso via ngrok.

2. **Estrutura de componentes**
   - Criamos componentes em React para organizar o conteúdo:
     - `Trabalhos.jsx`: mostra os serviços realizados com cards e imagens.
     - `Links.jsx`: lista de links de contato (Google Avaliações, Google Maps, Facebook, WhatsApp, Celular).
     - `Header.jsx`: cabeçalho com o logo da loja.

3. **Imagens**
   - As imagens foram adicionadas na pasta `src/assets` ou `public/`.
   - No React, usamos `import` para que o Vite inclua corretamente no build.

4. **Estilização**
   - Utilizamos CSS para criar uma grade de trabalhos e estilizar os cards.
   - Responsividade foi aplicada para funcionar bem em celulares.

5. **Build e Deploy**
   - O build é gerado com `npm run build`.
   - Os arquivos finais ficam na pasta `dist/`.
   - Testes foram feitos com `vite preview` e também com **ngrok** para acesso externo.

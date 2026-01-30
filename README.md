# LinkTreeLoja

Uma página de links personalizada (similar ao Linktree) para uma loja de informática especializada em conserto e manutenção de computadores, impressoras, celulares e televisores.

## 📋 Sobre o Projeto

LinkTreeLoja é uma solução web moderna e responsiva que centraliza todos os serviços e contatos da loja em uma única página acessível.

## 🛠️ Tecnologias Utilizadas

- **Vite** - Build tool rápido e otimizado
- **React** - Biblioteca para interface de usuário
- **CSS** - Estilização e responsividade
- **React Router** - Navegação entre páginas

## 📁 Estrutura do Projeto

```
src/
├── components/
│   ├── Header.jsx          # Cabeçalho com logo
│   ├── Trabalhos.jsx       # Galeria de serviços
│   └── Links.jsx           # Links de contato
├── assets/                 # Imagens e recursos
└── styles/
   └── index.css           # Estilos globais
```

## 🎯 Funcionalidades

- **Galeria de Serviços** - Cards com descrição de trabalhos realizados
- **Links de Contato** - Acesso direto a Google Avaliações, Google Maps, Facebook, WhatsApp e telefone
- **Design Responsivo** - Otimizado para desktop, tablet e celular
- **Performance** - Otimizado com Vite para carregamento rápido

## 🚀 Como Rodar Localmente

```bash
# Instalar dependências
npm install

# Executar em desenvolvimento
npm run dev

# Fazer build para produção
npm run build

# Visualizar build
npm run preview
```

## 📦 Deploy

Os arquivos compilados são gerados na pasta `dist/` e podem ser deplorados em qualquer servidor estático ou plataforma como Vercel, Netlify ou ngrok.

## 📝 Notas

- Imagens armazenadas em `src/assets/` ou `public/`
- Configuração do `vite.config.js` para acesso externo via ngrok
- Build otimizado para melhor performance em mobile

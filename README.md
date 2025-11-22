# Reprodutor de Mídia

## Descrição
Reprodutor de mídia para arquivos MP3 e vídeos MP4, desenvolvido com Next.js. Suporta playlists locais, controles personalizados, busca automática de capas via API do iTunes, barra de progresso e volume, com interface responsiva e consistente para áudio e vídeo.

## Funcionalidades
- Upload e seleção de arquivos MP3 e MP4 locais
- Reprodução sequencial com controles de play/pause, próximo, anterior, barra de progresso e volume
- Busca automática de capa e metadados via API do iTunes para músicas
- Interface responsiva, mantendo tamanho consistente para capas e vídeos
- Persistência da playlist durante a sessão
- Controles universais para áudio e vídeo, sem usar controles nativos do navegador

## Tecnologias Utilizadas
- Next.js
- React
- TypeScript
- Tailwind CSS

## Estrutura do Projeto

```
├── public/
│   ├── favicon_io.zip
│   ├── icon.svg
│   ├── favicon.ico
├── src/
│   └── app/
│   ├── play/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── .gitignore
├── README.md
├── eslint.config.mjs
├── next-env.d.ts
├── next.config.ts
├── package-lock.json
├── package.json
├── postcss.config.mjs
└── tsconfig.json
```

## Como Executar

```bash
git clone https://github.com/carlosabrantesdev/reprodutor-midia
cd reprodutor-midia
npm install
npm run dev
```

Acesse [http://localhost:3000](http://localhost:3000) no navegador para testar.

## Demonstração

![Demonstração do Reprodutor de Mídia](https://i.ibb.co/NdvdS86J/demonstracao.png)

## Autor

Desenvolvido por Carlos Abrantes
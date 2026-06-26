# Sala Cliente Lesaffre Narandiba

Projeto estático pronto para publicar no Vercel via GitHub.

## Como publicar

1. Crie um repositório novo no GitHub.
2. Suba todos os arquivos desta pasta para o repositório.
3. No Vercel, clique em **Add New Project** e importe o repositório.
4. Use as configurações abaixo, se o Vercel não detectar automaticamente:

| Campo | Valor |
| --- | --- |
| Framework Preset | Other |
| Build Command | `npm run build` |
| Output Directory | `dist` |
| Install Command | `npm install` |

## Desenvolvimento local

```bash
npm run build
npm start
```

O HTML principal fica em `index.html`. O build apenas copia este arquivo para `dist/index.html`, mantendo o site simples, rápido e sem dependências obrigatórias.

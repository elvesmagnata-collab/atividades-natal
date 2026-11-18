# Atividades de Natal para imprimir

Site estático (um único `index.html`, sem dependências nem build) com +200 fichas de Natal
para escola e família. Cada ficha descarrega-se em PNG A4 (1654×2339 px).

## Publicar no GitHub
```bash
git init
git add .
git commit -m "Atividades de Natal"
git branch -M main
git remote add origin https://github.com/O-TEU-UTILIZADOR/atividades-natal.git
git push -u origin main
```

## Publicar na Vercel
1. Em vercel.com → **Add New… → Project** e importa o repositório do GitHub.
2. **Framework Preset:** Other. Deixa **Build Command** e **Output Directory** vazios.
3. Clica em **Deploy**. O site fica em `https://o-teu-projeto.vercel.app`.

Cada `git push` para `main` volta a publicar automaticamente.

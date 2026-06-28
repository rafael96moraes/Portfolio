# Portfolio — Rafael Moraes

Portfolio pessoal com tema Calvin & Hobbes, construído com [Astro](https://astro.build).

## Stack

- **Astro** — static site generator (zero JS por padrão)
- **CSS puro** — tema custom Calvin & Hobbes com filtros SVG hand-drawn
- **Google Fonts** — Caveat (headings) + Patrick Hand (body)
- **Vercel** — deploy contínuo via GitHub

## Estrutura

```
src/
├── components/   # Componentes Astro (Header, Hero, About, Skills, Trajectory, Contact, Footer)
├── data/         # Dados em JSON (profile, skills, experience)
├── layouts/      # Layout base com meta tags e fontes
├── pages/        # Página principal (index.astro)
└── styles/       # Tema global (global.css)
public/assets/    # Imagens, SVGs e assets estáticos
```

## Comandos

| Comando | Ação |
|---|---|
| `npm run dev` | Servidor de desenvolvimento (http://localhost:4321) |
| `npm run build` | Gera site estático em `dist/` |
| `npm run preview` | Preview do build localmente |

## Personalizar

Edite os arquivos em `src/data/` para atualizar:
- `profile.json` — nome, bio, links
- `skills.json` — habilidades técnicas
- `experience.json` — trajetória profissional

## Deploy

O deploy é automático via Vercel ao fazer push no GitHub.

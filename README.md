# juliosantos73.github.io

Site pessoal e currículo online de **Julio Santos**, publicado via GitHub Pages.

🔗 https://juliosantos73.github.io/

---

## Stack

HTML + CSS + JavaScript puro. Sem frameworks, sem bundler, sem dependências de runtime.

## Estrutura

```
index.html              — página única com todo o conteúdo e lógica
assets/
  css/common.css        — todos os estilos
  img/
    julio-linkedin.jpeg — foto de perfil (hero)
    favicon.svg         — favicon com iniciais JS
.gitignore
```

## Funcionalidades

- **Seletor de idioma** 🇵🇹 🇬🇧 🇪🇸 — traduções via `data-i18n` e objeto `T`, guardadas em `localStorage`
- **Dark / light mode** — toggle com `data-theme` no `<html>`, sem flash ao carregar
- **Nav responsiva** — hamburger menu em mobile, sticky com blur
- **Projetos GitHub** — secção que busca automaticamente repos com o tópico `featured` via API pública
- **Animações de entrada** — Intersection Observer com fade + slide up, respeita `prefers-reduced-motion`
- **Open Graph / Twitter Card** — meta tags para partilha em redes sociais
- **Favicon SVG** — iniciais JS em cor accent, consistente com o logo da nav

## Secções

1. Hero — foto, nome, título, tagline, CTAs
2. Sobre — trajetória, contexto histórico, formação
3. Experiência — timeline com 4 posições
4. Stack — 5 categorias de tecnologias
5. Projetos — repos GitHub com tópico `featured`
6. Formação & Certificações — grau + Samsung Ocean + UniFavip Wyden
7. Footer — contacto e redes sociais

## Deploy

```bash
git add .
git commit -m "descrição"
git push origin main
```

O GitHub Pages publica automaticamente em ~1 minuto após o push.
Estado: https://github.com/juliosantos73/juliosantos73.github.io/actions

## Destacar projetos GitHub

Para um repositório aparecer na secção de projetos, adiciona o tópico `featured` nas suas Settings → About ⚙️ → Topics.

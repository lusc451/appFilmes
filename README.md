<h1 align="center">🎬 AppFilmes</h1>

<p align="center">
  Aplicativo mobile feito com <strong>React Native</strong> e <strong>Expo</strong> que consome a API do <strong>TMDB (The Movie Database)</strong>.<br />
  Com ele, você pode criar conta, autenticar, favoritar filmes, montar uma <em>watchlist</em>, avaliar filmes (★ de 1 a 5) e muito mais.
</p>

<p align="center">
  <!-- Badges (edite como quiser) -->
  <a href="https://reactnative.dev/"><img src="https://img.shields.io/badge/React%20Native-0.x-61DAFB?logo=react&logoColor=white" alt="React Native" /></a>
  <a href="https://expo.dev/"><img src="https://img.shields.io/badge/Expo-SDK%20x-000000?logo=expo&logoColor=white" alt="Expo" /></a>
  <a href="#-licença"><img src="https://img.shields.io/badge/Licença-MIT-green" alt="License MIT" /></a>
  <a href="https://www.themoviedb.org/"><img src="https://img.shields.io/badge/TMDB-API-blue" alt="TMDB" /></a>
  <a href="#-contribuição"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome" /></a>
</p>

> **Aviso:** Este aplicativo utiliza a API do TMDB, mas **não é certificado nem endossado** pelo TMDB.

---

## 📑 Índice
- [✨ Funcionalidades](#-funcionalidades)
- [🧱 Stack](#-stack)
- [🗂️ Estrutura](#️-estrutura)
- [🤝 Contribuição](#-contribuição)

---

## ✨ Funcionalidades

- 👤 **Autenticação de usuário** (criar conta e login)
- ⭐ **Favoritar** e **desfavoritar** filmes
- 🎯 **Watchlist**: criar/gerenciar lista do que deseja assistir
- ★ **Avaliação** de filmes (1 a 5 estrelas)
- 🔎 Busca de títulos e navegação por categorias
- 📄 Detalhes do filme (sinopse, nota, gêneros, elenco etc.)
- 🌙 Suporte a temas e UX responsiva (mobile-first)

---

## 🧱 Stack

- **React Native** + **Expo**
- **TMDB API** para catálogo de filmes
- **Axios** para requisições HTTP

---

## 🗂️ Estrutura

.
<br/>
├── assets/
<br/>
├── src/
<br/>
│ └── services/
<br/>
│ └── api.js
<br/>
├── App.js
<br/>
├── app.json
<br/>
├── babel.config.js
<br/>
├── package.json
<br/>
└── package-lock.json

---

## 🤝 Contribuição

1. Faça um fork
2. Crie uma branch de feature: `git checkout -b feature/minha-feature`
3. Commit: `git commit -m "feat: minha feature"`
4. Push: `git push origin feature/minha-feature`
5. Abra um Pull Request

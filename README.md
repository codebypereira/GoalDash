# Goal Dash

Site para **acompanhar partidas de futebol**: jogos ao vivo, histórico, estatísticas de equipas e um sistema de **previsões** de resultados.

## Funcionalidades

- **Início** (`index.html`): jogos em destaque por liga e equipas populares
- **Ao vivo** (`live.html`): partidas em curso
- **Detalhes do jogo** (`matchdetails.html`)
- **Estatísticas** (`stats.html`): desempenho recente das equipas
- **Histórico de previsões** (`history.html`): as tuas previsões guardadas
- Ligas suportadas: Premier League, La Liga, Bundesliga, Serie A, Ligue 1, Champions League, Europa League e Mundial 2026

## Tecnologias

- HTML, CSS e JavaScript puro
- [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- [SportsGameOdds API](https://sportsgameodds.com/) para jogos, resultados e estatísticas
- [MockAPI](https://mockapi.io/) para utilizadores e previsões
- `localStorage` para guardar o nome de utilizador

## Estrutura

```
├── index.html, live.html, matchdetails.html, stats.html, history.html
├── js/
│   ├── api.js     chamadas às APIs e configuração
│   ├── data.js    ligas, equipas populares e logótipos
│   ├── ui.js      renderização da interface
│   └── main.js    lógica principal e eventos
├── styles/        estilos
└── Images/        imagens e favicon
```

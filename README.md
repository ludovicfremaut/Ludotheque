# 🎲 Ludothèque

Application web de gestion de collection de jeux de société avec recherche aléatoire intelligente.

## 🎯 Fonctionnalités

- Affichage de la collection de jeux
- Recherche et filtres (nombre de joueurs, durée, etc.)
- Sélection aléatoire de jeu selon des critères
- Interface responsive et moderne
- Import de données via CSV (MyLudo)

## Technologies

- **Vanilla JavaScript** (ES6+)
- **CSS3** avec variables CSS
- **HTML5** sémantique
- **static-web-server** + **Docker** + **Traefik**

## Utilisation

### Développement local

```bash
docker compose -f docker-compose.local.yml up -d
```

Accédez à l'application sur `http://localhost:8080`

### Production

```bash
docker compose up -d
```

Accédez à l'application sur `https://ludotheque.duckdns.org`

## Licence

MIT © Ludovic F

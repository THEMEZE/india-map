# india-map

# 🎯 Objectif

Créer une **mini-page** web élégante qui affiche ta carte `map.html`
avec un titre, une description et un style professionnel.

# 📁 Structure des fichiers

india-map/
    `index.html`
    `style.css`
    `map.html`        ← ton fichier généré par Folium

# 🧱 1. Fichier `index.html`

```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carte interactive de l'Inde</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <h1>🗺️ Carte interactive de l’Inde</h1>
        <p>Explorez les grandes villes, les routes principales et la densité de population.</p>
    </header>

    <main>
        <!-- Carte Folium intégrée via iframe -->
        <iframe src="map.html" title="Carte de l'Inde"></iframe>
    </main>

    <footer>
        <p>Créé avec ❤️ par Guillaume Thémèze | Données : OpenStreetMap, Folium</p>
    </footer>
</body>
</html>
```

🎨 2. Fichier `style.css``

```css
/* --- Style global --- */
body {
    margin: 0;
    font-family: "Segoe UI", Roboto, sans-serif;
    background-color: #f5f5f5;
    color: #333;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

/* --- En-tête --- */
header {
    background: linear-gradient(135deg, #0078d7, #00b4d8);
    color: white;
    text-align: center;
    padding: 1.5rem 1rem;
    box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}

header h1 {
    margin: 0;
    font-size: 2rem;
}

header p {
    font-size: 1.1rem;
    margin-top: 0.5rem;
}

/* --- Carte --- */
main {
    flex-grow: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 0;
}

iframe {
    width: 90vw;
    height: 80vh;
    border: 2px solid #ccc;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}

/* --- Pied de page --- */
footer {
    background: #222;
    color: #ddd;
    text-align: center;
    padding: 1rem 0;
    font-size: 0.9rem;
}
```

# Mise à jour 

```bach 
git init
git add .
git commit -m "blabla"
git branch -M main
git remote add origin https://github.com/THEMEZE/india-map.git
git push -u origin main
```






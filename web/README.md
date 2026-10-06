# GSB — Application web

Application web en **PHP natif** avec une architecture **MVC** et une base **MySQL**.

## Arborescence

```
web/
├── app/
│   ├── controllers/   # Contrôleurs (logique des pages)
│   ├── models/        # Modèles (accès à la base de données)
│   └── views/         # Vues (HTML/PHP)
├── config/            # Configuration (connexion BDD…)
├── public/            # Point d'entrée (index.php), CSS, JS, images
└── sql/               # Scripts de création et jeu d'essai de la base
```

## Installation

1. Copier `config/config.example.php` en `config/config.php` et renseigner les accès à la base.
2. Importer `sql/` dans MySQL (phpMyAdmin ou ligne de commande).
3. Faire pointer le serveur (WAMP/MAMP/XAMPP) sur `web/public/`.

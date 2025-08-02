# Soutenances-Sys-Pointage-
Projets de soutenances 
pointage-pro/
├── public/
│   ├── index.php              # Page d’accueil (router)
│   ├── assets/                # CSS, JS, images
│   └── .htaccess              # Pour rediriger vers index.php
│
├── app/
│   ├── Controllers/
│   │   ├── HomeController.php
│   │   ├── RetardController.php
│   │   └── AbsenceController.php
│   │
│   ├── Models/
│   │   ├── Employe.php
│   │   ├── Retard.php
│   │   └── Absence.php
│   │
│   ├── Views/
│   │   ├── home.php
│   │   ├── retard.php
│   │   └── absence.php
│   │
│   ├── Routes/
│   │   └── web.php
│   │
│   ├── Middleware/
│   │   └── AuthMiddleware.php
│   │
│   └── Helpers/
│       └── utils.php
│
├── config/
│   ├── database.php
│   └── app.php
│
├── database/
│   └── pointage.sql
│
├── storage/
│   ├── uploads/
│   └── logs/
│
├── README.md
└── .env (optionnel)

# lab-api

---

## 6) Technologies Utilisées

1. **Base de données :** MySQL.
2. **Framework :** Laravel 12.
3. **Architecture :**
   - **Pattern :** MVC avec couche Service (N-Tiers).
   - **Modèles :** `Note`, `Category`, `User`.
   - **Services :** `NoteService`, `CategoryService`, `BaseService`.
   - **Controllers :** Gestion des requêtes/réponses uniquement.

---

## 7) Frontend & Interactivité

1. **Design System :**
   - **Tailwind CSS :** v4.0.0 (via Vite).
   - **Preline UI :** Composants UI modernes.
   - **Lucide :** Bibliothèque d'icônes.
   - **Blade :** Templates et composants serveurs.
2. **Interactivité (AJAX) :**
   - Requêtes asynchrones pour une expérience fluide.
   - Gestion dynamique des modales et formulaires sans rechargement.

---

## 8) Fonctionnalités & Qualité

1. **Gestion des Médias :** Téléchargement et stockage d'images.
2. **Internationalisation (i18n) :** Support FR/EN (`lang/*.json`).
3. **Tests & Qualité :**
   - **Tests Automatisés :** `php artisan test`.
   - **Stratégie :** Utilisation intensive des seeders complets (`UserSeeder`, `CategorySeeder`) pour valider la logique métier.
4. **Conventions :** Code en **Anglais**, respect des standards **PSR**.

---

# Merci pour votre attention !
#### Des questions ?
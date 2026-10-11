# ⚡ AutoClicker Pro

![Version](https://img.shields.io/badge/version-2.4-blue)
![Platform](https://img.shields.io/badge/platform-Windows-0078D6)

**Autoclicker Windows moderne** avec **détection d'image**, **retour caméra automatique** et **29 thèmes animés**.

Compatible avec **tous les jeux et applications** : Fortnite, Minecraft, Roblox, navigateurs, bureautique…

---

## ✨ Fonctionnalités

### 🖱️ Modes de clic
- **Simple** — clic à la position actuelle de la souris
- **Continu** — maintient le bouton appuyé (style Fortnite)
- **Multi-clic** — Double, Triple ou jusqu'à 100 clics par cycle

### 🎯 Détection d'image
- Capture une zone de l'écran
- L'appli **retrouve cette zone automatiquement** à chaque frame
- **Retour caméra auto** (horizontal + vertical) si la cible disparaît
- Anti-rebond configurable

### 🛡️ Anti-ban intégré
- Jitter aléatoire sur chaque clic (3 px)
- Variation dynamique des intervalles (comportement humain)
- Pauses humaines aléatoires
- **Non désactivable** (protection)

### 🎨 29 thèmes + effets animés
- Matrix, Minecraft, Pokémon, Cyberpunk, Fortnite, Zelda, Among Us, Doom…
- Effets : pluie de caractères, feuilles qui tombent, orbes, fées, braises…
- Thème Pokémon avec **tes propres sprites PNG**

### ⚙️ Interface
- Overlay CPS flottant
- Hotkeys personnalisables (F6/F7 par défaut)
- Système tray (minimiser dans la barre système)
- Sauvegarde automatique des profils
- Logs + backups automatiques

### 🔄 Auto-update
- Détecte les nouvelles versions au lancement
- Téléchargement + installation en 1 clic

---

## 🚀 Installation

1. Va dans [**Releases**](../../releases)
2. Télécharge `AutoClickerPro.exe`
3. Place-le où tu veux (Bureau, Documents…)
4. **Double-clic** → l'appli s'ouvre
5. Au 1er lancement : Windows peut demander *« Exécuter quand même »* → clique dessus
6. UAC : clique **Oui**

**Aucune installation requise.** Python, OpenCV et toutes les dépendances sont embarqués.

---

## 🎮 Utilisation rapide

| Touche | Action |
|---|---|
| **F6** | Démarrer / Arrêter |
| **F7** | Quitter complètement |

### Mode Simple
1. Onglet **Simple**
2. Choisis ton type de clic (Gauche / Droit / Continu)
3. F6 → ça clique à la position actuelle de la souris

### Mode Détection d'image
1. Onglet **🎯 Image**
2. Clique **Capturer la cible** → sélectionne la zone dans le jeu
3. F6 → l'appli retrouve la cible automatiquement

---

## 🖼️ Pokémons personnalisés

Pour afficher tes propres Pokémons en fond d'écran avec le thème **Pokémon** :

1. Crée un dossier `pokemon` à côté de `AutoClickerPro.exe`
2. Mets-y tes images **PNG** (fond transparent recommandé, 100 à 300 px)
3. Lance l'appli → Thème → **Pokémon**

Structure :

```text
AutoClicker/
├── AutoClickerPro.exe
└── pokemon/
    ├── pikachu.png
    ├── charmander.png
    └── ...
```
---

## ⚠️ Avertissement

Cet outil est un autoclicker classique. **Utilise-le de manière responsable.**

Certains jeux avec anti-cheat kernel (Valorant, FiveM, etc.) peuvent bloquer les entrées synthétiques — ce n'est pas un bug, c'est leur système de protection.

**L'utilisation d'autoclickers dans certains jeux en ligne peut entraîner des sanctions.** Tu es seul responsable de l'usage que tu en fais.

---

## 🐛 Signaler un bug

Ouvre une [**Issue**](../../issues) avec :
- Ta version de Windows
- La version de l'appli (visible dans Réglages → Mises à jour)
- Une description précise du problème
- Le fichier `%APPDATA%\AutoClickerPro\autoclicker.log` si possible

---

## 📁 Fichiers de configuration

Tout est stocké dans :

```text
%APPDATA%\AutoClickerPro\
├── profiles.json         ← tes profils
├── settings.json         ← réglages généraux
├── stats.json            ← statistiques
├── autoclicker.log       ← logs
└── target_template.png   ← cible image
```

---

## ⭐ Soutiens le projet

Si l'appli te plaît :
- ⭐ Mets une **étoile** sur ce repo
- 🐛 Signale les **bugs** que tu trouves
- 💡 Propose des **idées** d'amélioration

---

**© 2026 AmbTAlpha — Tous droits réservés.**

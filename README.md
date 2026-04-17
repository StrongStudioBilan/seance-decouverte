# StrongStudio — Page Bilan Offert

Page de capture tunnel Meta Ads → Bilan offert → Coaching privé.

## Structure du dossier

```
strongstudio-bilan/
├── index.html              # La page complète (tout-en-un : HTML + CSS + JS inline)
├── _PRO1584-Modifier.jpg   # Hero background (coaching kettlebell)
├── _PRO1614-Modifier.jpg   # Break humain (sourire)
├── _PRO1646-Modifier.jpg   # Section problème (squat goblet)
├── _PRO1657-Modifier.jpg   # Bloc "Une fois commencé" (barre de traction)
├── _PRO1686-Modifier.jpg   # Galerie studio (coaching mobilité)
├── _PRO1687-Modifier.jpg   # Final CTA background (deadlift)
├── image00009.jpeg         # Photo du studio (section Nous trouver)
├── 555725458...jpg         # Grille des transformations clientes
├── cover-cadeau.jpg        # (réserve)
├── MAR0016.jpg             # (réserve - certif StrongFirst)
└── README.md               # Ce fichier
```

## Déploiement sur GitHub Pages

### Option A — Nouveau repo dédié

1. Créer un nouveau repo GitHub (ex : `bilan-strongstudio`)
2. Uploader tous les fichiers du dossier à la racine
3. Settings → Pages → Source : `main` branch, folder `/ (root)`
4. URL finale : `https://strongstudiobilan.github.io/bilan-strongstudio/`

### Option B — Remplacer la page actuelle

Si tu veux remplacer directement `https://strongstudiobilan.github.io/seance-decouverte/` :

1. Va sur le repo `strongstudiobilan.github.io` (ou le repo qui héberge `/seance-decouverte/`)
2. Dans le dossier `seance-decouverte/`, **remplace tous les fichiers** par ceux de ce dossier
3. Commit & push
4. La nouvelle page sera en ligne en 1-2 minutes

## Ce qui est déjà branché

### ✅ Pixel Meta (Facebook)
- ID : `1152376082444766` (le même que ta page actuelle)
- Événements trackés : `PageView`, `Lead` (ouverture modal), `CompleteRegistration` (envoi form)

### ✅ Formulaire Learnybox
- URL : `https://martini-pierre-antoine.learnybox.com/form/68fe551408f04mz2ijkrjtotubb48n5mms/`
- Champs : prénom, email, téléphone, checkbox RGPD
- Envoi en AJAX sans rechargement
- Confirmation inline avec le message "vérifiez vos spams"

### ✅ CTA sticky mobile
- S'affiche sur écrans < 640px
- Toujours visible pour maximiser les conversions mobiles

### ✅ Popup de réservation
- S'ouvre depuis tous les boutons "Réserver"
- Fermeture : croix, clic hors modale, touche Escape
- Transition fluide form → confirmation

## Ce qui reste à faire (phase 2)

- [ ] Intégrer les témoignages vidéos (Rose, Fatia, Laurent, Lu-Anna)
- [ ] Ajouter JSON-LD schema LocalBusiness pour SEO local
- [ ] A/B test hero conservative vs hero "déjà essayé" plus directif
- [ ] Suivi Google Analytics 4 si souhaité
- [ ] Email séquence post-réservation (confirmation + rappel J-1)

## Notes techniques

- **100% statique** : aucune dépendance, aucune build step
- **Compatible GitHub Pages** (aucun serveur requis)
- **Responsive** : mobile-first, breakpoints à 640px / 768px / 960px
- **Accessible** : contraste AA, navigation clavier, aria-labels
- **Performance** : fonts préchargées, images optimisables à passer en WebP si besoin

## Charte graphique

| Couleur | Code | Usage |
|---------|------|-------|
| Fond | `#0D1B2A` | Background principal |
| Fond alt | `#0a1521` | Sections alternées |
| Cards | `#122536` | Cartes contenus |
| Or | `#E8C547` | Accents, CTA, titres accentués |
| Texte | `#EAEEF2` | Corps de texte |
| Texte dim | `#A8B4BF` | Sous-titres, légendes |

**Typographie** : Bebas Neue (display) + DM Sans (body), via Google Fonts.

---

Construit en collaboration stratégique avec Claude. Pour toute question sur la structure ou les ajustements à faire, reprendre la conversation.

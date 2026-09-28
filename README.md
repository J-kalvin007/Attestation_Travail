# 📄 Attestation de Travail — La Régale (Documentation Technique & Guide Design System)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/CSS)
[![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://fonts.google.com/)
[![Format A4](https://img.shields.io/badge/Format-A4_210x297mm-green?style=for-the-badge)](#)
[![Print Ready](https://img.shields.io/badge/Print-Ready_PDF-purple?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-Propriétaire-red?style=for-the-badge)](#)

---

## 📋 Table des Matières

1. [📌 Présentation du Projet & Cas d'Usage](#-présentation-du-projet--cas-dusage)
2. [✳️ Fonctionnalités Clés & Spécifications Design](#-fonctionnalités-clés--spécifications-design)
3. [🛠 Ecosysteme & Stack Technologique](#-ecosysteme--stack-technologique)
4. [📁 Structure Complète du Projet](#-structure-complète-du-projet)
5. [🔍 Analyse Détaillée des Fichiers & Modèles HTML](#-analyse-détaillée-des-fichiers--modèles-html)
   - [1. Modèle Principal Officiel (`index.html`)](#1-modèle-principal-officiel-indexhtml)
   - [2. Modèle Épuré / Simplifié (`doc.html`)](#2-modèle-épuré--simplifié-dochtml)
   - [3. Modèle Design Premium (`images/test.html`)](#3-modèle-design-premium-imagestesthtml)
   - [4. Assets Graphiques & Ressources (`images/`)](#4-assets-graphiques--ressources-images)
6. [🎨 Design System & Variables CSS](#-design-system--variables-css)
7. [🖨️ Guide d'Exportation PDF & Impression HD](#-guide-dexportation-pdf--impression-hd)
8. [🛠️ Guide de Personnalisation & Évolutivité](#-guide-de-personnalisation--évolutivité)
9. [❓ Dépannage & FAQ](#-dépannage--faq)

---

## 📌 Présentation du Projet & Cas d me d'Usage

Ce projet regroupe une suite de gabarits **HTML5 / CSS3 ultra-précis et print-ready** conçus spécifiquement pour la génération et l'impression d'**Attestations de Travail** officielles et haut de gamme pour l'établissement gastronomique **Restaurant La Régale** (Lomé, Togo).

Chaque document est élaboré pour respecter à la lettre le format strict **A4 (210mm x 297mm)**, en intégrant une typographie de prestige (*Cormorant Garamond*, *Montserrat*, *Playfair Display*), un filigrane de sécurité vectorisé, des bordures géométriques personnalisées, des bandes chromatiques raffinées et un bloc de signature officiel.

L'objectif principal est d'assurer une restitution visuelle irréprochable aussi bien à l'écran lors du contrôle administratif que lors de l'exportation au format **PDF HD** ou de l'impression physique.

---

## ✨ Fonctionnalités Clés & Spécifications Design

- 📏 **Dimensions A4 Millimétrées** : Gabarit calibré au millimètre près (`width: 210mm`, `height: 297mm`, `overflow: hidden`) empêchant tout débordement indésirable sur une seconde page.
- 🖨️ **Rendu Impression "Print-Ready"** : Directives CSS3 `@media print` avec forçage de l'impression des couleurs et graphiques d'arrière-plan (`-webkit-print-color-adjust: exact`).
- 💎 **Typographie Haute Couture** :
  - **Cormorant Garamond** & **Playfair Display** : Polices sérif pour les en-têtes majeurs, titres et nom du bénéficiaire.
  - **Montserrat** : Police sans-sérif moderne garantissant une lisibilité maximale des pavés de texte légaux et des coordonnées.
- 🎨 **Palette Chromatique Signée** : Thème personnalisé associant des teintes nudes/rosées élégantes (`#E59696`, `#C97070`) à un encre sombre profond (`#18243A`).
- 🛡️ **Attributs de Sécurité & Filigrane** : Filigrane d'arrière-plan en opacité réduite (`logo_laregale.jpeg`), encadrements à coins ornés pour le nom du bénéficiaire et zone réservée au cachet officiel.
- 📑 **Architecture Multi-Variantes** : 3 déclinaisons de mise en page (`index.html`, `doc.html`, `images/test.html`) répondant à des besoins visuels variés.

---

## 🛠 Ecosysteme & Stack Technologique

| Composant | Technologie | Description |
| :--- | :--- | :--- |
| **Structure** | **HTML5 Semantic** | Balisage sémantique (`<header>`, `<main>`, `<section>`, `<footer>`, `<aside>`) |
| **Stylisation** | **CSS3 Native** | Flexbox, CSS Grid, Variables CSS (`:root`), Pseudo-éléments (`::before`, `::after`) |
| **Polices** | **Google Fonts** | Importation dynamique de `Cormorant Garamond`, `Montserrat`, `Playfair Display` |
| **Impression** | **CSS Media Queries** | Directives `@media print` pour la mise en page lors de l'impression et de la conversion PDF |
| **Assets** | **PNG & JPEG** | Logotype vectorisé haute définition (`logo.png`) & texture filigrane (`logo_laregale.jpeg`) |

---

## 📁 Structure Complète du Projet

```text
Attestation_Travail/
├── doc.html                    # Modèle 2 : Variant Épuré / Minimaliste (7.9 KB - 236 L)
├── index.html                  # Modèle 1 : Standard Officiel La Régale (27.3 KB - 823 L)
├── README.md                   # Documentation Officielle & Spécifications Design System
└── images/                     # Dossier des Ressources Graphiques
    ├── logo.png                # Logo officiel transparent du Restaurant La Régale (119.9 KB)
    ├── logo_laregale.jpeg      # Asset graphique utilisé pour le filigrane d'arrière-plan (124.1 KB)
    └── test.html               # Modèle 3 : Variant Premium avec Badges & Triple Bandes (18.9 KB - 618 L)
```

---

## 🔍 Analyse Détaillée des Fichiers & Modèles HTML

### 1. Modèle Principal Officiel ([`index.html`](file:///d:/Travaux_Moise/optimisation/Attestation_Travail/index.html))

**Rôle** : Document de référence complet, le plus élaboré, utilisé pour l'émission des attestations de travail officielles.

#### Extraits de Code & Architecture CSS Majeure :

```css
/* Variables Chromatiques Racine */
:root {
    --rose: #E59696;
    --rose-deep: #C97070;
    --rose-pale: #F7E8E8;
    --rose-muted: #f0d5d5;
    --ink: #18243A;
    --ink-medium: #344357;
    --ink-light: #5D6E85;
    --ink-ghost: #9AAABB;
    --divider: #DDE4EE;
    --surface-alt: #F8F9FC;
    --white: #FFFFFF;
}

/* Format A4 Stricte */
.page {
    background: var(--white);
    width: 210mm;
    height: 297mm;
    margin: 0 auto;
    position: relative;
    display: flex;
    flex-direction: column;
    overflow: hidden;
    box-shadow: 0 2px 4px rgba(0,0,0,0.07), 0 8px 28px rgba(0,0,0,0.13);
}
```

#### Points Forts du Code `index.html` :
- **Barres Latérales & Bandes Horizontales** : Utilisation des pseudo-éléments `.page::before` et `.page::after` pour afficher des bordures latérales verticales dégradées de 5px.
- **Header Multi-Colonnes** : Disposé en grid (`grid-template-columns: auto auto 1fr auto`) combinant le logo principal (`images/logo.png`), un séparateur dégradé vertical et l'ensemble des coordonnées légales de l'entreprise (NIF `1001534263`, CNSS `90621`, BP `30708`, Téléphone `+228 92 46 92 16`).
- **Encadré Bénéficiaire Stylisé** : Encadrement central avec des coins renforcés via `.c-tr` et `.c-bl` mettant en valeur le nom du bénéficiaire **M. NOMEUMEU TAKOUDJOU Moise Calvin**.
- **Bloc des Missions Informatiques** : Section `.mission-block` bordée à gauche d'un liseré ambré/rosé avec des puces personnalisées `›`.
- **Zone de Signature & Cachet** : Pied de page intégrant la date d'émission (*Fait à Lomé, le 07 février 2025*), la qualité de la signataire (*Directrice Générale - BAITE A. Justine*) et un emplacement en pointillés `.stamp-zone` réservé au tampon physique.

---

### 2. Modèle Épuré / Simplifié ([`doc.html`](file:///d:/Travaux_Moise/optimisation/Attestation_Travail/doc.html))

**Rôle** : Version légère du document, idéale pour les impressions rapides ou les formats d'attestations simplifiées.

#### Spécificités Techniques :
- Utilisation de la police sérif **Playfair Display** pour le titre et les sous-titres.
- Encadrement graphique basé sur des bordures solides de 8px en haut et en bas (`border-top: 8px solid var(--rose-signature)`).
- Filigrane configuré à une opacité très douce de `0.05`.
- Zone de signature classique avec liseré en pointillés horizontaux pour marquer le cachet.

---

### 3. Modèle Design Premium ([`images/test.html`](file:///d:/Travaux_Moise/optimisation/Attestation_Travail/images/test.html))

**Rôle** : Modèle alternatif haut de gamme avec habillage géométrique moderne et éléments administratifs enrichis.

#### Spécificités Techniques :
- **Bandes Décoratives Triples** : `.top-band` et `.bottom-band` composées de 3 sous-couches chromatiques (`.band-primary`, `.band-secondary`, `.band-accent`).
- **Badge de Référence Administrati** : Inclusion du badge `.ref-badge` (*Réf. : ATT-2025/03 | Document officiel*).
- **Encadré Bénéficiaire 4 Coins** : Encadrement à quatre pièces d'angle distinctes (`.recipient-corner.tl`, `.tr`, `.bl`, `.br`).
- **Pied de Page avec Mention Légale** : Zone de réserve juridique en bas à gauche et case de signature avec zone de tampon fermée.

---

### 4. Assets Graphiques & Ressources (`images/`)

- [`images/logo.png`](file:///d:/Travaux_Moise/optimisation/Attestation_Travail/images/logo.png) : Logo haute résolution sur fond transparent du Restaurant La Régale.
- [`images/logo_laregale.jpeg`](file:///d:/Travaux_Moise/optimisation/Attestation_Travail/images/logo_laregale.jpeg) : Image de marque utilisée en filigrane central (`watermark`).

---

## 🎨 Design System & Variables CSS

### Charte Chromatique Officielle

| Nom de Variable | Code Hex / Value | Usage & Application Visuelle |
| :--- | :--- | :--- |
| `--rose` / `--rose-signature` | `#E59696` | Couleur primaire d'accentuation, bordures & puces |
| `--rose-deep` | `#C97070` | Dégradés, sous-titres & ornements contrastés |
| `--rose-pale` / `--rose-muted` | `#F7E8E8` / `#F0D5D5` | Arrière-plans de badges & liserés secondaires |
| `--ink` / `--texte-sombre` | `#18243A` / `#1A2535` | Titres majeurs, nom du bénéficiaire & texte fort |
| `--ink-medium` | `#344357` | Corps de texte principal & listes de puces |
| `--ink-light` / `--ink-ghost` | `#5D6E85` / `#9AAABB` | Textes légaux, références, séparateurs & filigranes |
| `--surface-alt` | `#F8F9FC` | Arrière-plan des blocs de référence et zones de tampon |

### Règles Typographiques

```css
/* Titres majeurs & Noms officiels */
font-family: 'Cormorant Garamond', 'Playfair Display', serif;

/* Corps de texte, Coordonnées & Mentions */
font-family: 'Montserrat', sans-serif;
```

---

## 🖨️ Guide d'Exportation PDF & Impression HD

Pour obtenir un document PDF ou une impression papier d'une qualité parfaite sans aucun décalage :

1. **Ouvrir le fichier HTML** :
   Ouvrez [`index.html`](file:///d:/Travaux_Moise/optimisation/Attestation_Travail/index.html) (ou la variante souhaitée) dans **Google Chrome**, **Microsoft Edge** ou **Mozilla Firefox**.

2. **Lancer le dialogue d'impression** :
   Appuyez sur `Ctrl + P` (sur Windows) ou `Cmd + P` (sur macOS).

3. **Configurer les paramètres d'impression** :
   - **Destination** : `Enregistrer au format PDF` (ou votre imprimante physique).
   - **Format de papier** : `A4`.
   - **Orientation** : `Portrait`.
   - **Marges** : `Aucun` (ou `Par défaut`).
   - **Options d'arrière-plan** : **Cochez impérativement "Graphiques d'arrière-plan"** (*Background graphics*). Ce réglage est indispensable pour afficher le filigrane et les bandes de couleur.
   - **Échelle** : `100%` (ou *Ajuster à la zone d'impression*).

4. **Exporter** :
   Cliquez sur **Enregistrer** et nommez le fichier (ex: `Attestation_Travail_TAKOUDJOU_Moise.pdf`).

---

## 🛠️ Guide de Personnalisation & Évolutivité

### 1. Modifier le Nom du Bénéficiaire & les Dates
Dans [`index.html`](file:///d:/Travaux_Moise/optimisation/Attestation_Travail/index.html), localisez le bloc `.beneficiary` et le paragraphe du corps :

```html
<!-- Modification du nom du bénéficiaire -->
<div class="beneficiary">
    <strong class="beneficiary-name">M. NOMEUMEU TAKOUDJOU Moise Calvin</strong>
</div>

<!-- Modification des dates et du poste -->
<p>
    A été employé au sein de notre établissement en qualité de
    <strong>Responsable Informatique</strong>, et y a exercé ses fonctions du
    <strong>1<sup>er</sup> novembre 2023</strong> au <strong>31 janvier 2025</strong>.
</p>
```

### 2. Modifier la Liste des Missions
Mettez à jour la liste à puces dans l'élément `<div class="mission-block">` :

```html
<div class="mission-block">
    <ul>
        <li>
            <strong>Nouvelle Mission :</strong> Description détaillée de la tâche réalisée.
        </li>
    </ul>
</div>
```

---

## ❓ Dépannage & FAQ

#### Q1 : Le document s'imprime sur 2 pages au lieu d'une seule
👉 **Solution** : Dans les options d'impression de votre navigateur, assurez-vous que les **Marges** sont définies sur `Aucun`. Si le problème persiste, réduisez légèrement l'échelle d'impression (ex: `98%`).

#### Q2 : Le filigrane ou les bandes de couleur n'apparaissent pas sur le PDF
👉 **Solution** : Vous devez **cocher la case "Graphiques d'arrière-plan"** (*Background graphics*) dans le panneau des options avancées d'impression de votre navigateur.

---


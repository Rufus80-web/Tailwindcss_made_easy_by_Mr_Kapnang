# English 

# Student Exercise — Making a Page Responsive with Tailwind CSS

> I built this admin dashboard intentionally **without responsive design**.  
> Your task is to add Tailwind responsive prefixes (`sm:`, `md:`, `lg:`, `xl:`) to make the layout adapt properly to all screen sizes.

---

## Tasks

### 1. Sidebar
- **On mobile:** hide the sidebar — it should collapse or be replaced by a top navigation bar.
- **On large screens:** show the sidebar at a fixed width.

### 2. Main Content Area
- **On mobile:** take full width (no sidebar offset).
- **On large screens:** sit next to the sidebar.

### 3. Stats Cards *(the 4 metric cards)*
- **On mobile:** stack them in a single column.
- **On medium screens:** show 2 per row.
- **On large screens:** show all 4 in one row.

### 4. Bottom Section *(Table + Activity Feed)*
- **On mobile:** stack them vertically.
- **On large screens:** place them side by side.

### 5. Header
- **On mobile:** simplify — hide the search bar or make it full width. Stack the user info if needed.

### 6. Typography & Spacing
- Reduce font sizes and padding on smaller screens where things feel cramped.

---

## Hints

**Tailwind responsive prefixes** work like this:

```html
class="w-full lg:w-64"
```
> Means: full width by default, `16rem` wide on large screens.

| Goal | Class to use |
|---|---|
| Hide on mobile, show on large screens | `hidden lg:block` |
| Show on mobile, hide on large screens | `block lg:hidden` |

**Tailwind breakpoints:**

| Prefix | Min-width |
|---|---|
| `sm:` | 640px |
| `md:` | 768px |
| `lg:` | 1024px |
| `xl:` | 1280px |

---

## Bonus Challenges

- [ ] Add a **hamburger menu button** (visible only on mobile) that toggles the sidebar open/closed using JavaScript.
- [ ] Make the **table horizontally scrollable** on mobile using `overflow-x-auto` on a wrapper `div`.
- [ ] Add a **mobile bottom navigation bar** as an alternative to the sidebar on small screens.


## French

# Exercice Étudiant — Rendre une page responsive avec Tailwind CSS

>J'ai intentionnellement conçu ee tableau de bord admin  **sans design responsive**.  
> Votre mission est d'ajouter les préfixes responsive de Tailwind (`sm:`, `md:`, `lg:`, `xl:`) pour que la mise en page s'adapte correctement à toutes les tailles d'écran.

---

## Tâches

### 1. Barre latérale *(Sidebar)*
- **Sur mobile :** masquer la barre latérale — elle doit se replier ou être remplacée par une barre de navigation en haut de page.
- **Sur grand écran :** afficher la barre latérale à une largeur fixe.

### 2. Zone de contenu principal
- **Sur mobile :** occuper toute la largeur (sans décalage lié à la sidebar).
- **Sur grand écran :** se placer à côté de la barre latérale.

### 3. Cartes de statistiques *(les 4 cartes de métriques)*
- **Sur mobile :** les empiler en une seule colonne.
- **Sur écran moyen :** afficher 2 cartes par ligne.
- **Sur grand écran :** afficher les 4 cartes sur une seule ligne.

### 4. Section du bas *(Tableau + Fil d'activité)*
- **Sur mobile :** les empiler verticalement.
- **Sur grand écran :** les placer côte à côte.

### 5. En-tête *(Header)*
- **Sur mobile :** simplifier — masquer la barre de recherche ou la mettre en pleine largeur. Empiler les informations utilisateur si nécessaire.

### 6. Typographie & Espacement
- Réduire les tailles de police et les espacements sur les petits écrans pour éviter que l'interface soit trop à l'étroit.

---

## Astuces

Les **préfixes responsive de Tailwind** fonctionnent comme ceci :

```html
class="w-full lg:w-64"
```
> Signifie : pleine largeur par défaut, `16rem` de large sur les grands écrans.

| Objectif | Classe à utiliser |
|---|---|
| Masquer sur mobile, afficher sur grand écran | `hidden lg:block` |
| Afficher sur mobile, masquer sur grand écran | `block lg:hidden` |

**Points de rupture Tailwind :**

| Préfixe | Largeur minimale |
|---|---|
| `sm:` | 640px |
| `md:` | 768px |
| `lg:` | 1024px |
| `xl:` | 1280px |

---

## Défis Bonus

- [ ] Ajouter un **bouton menu hamburger** (visible uniquement sur mobile) qui ouvre/ferme la barre latérale en JavaScript.
- [ ] Rendre le **tableau défilable horizontalement** sur mobile en utilisant `overflow-x-auto` sur une `div` englobante.
- [ ] Ajouter une **barre de navigation mobile en bas de page** comme alternative à la barre latérale sur les petits écrans.
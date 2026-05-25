# Cahier des charges — Boutique en ligne Mielido

## 1. Présentation du projet

Le projet consiste à créer une boutique en ligne professionnelle pour **Mielido**, marque de miel de **Al’Fat Entreprise**.

La boutique doit présenter la marque, valoriser la gamme de produits, afficher les prix, permettre la commande via WhatsApp et générer des demandes revendeur.

## 2. Objectifs

### Objectif principal

Vendre les produits Mielido en ligne grâce à une boutique claire, premium, rapide et facile à utiliser.

### Objectifs secondaires

- Renforcer l’image de marque Mielido.
- Valoriser Al’Fat Entreprise comme entreprise porteuse.
- Rendre la gamme facile à comprendre.
- Simplifier la commande via WhatsApp.
- Structurer les demandes revendeur.
- Préparer une évolution vers paiement mobile et suivi de commandes.

## 3. Cibles

### Client particulier

Profil : familles, actifs, consommateurs de thé, yaourts, petit-déjeuner, cuisine maison, personnes recherchant un produit local présenté de façon premium.

Besoins : acheter rapidement, comprendre les formats, connaître les prix, commander facilement.

### Revendeur

Profil : boutiques, mini-marchés, épiceries, vendeurs en ligne, revendeurs alimentaires, partenaires de distribution.

Besoins : prix revendeur, minimum de commande, contacts rapides, présentation claire de la gamme.

### Entreprise / cadeau

Profil : organisations, particuliers ou commerces souhaitant offrir des produits gourmands.

Besoins : commande en quantité, présentation professionnelle, contact direct.

## 4. Identité de marque

- Marque : **Mielido**
- Entreprise : **Al’Fat Entreprise**
- Signature : **L’Or de la nature, pur & authentique**
- Univers : miel, abeille, goutte dorée, alvéoles, naturel, premium, ivoire, prune et or.

## 5. Catalogue produit

| Format | SKU | Nom du produit | Prix public conseillé | Prix revendeur dès 12 unités | Usage recommandé |
|---|---|---:|---:|---:|---|
| 0,25 L | `MIELIDO-MINI-025` | Mielido Mini Squeeze | **2 000 FCFA** | **1 600 FCFA** | format découverte, bureau, sac, petit-déjeuner |
| 0,5 L | `MIELIDO-CLASSIC-050` | Mielido Classic Squeeze | **3 500 FCFA** | **3 000 FCFA** | usage quotidien, thé, tartines, yaourts |
| 1 L | `MIELIDO-FAMILY-100` | Mielido Family Squeeze | **6 000 FCFA** | **5 200 FCFA** | famille, cuisine, consommation régulière |
| 1,5 L | `MIELIDO-MAXI-150` | Mielido Maxi Squeeze avec poignée | **8 500 FCFA** | **7 500 FCFA** | grande famille, restaurant, revendeur, cuisine |

## 6. Fonctionnalités attendues

### 6.1 Page d’accueil

- Header responsive.
- Hero section premium.
- Présentation rapide de la marque.
- CTA vers commande WhatsApp.
- Mise en avant de la gamme.
- Bloc de confiance.
- Section usages.
- Section revendeur.
- FAQ courte.
- Contact final.

### 6.2 Catalogue produits

Pour chaque produit :

- format ;
- nom commercial ;
- prix public ;
- prix revendeur ;
- description courte ;
- image ;
- quantité ;
- ajout au panier ;
- commande directe WhatsApp.

### 6.3 Panier simple

Le panier doit :

- lister les produits sélectionnés ;
- permettre la modification des quantités ;
- calculer le total ;
- supprimer un produit ;
- demander les informations client ;
- générer un message WhatsApp complet.

### 6.4 Formulaire de commande

Champs recommandés :

- nom complet ;
- téléphone / WhatsApp ;
- commune / quartier ;
- produit souhaité ;
- quantité ;
- message ;
- préférence de livraison.

### 6.5 Formulaire revendeur

Champs recommandés :

- nom complet ;
- téléphone WhatsApp ;
- nom de la boutique ;
- ville / commune ;
- formats souhaités ;
- quantité estimée ;
- message.

### 6.6 WhatsApp

Tous les boutons de commande doivent ouvrir WhatsApp avec un message pré-rempli.

Liens à utiliser :

- `https://wa.me/2250504498899`
- `https://wa.me/2250778285271`
- `https://wa.me/2250574540805`

### 6.7 Administration future

Prévoir une structure qui pourra évoluer vers :

- ajout/modification de produits ;
- gestion des prix ;
- gestion des commandes ;
- export Excel ;
- suivi livraison ;
- suivi clients ;
- tableau de bord ventes.

## 7. Arborescence recommandée

```text
Accueil
├── Boutique
│   ├── Mielido Mini Squeeze 0,25 L
│   ├── Mielido Classic Squeeze 0,5 L
│   ├── Mielido Family Squeeze 1 L
│   └── Mielido Maxi Squeeze 1,5 L
├── Revendeurs
├── À propos
├── FAQ
└── Contact
```

## 8. Design et UI

### Couleurs

| Couleur | Code |
|---|---:|
| Prune Royal | `#27123D` |
| Prune Profond | `#4B1D6D` |
| Or Miel | `#D4A017` |
| Miel Ambré | `#F2C46D` |
| Ivoire Chaud | `#FFF6E6` |
| Beige Naturel | `#EADDC7` |

### Typographies

- Titres : Playfair Display.
- Textes : Montserrat.

### Composants UI

- Cartes produits premium.
- Boutons dorés contrastés.
- Badges de format.
- Tableaux de prix lisibles.
- Motifs alvéoles subtils.
- Pictogrammes abeille/goutte.
- Footer riche.

## 9. Règles responsive

- Mobile-first.
- Panier facile à utiliser sur téléphone.
- Boutons larges.
- Prix visibles.
- Formulaires courts.
- Images compressées.
- Menu hamburger.
- CTA WhatsApp sticky possible.

## 10. Règles SEO

### Mots-clés à viser

- miel naturel Côte d’Ivoire ;
- miel à Abidjan ;
- miel pour thé ;
- miel pour petit-déjeuner ;
- boutique miel Abidjan ;
- Mielido ;
- Al’Fat Entreprise ;
- miel premium ;
- miel en bouteille squeeze.

### Éléments à intégrer

- titres H1/H2 propres ;
- meta title ;
- meta description ;
- alt text sur les images ;
- données structurées produit ;
- URLs simples ;
- temps de chargement rapide.

## 11. Règles juridiques et confiance

Prévoir :

- mentions de contact ;
- politique de confidentialité simple ;
- conditions de commande ;
- informations de livraison ;
- moyen de contact client ;
- avertissement contre les allégations médicales non justifiées.

Ne pas écrire que le produit guérit, soigne ou remplace un traitement.

## 12. Automatisation recommandée

Données à enregistrer dans un fichier de suivi :

- date ;
- nom client ;
- téléphone ;
- commune ;
- produits commandés ;
- quantité ;
- total ;
- statut ;
- source ;
- remarques.

Outils possibles :

- Google Sheets ;
- Airtable ;
- Notion ;
- n8n ;
- Make ;
- CRM simple.

## 13. Critères d’acceptation

La boutique sera considérée comme conforme si :

- la charte graphique est respectée ;
- les 4 produits sont présents ;
- les prix sont exacts ;
- les boutons WhatsApp fonctionnent ;
- le panier calcule les totaux ;
- le site est lisible sur mobile ;
- les textes sont professionnels ;
- aucun prix non fourni n’est inventé ;
- aucune promesse médicale n’est faite ;
- la section revendeur est disponible ;
- les images sont optimisées ;
- le site inspire confiance rapidement.

## 14. Livrables attendus

- Boutique responsive.
- Page d’accueil.
- Catalogue produits.
- Panier simple.
- Page/section revendeur.
- Formulaire contact.
- FAQ.
- Footer complet.
- Textes SEO.
- Workflow de commande WhatsApp.
- Documentation courte pour modifier produits et prix.

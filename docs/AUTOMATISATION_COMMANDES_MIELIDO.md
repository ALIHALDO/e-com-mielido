# Automatisation des commandes Mielido

## 1. Objectif

Mettre en place un workflow simple pour transformer les visiteurs de la boutique en commandes suivies.

La priorité est de connecter :

- boutique en ligne ;
- formulaire ;
- panier ;
- WhatsApp Business ;
- fichier de suivi ;
- relance client ;
- suivi revendeur.

## 2. Parcours client recommandé

```text
Visiteur
→ Consulte la boutique
→ Choisit un format
→ Ajoute au panier
→ Renseigne nom + téléphone + commune
→ Clique sur Commander sur WhatsApp
→ Message pré-rempli envoyé
→ Équipe Mielido confirme disponibilité / livraison / paiement
→ Commande enregistrée dans le fichier de suivi
→ Livraison ou retrait
→ Relance avis client
```

## 3. Parcours revendeur

```text
Revendeur potentiel
→ Consulte la section Revendeurs
→ Voit les prix dès 12 unités
→ Remplit le formulaire ou clique WhatsApp
→ Données enregistrées
→ Équipe Mielido contacte le revendeur
→ Proposition de commande
→ Suivi commercial
```

## 4. Fichier de suivi recommandé

Créer un fichier Google Sheets, Airtable ou Notion avec les colonnes suivantes :

| Colonne | Description |
|---|---|
| Date | Date de la demande |
| Source | Site, WhatsApp, TikTok, Instagram, Facebook |
| Type | Particulier, revendeur, entreprise |
| Nom client | Nom du prospect/client |
| Téléphone | Numéro WhatsApp |
| Commune / quartier | Zone de livraison |
| Produit | Produit commandé |
| Format | 0,25 L, 0,5 L, 1 L, 1,5 L |
| Quantité | Nombre d’unités |
| Prix unitaire | Prix public ou revendeur |
| Total estimé | Total de la commande |
| Statut | Nouveau, confirmé, livré, annulé, relance |
| Moyen de paiement | À confirmer, cash, mobile money, autre |
| Responsable | Personne qui suit la commande |
| Remarques | Notes utiles |

## 5. Statuts de commande

Statuts recommandés :

- Nouveau ;
- Contacté ;
- En attente confirmation ;
- Confirmé ;
- En préparation ;
- En livraison ;
- Livré ;
- Annulé ;
- Relance ;
- Revendeur à suivre.

## 6. Messages automatiques recommandés

### Après commande

```text
Bonjour [Nom], merci pour votre commande Mielido 🍯
Nous avons bien reçu votre demande : [détail commande].
Un membre de l’équipe vous confirme rapidement la disponibilité et les modalités de livraison.
```

### Confirmation de disponibilité

```text
Bonjour [Nom], votre commande Mielido est disponible.
Total : [montant] FCFA.
Zone : [commune/quartier].
Merci de confirmer votre disponibilité pour la livraison ou le retrait.
```

### Relance douce

```text
Bonjour [Nom], nous revenons vers vous concernant votre commande Mielido.
Souhaitez-vous toujours confirmer votre commande ?
```

### Demande d’avis après livraison

```text
Bonjour [Nom], merci d’avoir choisi Mielido 🍯
Votre avis nous aide beaucoup. Êtes-vous satisfait de votre commande ?
```

## 7. Intégration WhatsApp

Liens WhatsApp :

- `https://wa.me/2250504498899`
- `https://wa.me/2250778285271`
- `https://wa.me/2250574540805`

Message pré-rempli commande :

```text
Bonjour Mielido, je souhaite passer une commande.
Détail : [produits]
Total estimé : [total] FCFA
Nom : [nom]
Téléphone : [téléphone]
Lieu de livraison : [commune]
Message : [message]
Merci de me confirmer la disponibilité.
```

## 8. Workflow n8n ou Make recommandé

### Déclencheur formulaire

Quand un formulaire est soumis :

1. récupérer les données ;
2. enregistrer dans Google Sheets ;
3. envoyer une notification email ou Telegram à l’équipe ;
4. générer un message WhatsApp ;
5. marquer le statut “Nouveau”.

### Déclencheur statut confirmé

Quand le statut devient “Confirmé” :

1. envoyer une notification interne ;
2. préparer la livraison ;
3. planifier une relance avis client à J+1 après livraison.

### Déclencheur revendeur

Quand le type est “Revendeur” :

1. enregistrer dans l’onglet Revendeurs ;
2. notifier le responsable commercial ;
3. envoyer un message de prise en charge ;
4. programmer une relance si pas de réponse.

## 9. Onglets Google Sheets recommandés

- Commandes ;
- Revendeurs ;
- Produits ;
- Prix ;
- Livraisons ;
- Relances ;
- Statistiques.

## 10. Indicateurs à suivre

- nombre de commandes ;
- chiffre d’affaires estimé ;
- produit le plus demandé ;
- canal le plus rentable ;
- taux de confirmation ;
- demandes revendeur ;
- commandes livrées ;
- commandes annulées ;
- délai moyen de réponse.

## 11. Recommandation de démarrage

Commencer simple :

1. boutique + panier WhatsApp ;
2. Google Sheets de suivi ;
3. WhatsApp Business avec réponses rapides ;
4. relance manuelle ;
5. automatisation n8n/Make lorsque le volume augmente.

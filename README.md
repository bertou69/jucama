# Tableau de suivi des loyers encaissés

Ce dépôt propose un modèle simple pour suivre l'encaissement des loyers mois par mois. Le fichier [`tableau_suivi_loyers.csv`](tableau_suivi_loyers.csv) peut être importé dans Excel, LibreOffice Calc ou Google Sheets pour un suivi et des calculs personnalisés.

## Colonnes du tableau

- **Mois** : période concernée par le loyer.
- **Locataire** : nom du locataire.
- **Logement** : référence ou adresse du bien loué.
- **Loyer_net** : montant du loyer hors charges.
- **Charges** : montant des charges récupérables.
- **Total_du** : total attendu (loyer + charges).
- **Date_echeance** : date limite de paiement stipulée dans le bail.
- **Date_paiement** : date d'encaissement effectif (laisser vide tant que le paiement n'est pas reçu).
- **Montant_encaisse** : montant payé par le locataire.
- **Mode_paiement** : type de règlement (virement, chèque, prélèvement, espèces, etc.).
- **Statut** : état du paiement (Reçu, Partiel, En attente, À venir, etc.).
- **Solde** : reste dû après encaissement.
- **Observations** : zone libre pour noter les relances, les quittances envoyées ou tout commentaire utile.

## Conseils d'utilisation

1. **Copiez le modèle** : dupliquez ce fichier dans votre propre espace de travail avant d'y saisir vos données sensibles.
2. **Mettez à jour chaque mois** : ajoutez une ligne par locataire et par mois pour conserver un historique complet.
3. **Suivez les soldes** : utilisez la colonne *Solde* pour identifier rapidement les retards ou les paiements partiels.
4. **Filtrez et triez** : après import dans un tableur, filtrez par *Statut* ou par *Logement* afin de cibler les actions à mener.
5. **Sécurisez vos données** : pensez à sauvegarder vos fichiers et à respecter la confidentialité des informations personnelles.

## Personnalisation

- Ajoutez d'autres colonnes si besoin (ex. dépôt de garantie, assurance, indexation du loyer).
- Créez des mises en forme conditionnelles dans votre tableur pour mettre en évidence les retards.
- Utilisez des formules pour calculer automatiquement les soldes et les totaux par locataire ou par mois.

Ce modèle constitue un point de départ modulable pour gérer votre suivi des loyers encaissés.

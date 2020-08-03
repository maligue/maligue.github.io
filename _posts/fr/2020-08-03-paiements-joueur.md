---
title: "Nouvelle fonctionnalité - Paiement en ligne pour les joueurs"
lang: fr
localization: player-payments
---
Dès maintenant, les joueurs réguliers peuvent payer leur frais de saison en ligne sur Maligue.ca. Plus besoin de collecter l’argent comptant! L’argent est transférée directement dans votre compte et vous pouvez voir le montant dû de chaque joueur directement en ligne. Nous utilisons la technologie de paiement Stripe pour vous assurer une sécurité et une simplicité hors pair.

Pour que le paiement fonctionne, vous devez tout d’abord configurer votre ligue sur le site web. Ensuite, vous pourrez générer des frais de saisons à payer en ligne et les joueurs auront l’option de payer par le site web ou par l’application mobile. Dans cet article, nous vous présentons tout d’abord la simplicité du paiement pour ensuite vous montrer comment configurer votre ligue.

### Générer un frais de saison (Gestionnaire de ligue)

Une fois votre ligue configurée pour accepter les paiement en ligne, pour générer un frais de saison, il suffit d’aller dans l’onglet “Facturation” de l’interface de gestion de la ligue, puis de cliquer sur “Enregistrer un frais de saison”

{% include image.html src="2020-08-03-enregistrer-frais-de-saison" caption="Enregistrer un frais de saison." %}

Par la suite, il faut entrer le revenu désiré pour la ligue. Le montant chargé à chaque joueur, incluant le 0.30$ + 2.9% collecté par Stripe, sera automatiquement affiché à droite. Au besoin, une date d’échéance et une note peuvent être ajoutées au paiement. Lorsque le tout est configuré, pesez sur “Ajouter”.

{% include image.html src="2020-08-03-enregistrer-frais-de-saison-popup.png" caption="Configurer le frais de saison" %}

C’est tout! Vous pourrez ensuite faire le suivi du paiement de chaque joueur à l’aide de l’onglet “Facturation”. Lorsqu’un joueur effectuera son paiement en ligne, vous le verrez automatiquement comme payé dans cet interface.

<p>{% include image.html src="2020-08-03-frais-de-saison-tracking.png" caption="Suivi des frais de saisons" %}</p>

### Payer en ligne (Joueur)

Les joueurs peuvent payer leur frais de saison directement à partir de leur horaire soit par l’application mobile ou par le site web Maligue.ca. Tout d’abord, le joueur doit cliquer sur le frais en question en haut de l’horaire.

{% include image.html src="2020-08-03-horaire-paiement.png" caption="Horaire" %}

Les détails des frais de la ligue sont ensuite affichés. Il suffit au joueur de peser sur “Payer maintenant”.

{% include image.html src="2020-08-03-effectuer-paiement-détail.png" caption="Détail de paiement" %}

Finalement, le joueur n’a qu’à entrer ses informations de paiement, puis peser sur “Payer”.

{% include image.html src="2020-08-03-paiement.png" caption="Payer en ligne" %}

### Configuration de la ligue

Pour activer le paiement, allez dans les paramètres de votre ligue et cliquez sur l'onglet Paiement. Cliquez ensuite sur Connecter un compte Stripe. Vous devez être sur le site web et non sur l'app mobile.

{% include image.html src="2017-09-10-configure-payment-fr.png" caption="Configurer le paiement." %}

Sélectionnez Canada et dans la zone de texte «Tell us about your business», vous devez expliquer que vous êtes une ligue sportive qui vend une saison ou des parties de sport. Voici un exemple de message: «I own a sport league that sells hockey games to substitutes. I charge customers before the start of the game.». Ne cochez pas la case à cocher suivante.

{% include image.html src="2017-09-10-configure-payment-product-fr.png" caption="Entrez la description de votre ligue." %}

Pour «Your business type», choisissez «Individual/Sole proprietorship» et entrez votre «Business number (TAX ID)» si vous en avez un. Entrez ensuite votre adresse personnelle dans «Business address». Pour «Your website», activez le site web de ligue sur Maligue.ca et copiez-y l’URL.

Entrez ensuite votre nom et votre date de naissance dans les champs «Legal name» et «Date of birth». Pour SIN (Tax ID), vous devez entrer votre numéro d’assurance social pour confirmer votre identifiée.

Saisissez le nom de votre ligue dans le champ «Business Name» et votre numéro de téléphone dans «Phone». Cette information sera affichée sur les relevés de carte de crédit des joueurs.

Sélectionnez «CAD» comme Bank account currency et ensuite saisissez les informations de votre compte de banque. Vous pouvez trouver ces informations sur votre spécimen chèque.

Finalement, entrez votre adresse courriel et votre mot de passe pour créer votre compte Stripe. Vous pourrez utiliser ces données pour vous authentifier sur Stripe et consulter l’information de vos paiements.

Nous attendons vos commentaires au [info@maligue.ca](mailto:info@maligue.ca).

Par Carl de Maligue.ca.

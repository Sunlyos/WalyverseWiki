# 🏢 Villes

Les villes permettent de protéger vos bases et constructions, et de créer vos histoires avec vos amis. Elles sont entièrement personnalisables, selon vos projets et idées, et évoluent selon votre grade et le nombre de personnes qui s'y trouvent.

***

## 🧐 Commandes principales des villes

* <mark style="color:green;">Création de la ville</mark> 🏢 &#x20;

Naufragé, Moussaillon, Matelot : 1 Ville.\
Canonnier, Second, Capitaine, Corsaire : 2 Villes. (<mark style="color:red;">`/grades`</mark>)

| Commande                                                       | Description                                                           |
| -------------------------------------------------------------- | --------------------------------------------------------------------- |
| <mark style="color:red;">`/ville create "NomDeLaVille"`</mark> | Créer une ville.                                                      |
| <mark style="color:red;">`/ville delete "NomDeLaVille"`</mark> | Supprimer une ville.                                                  |
| <mark style="color:red;">`/ville setspawn`</mark>              | Changer le spawn de la ville, coût de 500$.                           |
| <mark style="color:red;">`/ville claim`</mark>                 | Claim le chunk dans lequel vous vous trouvez.                         |
| <mark style="color:red;">`/ville claim auto`</mark>            | Activer/Désactiver le claim automatique des chunks en passant dedans. |
| <mark style="color:red;">`/ville map`</mark>                   | Menu interactif cliquable pour claim.                                 |
| <mark style="color:red;">`/ville unclaim`</mark>               | Unclaim le chunk dans lequel vous vous trouvez.                       |
| <mark style="color:red;">`/ville view`</mark>                  | Informations sur les claims.                                          |
| <mark style="color:red;">`/ville spawn "NomDeLaVille"`</mark>  | Se téléporter au spawn d'une ville.                                   |
| <mark style="color:red;">`/ville edit "NomDeLaVille"`</mark>   | Mode édition de la ville.                                             |



* <mark style="color:green;">Membres & Discussions</mark> 💭

| Commande                                                               | Description                                                                                    |
| ---------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| <mark style="color:red;">`/ville trust/untrust "pseudo"`</mark>        | Ajouter/Retirer un joueur à/de la ville.                                                       |
| <mark style="color:red;">`/ville untrust "pseudo" *`</mark>            | Retire un joueur de la ville ainsi que de toutes les zones.                                    |
| <mark style="color:red;">`/ville ban/unban "pseudo"`</mark>            | Bannir/Dé-bannir un joueur de la ville ou zone.                                                |
| <mark style="color:red;">`/ville chat "NomDeLaVille "message"`</mark>  | Envoyer un message dans le tchat de ville.                                                     |
| <mark style="color:red;">`/vc "message"`</mark>                        | En sélectionnant la /ville dans le menu, tu peux écrire directement dans le tchat de celle ci. |
| <mark style="color:red;">`/ville leave`</mark>                         | Quitter une ville ou une zone.                                                                 |
| <mark style="color:red;">`/ville list recrutements_on`</mark>          | Ouvre le menu des villes qui recrutent.                                                        |

:bulb: Les villes ont été repensées pour regrouper le système de claim et celui des guildes. En plus de la commande en jeu regroupant la liste des villes qui recrutent, le super channel :herb:Communauté sur [discord](http://discord.gg/astralya) est à ta disposition.&#x20;



* <mark style="color:green;">Niveaux & Économie</mark>💲

| Commande                                                            | Description                                        |
| ------------------------------------------------------------------- | -------------------------------------------------- |
| <mark style="color:red;">`/ville level`</mark>                      | Consulter le niveau de la ville.                   |
| <mark style="color:red;">`/ville balance`</mark>                    | Consulter le solde bancaire de la ville.           |
| <mark style="color:red;">`/ville deposit/withdraw "montant"`</mark> | Déposer/Retirer de l'argent de la banque de ville. |
| <mark style="color:red;">`/ville upkeep`</mark>                     | Voir le montant des impôts à payer pour ta ville.  |

:bulb: Une nouvelle catégorie pour les villes a été ajoutée au /profil des joueurs ! Elle permet de voir combien de chunk(s) ont déjà été claim(s) par la ville sélectionnée dans le menu /villes, et le total de chunks pouvant être claims.

## 🏡 Faire évoluer sa ville&#x20;

L'évolution du nombre de chunks pouvant être claim par le joueur augmente avec plusieurs facteurs : le grade du Maire, le niveau de la ville, le grade ainsi que les chunks support de membre.&#x20;

{% tabs %}
{% tab title="📌 Maire de la ville" %}
Tout d'abord, dès la création de la ville, votre grade a un rôle dans la limite de chunks pouvant être claim. En effet :&#x20;

* Naufragé : `50 chunks`
* Moussaillon : `115 chunks`
* Matelot : `195 chunks`
* Canonnier: `290 chunks`
* Second : `400 chunks`
* Capitaine : `525 chunks`
* Corsaire : `665 chunks`
* Astralis : `2000 chunks` qui s'ajoutent à ceux du grade farmable
{% endtab %}

{% tab title="📈 Niveau de la ville" %}
💡Consultez votre niveau avec <mark style="color:red;">`/ville level`</mark>.<br>

* Abri (Niveau par défaut) : `+0 chunk`
* Campement : `+100 chunks`
* Village : `+250 chunks`
* Cité : `+500 chunks`
* Province : `+800 chunks`
* Ordre : `+1000 chunks`
* Empire : `+1500 chunks`\
  \
  ✅ Ces bonus sont cumulables, donc une ville Empire a un total de 4150 chunks supplémentaires.<br>
{% endtab %}

{% tab title="🧮 Exemple " %}
Un joueur **Astralis & Canonnier** ayant **2 villes de niveau Empire** (et sans compter les chunks support) peut déjà obtenir jusqu’à :

> 2000 chunks (grade Astralis) + 290 chunks (grade Canonnier) + 1500 chunks (Empire) × 2 villes = **7 580 chunks au total**, sans compter les chunks support apportés par les membres !
{% endtab %}

{% tab title="🫂 Chunks support" %}
Chaque membre ajouté à votre ville apporte des chunks supplémentaires selon son grade :

* Naufragé : `+0 chunk`
* Moussaillon : `+5 chunks`
* Matelot : `+8 chunks`
* Canonnier: `+13 chunks`
* Second : `+18 chunks`
* Capitaine : `+25 chunks`
* Corsaire : `+30 chunks`
* Astralis : `+50 chunks` \
  \
  \- <mark style="color:red;">`/ville trust "pseudo"`</mark> 😜&#x20;
{% endtab %}
{% endtabs %}

| Nombre de membres 🧳​                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>Selon votre grade, vous pouvez inviter dans votre ville plus de personnes, et rejoindre un plus grand nombre de villes :</p><ul><li>Naufragé : <code>5 villes</code></li><li>Moussaillon : <code>10 villes</code></li><li>Matelot : <code>15 villes</code></li><li>Canonnier: <code>20 villes</code></li><li>Second : <code>25 villes</code></li><li>Capitaine : <code>30 villes</code></li><li>Corsaire : <code>35 villes</code></li><li>Astralis : <code>+5 villes</code> qui s'ajoutent à ceux du grade farmable<br><br>- <mark style="color:red;"><code>/ville invites</code></mark> 🏃​</li></ul> |

## 🗺️ Zones

Les zones sont des "sous-claims", permettant de définir des règles spécifiques dans une partie d'un claim. Le nombre de zones disponibles dépend du grade du joueur :&#x20;

{% tabs %}
{% tab title="⚠️ Zones & Grades " %}
* Naufragé : `2 zones`
* Moussaillon : `5 zones`
* Matelot : `10 zones`
* Canonnier: `15 zones`
* Second : `20 zones`
* Capitaine : `25 zones`
* Corsaire : `30 zones`
* Astralis : `+5 zones` qui s'ajoutent au grade farmable

\
Avec le système de **zones**, vous pouvez définir des **règles localisées** : un rôle peut être autorisé à ouvrir les portes dans une zone, mais pas dans une autre. Ça c'est de la technologie !😎
{% endtab %}

{% tab title="💌 Une idée pour vous " %}
Tu peux par exemple diviser ta ville en quartiers avec des fonctions différentes : résidentiel, commercial, industriel et bien plus encore. Cela dépend entièrement de ton imagination !&#x20;
{% endtab %}
{% endtabs %}

## 📜 Flags & Paramètres

* Les flags sont rangés en **3 catégories** :&#x20;

{% tabs %}
{% tab title="☘️Paramètres naturels" %}
Cette catégorie concerne tous les flags naturels pouvant être activés/désactivés, par exemple :

* Apparition des animaux & des monstres & des phantoms. (_un pour chacun d'eux_)
* Grief des entités. Fini les Creepers qui cassent toute ta super maison en terre !🙄
* Propagation du feu.
* Fonte de la neige.

&#x20;Et bien plus à découvrir en jeu.\
&#x20;&#x20;
{% endtab %}

{% tab title="⚒️ Options d'actions " %}
Cette catégorie concerne toutes les options d'actions pouvant être activées/désactivées, par exemple :

* Casser/Poser des blocs. (_un pour chacun d'eux_)
* Ouvrir les trappes/conteneurs/portes. (_un pour chacun d'eux_)
* Récolter/Piétiner les cultures. (_un pour chacun d'eux_)
* Attaques les animaux/monstres. (_un pour chacun d'eux_)
* Utiliser des élytres/perle de l'end. (_un pour chacun d'eux_)

Et bien plus à découvrir en jeu.
{% endtab %}

{% tab title="🔐 Options de gestion " %}
Cette catégorie concerne toutes les options de gestion pouvant être activées/désactivées, par exemple :

* Approuver/Expulser un membre. (_un pour chacun d'eux_)
* Définir les rôles.
* Modifier les paramètres des rôles.
* Claim et Unclaim des chunks.
* Modifier les taxes.
* Retirer de l'argent de la banque de ville.

Et bien plus à découvrir en jeu.

&#x20;   ⚠️  Comme vous pouvez le voir, il s'agit d'options donnant accès à des paramètres <mark style="color:red;">**importants**</mark> pour la gestion de votre ville. C'est avec une grande vigilance qu'il faut les activer et les donner à vos membres. ⚠️
{% endtab %}
{% endtabs %}

:bulb: Et surtout : **chaque flag est lié aux rôles de ville**. Vous pouvez décider qui peut faire quoi, **selon son rôle** dans votre ville ou la zone. Plus besoin d'un seul flag global qui s'applique à tout le monde, vous y compris.

## 🤔 Ville(s) & inactivité(s) !&#x20;

{% tabs %}
{% tab title=" 👀 Propriétaire" %}
À partir d'un certain temps d'inactivité et en fonction de son temps de jeu, un propriétaire est considéré comme inactif ! ↙️\
\
Le propriétaire à moins de :

* **1 heure** de jeu, il est considéré inactif après **14 jours** d'absence.
* **12 heures** de jeu, il est considéré inactif après **30 jours** d'absence.
* **24 heures** de jeu, il est considéré inactif après **90 jours** d'absence.
* **72 heures** de jeu (donc moins de 3 jours), il est considéré inactif après **180 jours** d'absence.
* Et si le propriétaire a **plus de 14 jours de jeu**, il est considéré inactif après 365 jours d'absence.

**Plus tu as joué, plus tu es protégé** en tant que propriétaire, ce qui est logique 😎

💡Une fois le temps d'inactivité dépassé, la ville est ainsi donnée au membre le plus haut gradé !
{% endtab %}

{% tab title="🫂 Membres" %}
À partir d'un certain temps d'inactivité et en fonction de son temps de jeu, un membre est considéré comme inactif et est donc retiré de la ville !↙️

Le membre à moins de :

* **1 heure** de jeu, il est retiré après **14 jours** d'absence.
* **6 heures** de jeu, il est retiré après **30 jours** d'absence.
* **12 heures** de jeu, il est retiré après **60 jours** d'absence.
* **24 heures** de jeu, il est retiré après **90 jours** d'absence.
* Un membre qui a plus de **24 heures** de jeu est aussi retiré après **90 jours** d'absence.

**Tout membre se voit donc être retiré après 90 jours d'inactivité**, quel que soit son temps de jeu. ✔️
{% endtab %}
{% endtabs %}


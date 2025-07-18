---
hidden: true
---

# 🏢 Villes

Les villes permettent de protéger vos bases et constructions, et de créer vos histoires avec vos amis. Elles sont entièrement personnalisables, selon vos projets et idées, et évoluent selon votre grade et le nombre de personnes qui s'y trouvent.

## Informations pour le changement de système

?? je trouve pas ça super utile si ? :o en + si on dit que les joueurs ont le temps ils vont le faire le 364e jour&#x20;

## 🧐 Commandes principales des villes

* <mark style="color:green;">Création de la ville</mark> 🏘️&#x20;

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
| <mark style="color:red;">`/ville spawn "NomDeLaVille"`</mark>  | Se téléporter au spawn d'une ville.                                   |
| <mark style="color:red;">`/ville edit "NomDeLaVille"`</mark>   | Mode édition de la ville.                                             |



* <mark style="color:green;">Membres & Discussions</mark> 💭

| Commande                                                               | Description                                                                                    |
| ---------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| <mark style="color:red;">`/ville trust/untrust "pseudo"`</mark>        | Ajouter/Retirer un joueur à/de la ville.                                                       |
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
|                                                                     |                                                    |

:bulb: Une nouvelle catégorie pour les villes a été ajoutée au /profil des joueurs ! Elle permet de voir combien de chunk(s) ont déjà été claim(s) par la ville sélectionnée dans le menu /villes, et le total de chunks pouvant être claims.

## 🏡 Faire évoluer sa ville&#x20;

L'évolution du nombre de chunks pouvant être claim par le joueur augmente avec plusieurs facteurs : Le grade du Maire, le niveau de la ville ainsi que les chunks support de membre.&#x20;

{% tabs %}
{% tab title="Maire de la ville 📌" %}
Tout d'abord, dès la création de la ville, votre grade a un rôle dans la limite de chunks pouvant être claim. En effet :&#x20;

* Naufragé : `50 chunks`
* Moussaillon : `100 chunks`
* Matelot : `150 chunks`
* Canonnier: `250 chunks`
* Second : `350 chunks`
* Capitaine : `500 chunks`
* Corsaire : `600 chunks`
* Astralis : `1000 chunks`&#x20;
{% endtab %}

{% tab title="Niveau de la ville 📈" %}
💡Consultez votre niveau avec <mark style="color:red;">`/ville level`</mark>.\


* Abri (Niveau par défaut) : `+0 chunk`
* Campement : `+100 chunks`
* Village : `+250 chunks`
* Cité : `+500 chunks`
* Province : `+800 chunks`
* Ordre : `+1000 chunks`
* Empire : `+1500 chunks`\
  \
  ✅ Ces bonus sont cumulables, donc une ville Empire a un total de 4150 chunks supplémentaires.\

{% endtab %}

{% tab title="Chunks support 🫂" %}
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

{% tab title="Exemple 🧮 " %}
Un joueur **Astralis & Canonnier** ayant **2 villes de niveau Empire** (et sans compter le bonus n°2, soit les chunks support) peut déjà obtenir jusqu’à :

> 1000 chunks (grade Astralis) +4150 chunks × 2 (niveau Empire × 2 villes) = **9300 chunks au total**, sans compter les chunks support apportés par les membres !
{% endtab %}
{% endtabs %}

## Zones



## 📜 Flags & Paramètres

* 3 types de flags : naturels, gestion de mb, et j'sais plus quoi (action ?)


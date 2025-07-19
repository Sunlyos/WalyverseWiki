---
hidden: true
---

# 🏢 Villes2

Les villes permettent de protéger vos bases et constructions, tout en vous offrant un cadre évolutif pour jouer entre amis. Personnalisables, modulables, et liées à vos grades, elles vous accompagnent dans vos projets les plus ambitieux.

## <mark style="color:yellow;">Commandes principales</mark>

<details>

<summary><span data-gb-custom-inline data-tag="emoji" data-code="1f3d9">🏙️</span> <mark style="color:green;">Créer &#x26; gérer une ville</mark></summary>

| Commande                                              | Description                             |
| ----------------------------------------------------- | --------------------------------------- |
| <mark style="color:red;">`/ville create "nom"`</mark> | Créer une ville                         |
| <mark style="color:red;">`/ville delete "nom"`</mark> | Supprimer une ville                     |
| <mark style="color:red;">`/ville edit "nom"`</mark>   | Sélectionner une ville pour les actions |
| <mark style="color:red;">`/ville setspawn`</mark>     | Modifier le spawn de la ville (500$)    |
| <mark style="color:red;">`/ville spawn "nom"`</mark>  | Se téléporter au spawn d'une ville      |
| <mark style="color:red;">`/ville claim`</mark>        | Claim le chunk actuel                   |
| <mark style="color:red;">`/ville claim auto`</mark>   | (Dés)active le claim automatique        |
| <mark style="color:red;">`/ville map`</mark>          | Ouvre une carte cliquable pour claim    |
| <mark style="color:red;">`/ville unclaim`</mark>      | Supprimer le chunk actuel               |

Le nombre de villes que vous pouvez créer dépend de votre grade :

* Naufragé, Moussaillon, Matelot : **1 ville**
* Canonnier, Second, Capitaine, Corsaire : **2 villes**\
  (<mark style="color:red;">`/grades`</mark> pour plus d'infos)

</details>

<details>

<summary><span data-gb-custom-inline data-tag="emoji" data-code="1f5e3">🗣️</span> <mark style="color:green;">Membres &#x26; interactions</mark></summary>

<table><thead><tr><th width="325">Commande</th><th>Description</th></tr></thead><tbody><tr><td><mark style="color:red;"><code>/ville trust/untrust "pseudo"</code></mark></td><td>Ajouter ou retirer un membre</td></tr><tr><td><mark style="color:red;"><code>/ville ban/unban "pseudo"</code></mark></td><td>Bannir ou débannir un joueur</td></tr><tr><td><p><mark style="color:red;"><code>/ville chat "nom" "message"</code></mark></p><p><mark style="color:red;">💡</mark> ou <mark style="color:red;"><code>/vc</code></mark></p></td><td>Envoyer un message dans le tchat de la ville</td></tr><tr><td><mark style="color:red;"><code>/ville leave</code></mark></td><td>Quitter la ville ou une zone</td></tr><tr><td><mark style="color:red;"><code>/ville list recrutement_on</code></mark></td><td>Liste les villes qui recrutent</td></tr></tbody></table>

{% hint style="success" %}
Retrouvez également les villes ouvertes au recrutement dans le channel Discord 🌿 **Communauté** : [discord.gg/astralya](http://discord.gg/astralya)
{% endhint %}

</details>

<details>

<summary><span data-gb-custom-inline data-tag="emoji" data-code="1f4b0">💰</span> <mark style="color:green;">Niveau &#x26; Économie</mark></summary>

<table><thead><tr><th width="325">Commande</th><th>Description</th></tr></thead><tbody><tr><td><mark style="color:red;"><code>/ville level</code></mark></td><td>Voir le niveau de la ville et l'améliorer</td></tr><tr><td><mark style="color:red;"><code>/ville balance</code></mark></td><td>Voir le solde de la ville</td></tr><tr><td><mark style="color:red;"><code>/ville deposit "montant"</code></mark></td><td>Déposer de l'argent</td></tr><tr><td><mark style="color:red;"><code>/ville withdraw "montant"</code></mark></td><td>Retirer de l'argent</td></tr><tr><td><mark style="color:red;"><code>/ville upkeep</code></mark></td><td>Voir les impôts à payer</td></tr></tbody></table>

{% hint style="success" %}
Une catégorie **"Villes"** est disponible dans le `/profil`, indiquant le nombre de chunks déjà claim par votre ville ainsi que la quantité maximale de chunks pouvant être revendiqués par celle-ci.
{% endhint %}

</details>

***

## <mark style="color:yellow;">Évolution de votre ville</mark>

L'expansion d'une ville dépend de **plusieurs facteurs** : le grade du maire, le niveau de la ville, le soutien des membres, etc.

{% tabs %}
{% tab title="📌 Grade du Maire" %}
<details>

<summary>🦜 <mark style="color:green;">Chunks disponibles selon votre grade</mark></summary>

| Grade       | Chunks autorisés                            |
| ----------- | ------------------------------------------- |
| Naufragé    | 50                                          |
| Moussaillon | 115                                         |
| Matelot     | 195                                         |
| Canonnier   | 290                                         |
| Second      | 400                                         |
| Capitaine   | 525                                         |
| Corsaire    | 665                                         |
| Astralis    | +2000 (cumulable avec votre grade farmable) |

</details>
{% endtab %}

{% tab title="📈 Niveau de la Ville" %}
<details>

<summary>📈 <mark style="color:green;">Bonus cumulables</mark></summary>

| Niveau        | Bonus |
| ------------- | ----- |
| Abri (défaut) | +0    |
| Campement     | +100  |
| Village       | +250  |
| Cité          | +500  |
| Province      | +800  |
| Ordre         | +1000 |
| Empire        | +1500 |

✅ Les bonus sont **cumulables**, donc une ville Empire a un total de 4150 chunks supplémentaires.

</details>
{% endtab %}

{% tab title="🧮 Exemple" %}
Un joueur **Astralis & Corsaire** avec **2 villes Empire** (sans membre) dispose déjà de :

`2000 (Astralis) + 665 (Corsaire) + 4150 x 2 = 10 965 chunks` 🎯
{% endtab %}

{% tab title="🫂 Chunks de soutien" %}
<details>

<summary>🫂 <mark style="color:green;">Bonus par membre ajouté</mark></summary>

| Grade du membre | Chunks bonus |
| --------------- | ------------ |
| Naufragé        | 0            |
| Moussaillon     | +5           |
| Matelot         | +8           |
| Canonnier       | +13          |
| Second          | +18          |
| Capitaine       | +25          |
| Corsaire        | +30          |
| Astralis        | +50          |

> <mark style="color:red;">`/ville trust "pseudo"`</mark> pour inviter

</details>
{% endtab %}
{% endtabs %}

<details>

<summary><mark style="color:green;">👥 Nombre de villes rejoignables &#x26; de membres</mark></summary>

| Grade       | Villes rejoignables/Membres              |
| ----------- | ---------------------------------------- |
| Naufragé    | 5                                        |
| Moussaillon | 10                                       |
| Matelot     | 15                                       |
| Canonnier   | 20                                       |
| Second      | 25                                       |
| Capitaine   | 30                                       |
| Corsaire    | 35                                       |
| Astralis    | +5 (cumulable avec votre grade farmable) |

> 🔁 <mark style="color:red;">`/ville invites`</mark> <mark style="color:red;"></mark><mark style="color:red;">pour voir vos invitations</mark>

</details>

***

## <mark style="color:yellow;">Zones</mark>

Les zones sont des "sous-parties" de votre ville. Elles permettent de **définir des règles spécifiques** dans certaines portions de vos claims. Exemples : donner l'accès aux portes uniquement dans une zone marchande, restreindre l'ouverture de coffres dans une autre…

{% tabs %}
{% tab title="⚠️ Capacités selon grade" %}
| Grade       | Zones autorisées                         |
| ----------- | ---------------------------------------- |
| Naufragé    | 2                                        |
| Moussaillon | 5                                        |
| Matelot     | 10                                       |
| Canonnier   | 15                                       |
| Second      | 20                                       |
| Capitaine   | 25                                       |
| Corsaire    | 30                                       |
| Astralis    | +5 (cumulable avec votre grade farmable) |
{% endtab %}

{% tab title="💡 Idée d'organisation" %}
Pourquoi ne pas organiser votre ville en **quartiers** ?

* Zone résidentielle
* Quartier marchand
* Secteur administratif
* Zone "musée" ou zone à accès restreint

➡️ Vous pouvez adapter les permissions selon les rôles !
{% endtab %}
{% endtabs %}

***

## <mark style="color:yellow;">Flags & paramètres</mark>

Les **flags** sont les règles appliquées dans vos villes ou zones. Ils sont **liés aux rôles** : chaque rôle peut avoir des droits différents.

{% tabs %}
{% tab title="☘️ Paramètres naturels" %}
* Apparition des animaux / monstres / phantoms
* Propagation du feu
* Fonte de la neige / glace
* Grief des entités
* ...
{% endtab %}

{% tab title="⚒️ Actions" %}
* Ouvrir trappes, portes, coffres
* Poser / casser des blocs
* Piétiner ou récolter des cultures
* Utiliser des élytres, perles
* Taper des mobs
* Jeter / ramasser des objets
* ...
{% endtab %}

{% tab title="🔐 Gestion" %}
* Modifier les rôles
* Claim / unclaim
* Modifier les taxes
* Gérer la banque
* Expulser un joueur
* ...

⚠️ Ces paramètres donnent accès à des fonctions sensibles. À ne confier qu'à des membres de confiance !
{% endtab %}
{% endtabs %}

{% hint style="success" %}
Les flags sont **indépendants selon les zones**, et liés aux **rôles**. Vous pouvez donc avoir un rôle "Habitant" qui peut casser des blocs dans une zone, mais rien faire ailleurs.
{% endhint %}

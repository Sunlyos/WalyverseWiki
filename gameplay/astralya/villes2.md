---
hidden: true
---

# 🏢 Villes

Les villes permettent de protéger vos bases et constructions, tout en vous offrant un cadre évolutif pour jouer entre amis. Personnalisables, modulables, et liées à vos grades, elles vous accompagnent dans vos projets les plus ambitieux.

## <mark style="color:yellow;">Commandes principales</mark>

<details>
<summary><span data-gb-custom-inline data-tag="emoji" data-code="1f3d9">🏘️</span> <mark style="color:green;">Créer & gérer une ville</mark></summary>

💬 Le nombre de villes que vous pouvez créer dépend de votre grade :

- Naufragé, Moussaillon, Matelot : **1 ville**
- Canonnier, Second, Capitaine, Corsaire : **2 villes**  
(<mark style="color:red;">`/grades`</mark> pour plus d'infos)

| Commande | Description |
|---|---|
| `/ville create "Nom"` | Créer une ville |
| `/ville delete "Nom"` | Supprimer une ville |
| `/ville edit "Nom"` | Mode édition de la ville |
| `/ville setspawn` | Modifier le spawn de la ville (500$) |
| `/ville spawn "Nom"` | Se téléporter au spawn |
| `/ville claim` | Claim le chunk actuel |
| `/ville claim auto` | (Dés)active le claim automatique |
| `/ville map` | Carte cliquable pour claim |
| `/ville unclaim` | Supprimer le chunk actuel |

</details>

<details>
<summary><span data-gb-custom-inline data-tag="emoji" data-code="1f5e3">🗣️</span> <mark style="color:green;">Membres & interactions</mark></summary>

| Commande | Description |
|---|---|
| `/ville trust/untrust "pseudo"` | Ajouter ou retirer un membre |
| `/ville ban/unban "pseudo"` | Bannir ou débannir un joueur |
| `/ville chat "Nom" "message"` | Envoyer un message dans le chat de ville |
| `/vc "message"` | Parler dans le chat de la ville sélectionnée |
| `/ville leave` | Quitter la ville ou une zone |
| `/ville list recrutements_on` | Liste les villes qui recrutent |

💡 Retrouvez également les villes ouvertes au recrutement dans le channel Discord 🌿 **Communauté** : [discord.gg/astralya](http://discord.gg/astralya)

</details>

<details>
<summary><span data-gb-custom-inline data-tag="emoji" data-code="1f4b0">💰</span> <mark style="color:green;">Niveau & Économie</mark></summary>

| Commande | Description |
|---|---|
| `/ville level` | Voir le niveau de la ville |
| `/ville balance` | Voir le solde de la ville |
| `/ville deposit "montant"` | Déposer de l'argent |
| `/ville withdraw "montant"` | Retirer de l'argent |
| `/ville upkeep` | Voir les impôts à payer |

💡 Une catégorie **"Villes"** est disponible dans le `/profil`, indiquant :
- Le nombre de chunks claim par votre ville
- Le nombre maximal possible

</details>

***

## <mark style="color:yellow;">Évolution de votre ville</mark>

L'expansion d'une ville dépend de **plusieurs facteurs** : le grade du maire, le niveau de la ville, le soutien des membres, etc.

{% tabs %}
{% tab title="📌 Grade du Maire" %}
| Grade | Chunks autorisés |
|--|--|
| Naufragé | 50 |
| Moussaillon | 115 |
| Matelot | 195 |
| Canonnier | 290 |
| Second | 400 |
| Capitaine | 525 |
| Corsaire | 665 |
| Astralis | +2000 (cumulable) |
{% endtab %}

{% tab title="📈 Niveau de la Ville" %}
| Niveau | Bonus |
|--|--|
| Abri (défaut) | +0 |
| Campement | +100 |
| Village | +250 |
| Cité | +500 |
| Province | +800 |
| Ordre | +1000 |
| Empire | +1500 |

✅ Les bonus sont **cumulables**.
{% endtab %}

{% tab title="🧮 Exemple" %}
Un joueur **Astralis & Canonnier** avec **2 villes Empire** (sans membres) dispose déjà de :

`2000 (Astralis) + 290 (Canonnier) + 1500 x 2 = 7 290 chunks` 🎯
{% endtab %}

{% tab title="🫂 Chunks de soutien" %}
Chaque membre ajouté à votre ville offre des chunks bonus selon son grade :

- Naufragé : 0
- Moussaillon : +5
- Matelot : +8
- Canonnier : +13
- Second : +18
- Capitaine : +25
- Corsaire : +30
- Astralis : +50

> `/ville trust "pseudo"` pour inviter
{% endtab %}
{% endtabs %}

<details>
<summary><mark style="color:green;">👥 Nombre de villes et de membres</mark></summary>

| Grade | Villes max |
|--|--|
| Naufragé | 5 |
| Moussaillon | 10 |
| Matelot | 15 |
| Canonnier | 20 |
| Second | 25 |
| Capitaine | 30 |
| Corsaire | 35 |
| Astralis | +5 (cumulables)

> 🔁 `/ville invites` pour voir vos invitations
</details>

***

## <mark style="color:yellow;">🗺️ Zones</mark>

Les zones sont des "sous-parties" de votre ville. Elles permettent de **définir des règles spécifiques** dans certaines portions de vos claims.

{% tabs %}
{% tab title="⚠️ Capacités selon grade" %}
| Grade | Zones autorisées |
|--|--|
| Naufragé | 2 |
| Moussaillon | 5 |
| Matelot | 10 |
| Canonnier | 15 |
| Second | 20 |
| Capitaine | 25 |
| Corsaire | 30 |
| Astralis | +5 (cumulables)

Exemples : donner l'accès aux portes uniquement dans une zone marchande, restreindre l'ouverture de coffres dans une autre…
{% endtab %}

{% tab title="💡 Idée d'organisation" %}
Pourquoi ne pas organiser votre ville en **quartiers** ?
- Zone résidentielle
- Quartier marchand
- Secteur administratif
- Zone "musée" ou zone à accès restreint

➡️ Vous pouvez adapter les permissions selon les rôles !
{% endtab %}
{% endtabs %}

***

## <mark style="color:yellow;">📜 Flags & paramètres</mark>

Les **flags** sont les règles appliquées dans vos villes ou zones. Ils sont **liés aux rôles** : chaque rôle peut avoir des droits différents.

{% tabs %}
{% tab title="☘️ Paramètres naturels" %}
- Apparition des animaux / monstres / phantoms
- Propagation du feu
- Fonte de la neige / glace
- Grief des entités
{% endtab %}

{% tab title="⚒️ Actions" %}
- Ouvrir trappes, portes, coffres
- Poser / casser des blocs
- Piétiner ou récolter des cultures
- Utiliser des élytres, perles
- Taper des mobs
- Jeter / ramasser des objets
{% endtab %}

{% tab title="🔐 Gestion" %}
- Modifier les rôles
- Claim / unclaim
- Modifier les taxes
- Gérer la banque
- Expulser un joueur

⚠️ Ces paramètres donnent accès à des fonctions sensibles. À ne confier qu'à des membres de confiance !
{% endtab %}
{% endtabs %}

💡 Les flags sont **indépendants selon les zones**, et liés aux **rôles**. Vous pouvez donc avoir un rôle "Habitant" qui peut casser des blocs dans une zone, mais rien faire ailleurs.

---

Tu veux que je te le mette en `.md` complet avec indentation + assets + GitBook ready ? Ou que je fasse la même chose pour une autre page ?

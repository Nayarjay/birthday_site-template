# 🖼️ Photos perso

Dépose ici tes propres photos (au dos des cartes retournables).

## Attendu pour l'instant
| Carte             | Fichier            | Rôle                                              |
|-------------------|--------------------|---------------------------------------------------|
| Minecraft         | `minecraft.jpg`    | Photo au **dos** de la carte                      |
| League of Legends | `lol.jpg`          | Photo au **dos** de la carte                      |
| Musculation       | `muscu.jpg`        | Photo au **dos** de la carte                      |
| Code Geass (invit)| `geass.jpg`        | **Recto** de la page invitation (si le lien web échoue) |

Tant que le fichier n'existe pas, un repère « Ajoute ta photo » s'affiche au dos
(rien ne casse). Dès que tu déposes `muscu.jpg` ici, il apparaît automatiquement.

## Changer / ajouter
Les chemins sont définis dans `index.html`, champ `back:[...]` de chaque chapitre
(bloc « CONTENU A EDITER »). Tu peux :
- mettre **2 photos** : `back:['images/muscu1.jpg','images/muscu2.jpg']`
- choisir le cadrage : `backFit:'cover'` (remplit) ou `'contain'` (photo entière)
- faire pareil pour les autres cartes (LoL, Valorant, Homies) si tu veux y mettre
  de vraies photos plutôt que les images de jeux.

Formats conseillés : `.jpg` ou `.png`, format portrait (ex. 1000×1250) pour un
rendu net dans le cadre.

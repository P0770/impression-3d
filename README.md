# Impression 3D — pièces conçues par moi

Pièces que j'ai modélisées sur Autodesk Inventor, puis imprimées en PLA sur ma Bambu Lab P1S : des pièces pour mes drones FPV, des objets du quotidien et une boîte de forme complexe.

## Contenu

| Dossier | Pièces |
|---|---|
| `stl/drone/` | Châssis du micro-drone Matrix HD, garde d'hélices, support de l'AIO, protection de l'AIO du Flywoo LR4 (version 6) |
| `stl/cuisine/` | Support pour salière et poivrière, versions 1 et 2 |
| `stl/rangement/` | Boîte de rangement pour un jouet |
| `rendus/` | Rendus 3D des pièces |

## Pièces de drone

![Pièces de drone](rendus/drone-pieces.jpg)

| Pièce | Dimensions | Rôle |
|---|---|---|
| Châssis | 104 × 104 × 12 mm | Châssis en X du micro-drone Matrix HD (classe 75 mm) |
| Garde d'hélices | 123 × 123 × 16 mm | Entoure les hélices pour les protéger |
| Support de l'AIO | 41 × 41 × 3 mm | Plaque de fixation de la carte AIO |

**Place des moteurs et des hélices.** Les moteurs se fixent sur les quatre motifs de trous situés aux sommets d'un carré de 50 mm de côté.

- Distance entre deux moteurs voisins : 50,0 mm.
- Distance entre deux moteurs opposés : 50 × √2 = 50 × 1,414 ≈ 70,7 mm. C'est la taille d'un micro-drone de classe 75 mm.
- Deux hélices voisines ne doivent pas se toucher. La somme de leurs deux rayons doit donc rester inférieure à 50 mm, soit un diamètre inférieur à 50 mm.
- Les trous de 5 mm en bout de bras reçoivent les plots de la garde d'hélices. Ils sont à (2 × 47,6) × √2 ≈ 134,6 mm en diagonale.

### Protection de l'AIO du LR4

![Protection de l'AIO](rendus/fc-protect.jpg)

Cadre de 30 × 30 × 4 mm qui entoure la carte AIO (contrôleur de vol et variateurs sur une seule carte) de mon Flywoo Explorer LR4, pour la protéger. Le centre est ajouré. Le fichier publié est la 6ᵉ version de la pièce.

## Support sel et poivre

![Support sel et poivre](rendus/sel-poivre.jpg)

Support qui tient une salière et une poivrière ensemble, avec une anse pour les transporter.

| Version | Dimensions | Volume de matière |
|---|---|---|
| 1 | 130 × 170 × 65 mm | 75,8 cm³ |
| 2 | 139 × 115 × 59 mm | 52,4 cm³ |

La version 2 est plus compacte : elle utilise (75,8 − 52,4) / 75,8 = 23,4 / 75,8 ≈ 31 % de matière en moins.

## Boîte de rangement

![Boîte de rangement](rendus/squeeshie.jpg)

Boîte de 80 × 80 × 15 mm qui range un jouet, avec une empreinte en creux qui épouse sa forme. Sa forme organique, avec des parties fines et arrondies, était intéressante et compliquée à réaliser.

## Masse des pièces

Le volume se calcule directement à partir du maillage STL. Multiplié par la masse volumique du PLA (environ 1,24 g/cm³), il donne la masse maximale, celle d'une pièce imprimée pleine. La masse réelle est plus faible, car elle dépend du nombre de parois et du taux de remplissage.

| Pièce | Volume | Calcul | Masse maximale |
|---|---|---|---|
| Châssis | 4,45 cm³ | 4,45 × 1,24 | 5,5 g |
| Garde d'hélices | 13,61 cm³ | 13,61 × 1,24 | 16,9 g |
| Support de l'AIO | 2,15 cm³ | 2,15 × 1,24 | 2,7 g |
| Protection de l'AIO (v6) | 1,21 cm³ | 1,21 × 1,24 | 1,5 g |
| Support sel et poivre v1 | 75,83 cm³ | 75,83 × 1,24 | 94,0 g |
| Support sel et poivre v2 | 52,38 cm³ | 52,38 × 1,24 | 65,0 g |
| Boîte de rangement | 59,66 cm³ | 59,66 × 1,24 | 74,0 g |

## Imprimé, mais pas conçu par moi

J'ai aussi imprimé un châssis 2,5" compatible Kayoumini, téléchargé sur MakerWorld. Ses moteurs sont à 111,8 mm en diagonale. Ses fichiers ne sont pas dans ce dépôt, car ils appartiennent à leur auteur : [page du modèle sur MakerWorld](https://makerworld.com/fr/models/2745750).

## Licence

© Mattéo Pozzo di Borgo. Ces modèles sont mis à disposition sous licence **CC BY-NC-SA 4.0** (voir [LICENSE.md](LICENSE.md)).

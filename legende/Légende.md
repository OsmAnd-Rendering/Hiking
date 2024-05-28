# Légende
## Sentiers, chemins, pistes agricoles et forestières type IGN


### Sentier (`highway=path`) :
| Légende             | Apparence                                                                   |
|---------------------|-----------------------------------------------------------------------------|
| **Normal**<br>- Traits noirs plus large<br>- Forme allongé<br>- Adouci  | ![](jpg/Adoucit.jpg)     |
| **Accès « non ou privé »**<br>- Traits rouge-marron                    | ![](jpg/path-access.jpg) |


## Difficulté et visibilité des sentiers :
Ces deux paramètres se combinent jusqu’à un certain zoom. Au zoom 18 (50 m) la visibilité est désactivée, il ne reste plus que la difficulté qui est affichée.

### Couleur selon la difficulté « Échelle CAS » (`sac_scale=*`) :
- T1 noir discontinu
- T2 rose discontinu
- T3 rose continu
- T4 violet discontinu
- T5 violet continu
- T6 violet pointillé allongé

### Visibilité du sentier (`trail_visibility=*`) :
- Mauvais (`bad`) : pointillé
- Horrible (`horrible`) : pointillés plus espacés
- Non (`no`) : pointillé très espacés

![Légende `highway=path`](https://github.com/OsmAnd-Rendering/Hiking/blob/main/legende/jpg/L%C3%A9gende-FR.jpg)

### Chemin/Chemin agricole/piste forestière (`highway=track`) :
#### Grades 1 et 2 (`tracktype=grade1`/`grade2`)
| Légende                                                                                                         | Apparence                       |
|-----------------------------------------------------------------------------------------------------------------|:-------------------------------:|
| **Normal**<br>- Trait blanc plein avec traitillé noir sur les côtés | ![](jpg/tracktype-1-2.jpg)                                              |
| **Accès « non ou privé »** (`acces=private`/`no`)<br>- Traits rouge-marron | ![](jpg/track-1-2-access.jpg)                                           |

#### Grades 3, 4 et 5 (`tracktype=grade3`/`grade4`/`grade5`)
| Légende                                                                                                         | Apparence                       |
|-----------------------------------------------------------------------------------------------------------------|:-------------------------------:|
| **Normal**<br>- Trait noir plein | ![](jpg/tracktype-3-4-5.jpg)                                                                                      |
| **Accès « non ou privé »** (`acces=private`/`no`)<br>- Trait blanc plein avec trait rouge discontinu sur les côtés | ![](jpg/track-3-4-5-access.jpg) |



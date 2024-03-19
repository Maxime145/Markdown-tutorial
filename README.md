# Markdown tutorial

## Commentaires

Pour faire un bloc (de commentaire ou de citation) vous devez écrire : `> Mon commentaire`

> Mon commentaire

## Liens

### Texte

##### Solution 1

- `[My Link](https://github.com/)`
-  Résultat : [My Link](https://github.com/)

##### Solution 2

- Déclarer le lien : `[Markdown]: <https://guides.github.com/features/mastering-markdown/>`
- Appelez le lien `[Markdown]`
- Résultat : [Markdown]
> Pratique pour éviter d'alourdir la lecture du code

### Images

##### Fixe ou Gif

- `[![Nom du lien](Lien de votre image)](Lien vers lequel rediriger en cas de clique sur l'image)`
-  Résultat : [![Home](https://image4.owler.com/logo/web-savvy-marketing_owler_20160228_232231_large.png)](https://github.com/)
> Si votre image est sur votre ordinateur vous pouvez simplement glisser/déposer votre image, un lien va se créer directement.

##### Youtube

Syntaxe :
> `[![Nom de l'image](Lien de l'image youtube)](Lien de la vidéo "Nom de la vidéo")`

Exemple :
>`[![](http://img.youtube.com/vi/`__*ID OF VIDEO*__`/0.jpg)](https://www.youtube.com/watch?v=`__*ID OF VIDEO*__`"Un nom customisé")`

Résultat :
[![](http://img.youtube.com/vi/o77MzDQT1cg/0.jpg)](http://www.youtube.com/watch?v=o77MzDQT1cg "Super vidéo de Hytale")

Si vous le souhaitez, vous pouvez convertir facilement le lien youtube en image grâce à [embed youtube] 

## Listes

Vous pouvez utiliser le `-`, le `+` ou l'`*`. L'utilisation et le résultat sera le même pour tous.

```
- Item 1
  - Item 1.1
    - Item 1.1.1
- Item 2
  + Item 2.1
    * Item 2.1.1
```

> Il ne faut pas oublier de faire `2 espaces` avant chaque ligne pour définir un `sous item`

Résultat :

- Item 1
  - Item 1.1
    - Item 1.1.1
- Item 2
  + Item 2.1
    * Item 2.1.1

## Spoiler texte

```
<details>
  <summary>Titre</summary>
  
  Contenu...
</details>
```

Résultat : 

<details>
  <summary>Titre</summary>
  
  Contenu...
</details>

## Tableaux

```
| Nom | Valeur |
| - | - |
| Nom1 | Valeur1 |
| Nom2 | Valeur2 |
```
Résultat : 
| Nom | Valeur |
| - | - |
| Nom1 | Valeur1 |
| Nom2 | Valeur2 |

---

[étapes]: <https://github.com/Trenacia/-Get-an-image-link/blob/master/README.md>
[Markdown]: <https://guides.github.com/features/mastering-markdown/>
[embed youtube]: <http://embedyoutube.org/>

# Dictée de mots

## Quesako ?

Juste un utilitaire d'encodage pour apprentissage de l'écriture au cycle II ou EBP

## Actuellement
Clic gauche sur les lettres -> OK
Clic droit sur les lettres -> donne le phonème.
Base de données de mots et de sons associés
Rélaisation de cette base selon la **fréquence**, à adpater au cycle 2.

## Installation

# Depuis le git

```
git clone
./source/encoder-mots.py
```


# Depuis pkg

```
wget https://github.com/CyrilleBiot/encoder_mots/raw/master/encoder-mots_1.0_all.deb
dpkg -i encoder-mots_1.0_all.deb
```

Desinstaller

```
dpkg -r encoder-mots
```

## Todo
Fichier de mots avec possibilité de filtre par phonème. Style
bateau, [O]. Et parsing de ce fichier. La moulinette initiale a été abandonnée. A suivre.
Incrémenter la base de données par thèmes.
Pour l'instant, la fonction en fin de série est desactivée.
Proposer une solution en cas de mot faux.
Proposer des tips pour les lettres muettes, les consommes doubles...


## Screenshoots

![screenshoot](./screenshoot001.png)

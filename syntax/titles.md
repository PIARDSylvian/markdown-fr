# Les titres

Comme nous avons commencer a écrire un document markdown, nous avons besoins d'un titre et d'un sous titre..

Markdown suporte deux type d' entete, Setext and atx.

Setext-style d' entete sont souligné par les signes égal (pour le premier nieveau d'entete) est des tirets (pour le second niveau d' entete). Par exemple: 

```
C'est un H1
=============

C'est un H2
-------------
```

Tout nombres sousligné par = ou - fonctioneras.

Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:
Atx-style d'entete utilise de 1-6 characteres dièse au debut de la ligne, est correspond à l'importance de l'entete. Par exemple:

```
# C'est un H1

## C'est un H2

###### C'est un H6
```


Optionnellement, vous pouvez "fermer" un entete atx-style. C'est purement cosmetic — Vous pouvez l utiliser si vous pensez que sa rend mieux. Les diéses de fermeture, ne dont pas obligatoirement du même nombre. ( le nombre de dièses qui ouvre de termine l'importance de l' entete) :

```
# C'est un H1 #

## C'est un H2 ##

### C'est un H3 ######
```


---

Voici un questionnaire sur les titres markdown.

Selectionne le header valide:
- [x] `# hello`
- [ ] `#hello`

> Le Header a besoin d'un espace entre le caractère dièse est le texte.

Selectionne le header valide:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Seulement le '=' et '-' sont accepter pour souligné un header.

---

# mergeconflictopdracht

## doelen:
Maak van 3 verschillende merge conflicten
- deleted file
- zelfde regel
- nieuwe regels beide houden
Los deze op


## voorbereiding
- met je groeps genoot kies je in welke github account je gaat samenwerken, deze noemen we student 1
- student 1 forked deze repository
- student 1 nodigd student 2 uit
- student 2 cloned de repo van student 1
- student 1 werkt op de main
- student 2 maakt een nieuwe branch met de naam feature
```
git branch feature
```
- student 2 checked feature uit

```
git checkout feature
```
- student 2 pushed deze meteen even naar de repo
```
git push --set-upstream origin feature
```

## oefening: deleted file
- student 1 werkt op main
- student 2 werkt op feature

- student 1 past oldgreeting.js aan, zet een andere (nette!) tekst als greeting neer
- student 2 maakt een newgreeting.js aan, en maakt een newgreeting function, met dezelfde tekst als de oude oldgreeting.js
- student 2 delete oldgreeting.js

- student 1 + 2 commiten hun werk

- push!
- pull alletwee
- student 1 doet een checkout van feature:
```
git checkout feature
```
- student 1 doet een pull
```
git pull
```
- student 1 doet een checkout van main:
```
git checkout main
```
- bij student 1 mergen we nu feature in main
```
git merge feature
```
- los samen het merge conflict op
- add, commit, push
- pull alletwee


## oefingen: dezelfde regel
- student 1 werkt op main
- student 2 werkt op feature

- de basicHaiku vinden we saai
- verander alletwee 1 van de 3 strings in de array (zie hieronder), overleg wie welke veranderd
```
["Toward those short trees","We saw a hawk descending","On a day in spring."]
```
### regel nummers:
- string 1 = Toward those short trees
- string 2 = We saw a hawk descending
- string 3 = On a day in spring.


- student 1 + 2 commiten hun werk
- push!
- pull alletwee
- student 1 doet een checkout van feature:
```
git checkout feature
```
- student 1 doet een pull
```
git pull
```
- student 1 doet een checkout van main:
```
git checkout main
```
- bij student 1 mergen we nu feature in main
```
git merge feature
```
- los samen het merge conflict op, zorg dat jullie beide changes blijven bestaan
- add, commit, push
- pull alletwee




## oefening: 
- student 1 werkt op main in main.js
- student 2 werkt op feature in main.js

- maak alle twee `1 haiku function erbij` net als basicHaiku
- noem de function `student1Haiku` of `student2Haiku`. Afhankelijk van welke rol jij hebt
```
zie https://github.com/progsen/haikugitopdracht voor ideeen
```

- student 1 + 2 commiten hun werk
- push!
- pull alletwee
- student 1 doet een checkout van feature:
```
git checkout feature
```
- student 1 doet een pull
```
git pull
```
- student 1 doet een checkout van main:
```
git checkout main
```
- bij student 1 mergen we nu feature in main
```
git merge feature
```
- los samen het merge conflict op
- add, commit, push
- pull alletwee

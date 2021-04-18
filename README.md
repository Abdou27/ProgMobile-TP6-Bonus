# ProgMobile-TP6-Bonus
Exercice 4 (Bonus) du TP6 du module Programmation Mobile en L3 à l'université de Tours

J'ai changé la ligne d'instatiation de mWordViewModel parceque la ligne du codelab a fait planter l'application au démarrage.
```java
mWordViewModel = new ViewModelProvider(
                        this,
                        ViewModelProvider.AndroidViewModelFactory.getInstance(this.getApplication())
                        ).get(WordViewModel.class);
```

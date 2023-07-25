## Exercice JavaScript - Calcul de la factorielle avec récursivité

### Objectif
L'objectif de cet exercice est de créer une fonction en JavaScript qui calcule la factorielle d'un nombre en utilisant la récursivité. Vous devrez également tester votre fonction à l'aide de Jest, un framework de test pour JavaScript.

### Instructions
1. Créez une fonction appelée `factorielleRecursive` qui prend un seul paramètre `n` (un nombre entier positif ou nul) et retourne la factorielle de `n` en utilisant la récursivité.

2. Avant d'entrer dans le processus récursif, vérifiez que n est un nombre entier positif. Si ce n'est pas le cas, la fonction doit retourner false.

3. Assurez-vous d'ajouter une condition de base pour mettre fin à la récursivité lorsque `n` est égal à 0. Dans ce cas, la fonction doit retourner 1.

4. Sinon, la fonction doit retourner `n` multiplié par le résultat de l'appel récursif de `factorielleRecursive` avec `n-1`.

5. Testez votre fonction à l'aide de Jest en écrivant au moins trois cas de test. Un cas pour vérifier que la fonction retourne false si le nombre donné en paramètre n'est pas un nombre entier positif, un cas de test pour vérifier le calcul de la factorielle d'un nombre positif et un autre cas de test pour vérifier que la factorielle de zéro est égale à 1.

### Documentation
- [Documentation sur la factorielle](https://www.studysmarter.fr/resumes/mathematiques/algebre/factorielle)
- [Documentation sur Jest](https://jestjs.io/fr/docs/getting-started)
- [Documentation sur Javascript](https://developer.mozilla.org/fr/docs/Web/JavaScript)

### Exemple d'utilisation de la fonction
```javascript
const resultat = factorielleRecursive(5);
console.log(resultat); // Output: 120
```

### Conseils
- Vous pouvez consulter les liens de documentation fournis pour vous aider à comprendre la factorielle et Jest.
- N'hésitez pas à rechercher des exemples de fonctions factorielles récursives en JavaScript pour vous inspirer.
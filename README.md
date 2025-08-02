# algorithms
Variables:

- wordCount ← 1
- vowelCount ← 0
- c ← caractère  
- sentence ← chaîne de caractères
- 
Begin

1. Afficher "Entrer une phrase qui se termine par un point : "
2. Lire sentence
3. Pour chaque c dans sentence faire :
   - Si c = ' ' alors  
     → wordCount ← wordCount + 1
   - Sinon si c ∈ {a, e, i, o, u, A, E, I, O, U} alors  
     → vowelCount ← vowelCount + 1
   - Si c = '.' alors  
     → Arrêter la boucle
4. Afficher "Number of words: ", wordCount
5. Afficher "Number of vowels: ", vowelCount
6. end

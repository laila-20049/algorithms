# algorithms
Variables:
  wordCount (= 1
  vowelCount (=0
  charCount (=0
  c (=character
  sentence (=string

Begin
  Display "Enter a sentence that ends with a period:"
  Read sentence

  For each c in sentence do:
      charCount (=charCount + 1

  If c = ' ' then
  wordCount (= wordCount + 1

   Else if c ∈ {a, e, i, o, u, A, E, I, O, U} then
          vowelCount (= vowelCount + 1

   If c = '.' then
          Exit the loop

  Display "Number of characters: ", charCount
  Display "Number of words: ", wordCount
  Display "Number of vowels: ", vowelCount
End


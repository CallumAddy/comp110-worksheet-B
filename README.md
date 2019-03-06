# comp110-worksheet-B
Base repository for COMP110 worksheet B
Flowchart : https://i.gyazo.com/b68962d571eda753bd6c580d63054c78.png

points = 0
secretWord = "Yeet"
firstLetter = secretWord[0]
secondLetter = secretWord[1]
thirdLetter = secretWord[2]
fourthLetter = secretWord[3]
print ("What is the first letter?")
firstLetterGuess = input()
print ("What is the second letter?")
secondLetterGuess = input ()
print("What is the third letter?")
thirdLetterGuess = input ()
print ("What is the fourth letter?")
fourthLetterGuess = input ()
print("Your guess was: " + firstLetterGuess + secondLetterGuess + thirdLetterGuess + fourthLetterGuess)

for(int i = 0; i++; i < secretWord.length)
{
  if secretWord[i] == guess[i]
      points += 1
}
  if points equals 4
    print ("You got the word right, well done!")
    else 
  print("You got " + points + " out of 4 letters correct, try again!")
  
  


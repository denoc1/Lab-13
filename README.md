# Lab-13  Word Search with While

**This lab should only use String methods already covered in the class.**

Have the user enter a sentence.  Store the sentence as a String.
Then have the user enter a “word” (i.e. a string – it doesn’t have to be a word in the English language).
Your program will return:
-	The character before and the character after the first occurrence of the “word”.
-	If the character referenced is a space, the program will state that it is a space.  
-	If there is nothing before the word, the program should say the word is at the beginning of the sentence.
-	If there is nothing after the word, the program should say the word is at the end of the sentence.
-	If the “word” is not contained within the sentence, the program should say that the “word” was not found.
Once you have this working, add a WHILE loop to the code that allows the user to repeat the process as many times as they want to.  You decide what the user uses to indicate they are finished.

As usual:

- Use header comments containing your name, the names of anyone that assisted you, the date, and a description of the program.
	
- Use comments throughout the program documenting the different aspects of your code.

Here is some sample output. 


    Enter a sentence.
      the quick brown fox jumped over.
    Enter a word in your sentence.
      ver
        
    Your sentence was... the quick brown fox jumped over.
    Your word was... ver
    The character before your word is o
    The character after your word is .
    Would you like to try again? Y or N?
      Y
    Enter a sentence.
      The quick brown fox jumped over.
    Enter a word in your sentence.
      The
        
    Your sentence was... The quick brown fox jumped over.
    Your word was... The
    Your word is at the beginning of the sentence.
    The character after was a space.
    Would you like to try again? Y or N?
      Y
    Enter a sentence.
      The quick red fox was extremely fast
    Enter a word in your sentence.
      ox
        
    Your sentence was... The quick red fox was extremely fast
    Your word was... ox
    The character before your word is f
    The character after was a space.
    Would you like to try again? Y or N?
      N
        




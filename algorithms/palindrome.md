Algorithm for palindrome. Use this psuedocode to curate a working solution.

Take in the word or phrase from the keyboard and save it to be used at the end of the program.

for(every character)
    if(character is letter) //i.e. ignore spaces and puctuation 
        add to new string

for(everycharacter/2)
    compare current character to subsequent character at the end of word

    if the same continue to next character
    else set increment variable to past end to exit loop and mark flag to be true

if flag
    //print word is not palindrome
else
    //print word is palindrome
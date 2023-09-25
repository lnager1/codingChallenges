Algorithm for binarySearch. Use this psuedocode to curate a working solution.

Load file into array
take in value user is looking for

define and initialize low, mid, high, position
    //define position to be flag value from start

while low if less than high
    update middle

    if user value is found at middle 
        exit loop and update position

    if user value is greater than middle
        update low

    else
        update high

if flag is not equal to original flag value 
    print found at given position
else
    print that it is not in the array 
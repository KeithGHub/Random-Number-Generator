(THIS PROJECT WAS ORIGINALLLY UPLOADED ON 11/29/2023)

This is my first coding project I've ever created in order to get my feet wet

BELOW IS THE PROCESS OF TRIAL AND ERROR TO CREATE THIS RNG PROJECT:

What Do I Know

- I want to make a random number generator
- I'd like this generator to produce any number within the range from "1 through 15"
- I know from prior research I must use the "RANDOM" function in this case
- I know from prior research I need to include is the lowest and the highest number from my selected numbers

This'll be my first attempt below to create said generator

random (1,15)

- When ran in the terminal this was the output: "NameError: name 'random' is not defined"
- My approach was using the "random" function and in parentheses including the lowest - highest number (1 and 15)
- That did not work - I decided to do research on Google to see why the specific error was popping up
- Apparently the main solution to my issue that I found was failure to include the "import" function
- Before using the "random" function I MUST include the "import" function first within my code

import random

- In the midst of thinking up missing things I realized I'm lacking a value for the function being used (x)
- I did also look up a video to assist me in the specific area of my error - "random.randint" is needed
- To finalize everything I needed to also print the value of x

x = random.randint(1,15)
print(x)

- The result when ran is a number between 1 and 15 will be the output shown in the terminal
- Where I became stumped is when I reached the phase where functions are needed (random.randint)
- I also forgot that a print function was required in the end to define x
- I forgot a lot of key pieces to make this specific project run - I did give a better effort to get a solution

I'll create another RNG just for good measures below

import random
y = random.randint(10,1000)
print(y)

The terminal will output a random number for the second RNG between 10 - 1000

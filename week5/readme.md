
__Lecture Notes__


- Shallow indentation is a good use to simplify the code which can be done by the functions and also through different expressions.
- Simplifying Code will make it easier to read and to understand in future reference



__Exercise #1__

Countdown
A Complicated / Messy code can be simplified within the excercise by just using a countdown rather than using 10 prints. This is much more convenient

For the Triangle exercises
                            
        To make it work, made a new variables and did a simple maths function in order to find the area / Perimeter / Aspect 
        Used ** for base raised to the power of 2
        Used * for representing Times
        Used {} to modify inside variables
        
        Formula
        Hypotenuse = (Base^2 + Height^2)^2 Divided by 1/2
        Area = Base x Height / 2
        Perimeter [Had to Google this for the formula] = ((Base x Base) + (Height x Height)) ^1/2 + Base + Height
        Aspect was the most difficult one which i had to ask my friends for help as i had no clue in how to do it at all :(
            Update: I finally understand now and how it works is with a If / elif / else function which would ultimately calculate it

        Overall it was basically a maths function with the mix up of Python



__Triangle Master__

 - Not much to do except to simplify the code itself with if / elif and else functions which i really found out that it cuts the code by almost half and makes it MUCH more easier to read.



__Wordy Pyramid__

 - I attempted to do it but i do not understand and i am still stuck...



__Get a word and List_Of_Words__
    For this part of the exercise, it took me more than 3 hours to complete and fully understand. Part of this was due to me being forgetting to update the exercises which lead to me being stuck with the old tests which i could not debug properly. However, these 2 parts basically is like importing JSon like in week 4 which takes time to understand. 

    __For the Get a word__
    1. Import request
    2. Put the URL in which is from the US-Central
    3. Make the statement of If type(length)
    4. Link formating
    5. Request to get the link
    6. Make a request status code 
    7. Name anything as the content and make it as a "STRING" 
    8. Do [2:len(message)-1] which acquires the words from the url and name it with anything
    9. Return and finished.

    __List_Of_Words__
    1. Import request
    2. Put the URL in which is from the US-Central
    3. Make a list
    4. Link formating
    5. Request to get the link
    6. Make a request status code 
    7. Create the message like last one but no need to make a string
    8. Do list append
    9. Return the list and finished.



__Exercise #2__

Changing Words For Recursion
    To do the abba exercise it was basically using the code from the example and applying changes towards the one that was required. It took abit of changes for it to work however. 

        EG:
        result = list(map(italian_rules, parts))
        Changed to 
        result.append(apply_rules(i, guard)) 
    
    This is done because abba is a list and in order to create these map, we need to create a recursion that allows abba to be transformed into the required wordings hence for the use of result.append. Other than that, there are nothing much to be changed other than some simple logic as well as the if/elif statement which i found a little bit challenging.


__Square Koch__
 - The Square Koch was very simple after reading the example provided. As every turn of the Square is 90 Degree, so all i had to do was change the values to 90 degrees as well as changing the koch name to square_koch and it's done.



__Important Notes__
 1. Status Code always set it as 200 
 2. == Means Is
 3. ** Means ^2
 4. * Means x
 5. Recursion basically means a new input function

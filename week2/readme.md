#Exercise #0

For Spacing, you can do string + ' ' + str(a_number) 
        
        ' ' <----Represents spacing
        str(a_number) <------Number or anything added


The Expression == can mean "Is" EG -> If moves is true [ If Moves == True ]





#Exercise #2

Exercise 2 was easy, because running the debug console basically solved everything that wasn't working and helped me identified majority of the issues which were capital letters and punctuation errors as well as missing : and ().





#Exercise #3
Odd and Fix_It Exercise were fairy simple which required the If + Else solutions. For the Fix it, it required a little bit more work as it required more logical thinking while doing it.

To Do A Range, you must do 
List = [] <------- Creates a list
for i in range of (10) <-------- Make any item such as i and if it is in the range of 10
    list.append(*) <------- This will create 10 stars in the range of 10
return List <----- Finally return the list that we made to get the stars finished

For Making more complicated List, it is required to do 2 lists and this can be done by doing the loop within the first loop. 

        Example (Not Spaced Properly):

            list1 = []  <----First Loop
            for i in range (10): <--- Range of 10 means 1 to 9
            list2 = []  <------Making the second loop within the first loop
            for a in range (i+1): <------Since range is 10, it means 1-9 and i+1
            list2.append(str(a)) <--- Using a string             
            list1.append(list2) <----- The 2 Lists combines
            return list1 <---- Returns the list and it's finished.

The last one which created the Pyramid required more of a Mathematical Solution which was slightly annoying as it was very hard to solve at first.

How to do it:
        -> It is required to make a range between 1 and 6 and gradually move on
        -> The Maths solution is if a > y - i and a < y + i which would provide us with the shape of a pyramid.
        -> An Else function is crucial as we need to create empty spaces otherwise it would not become a pyramid. 
        -> Lastly, x = x+1 is also needed as we need to move gradually to make the pyramid and finally list.append and it's done.


To Use the command a_number_of_items, you must include first a (int(a_number_of_items)) as numbers are integrals and it is required otherwise it will not work.

str(), int(), creating range between numbers are all solutions to be used for lists.

#Important Notes
 1. Always remember to put : otherwise will result in Syntax error
 2. == basically means is 
 3. Spacing is crucial
 4. INT is required to do number_of_items
 5. Harder loops sometimes require Mathematics solutions to complete them
 6. Always should return the Answer in order to make it function
 7. To create something in capital letter, it can be done by a_string.upper()
 8. To add another expression onto the current capital letter string, you must do the string + '!'

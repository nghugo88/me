-------------------------------------Exercise #1-----------------------------------------------
For Spacing, you can do string + ' ' + str(a_number) <----- The Number Or Anything added
                                  ^----Represents spacing

The Expression == can mean "Is" EG -> If moves is true [ If Moves == True ]

[b] Exercise #3 [/b]
To Do A Range, you must do 
List = [] <------- Creates a list
for i in range of (10) <-------- Make any item such as i and if it is in the range of 10
    list.append(*) <------- This will create 10 stars in the range of 10
return List <----- Finally return the list that we made to get the stars finished


To Use the command a_number_of_items, you must include first a (int(a_number_of_items)) as numbers are integrals and it is required otherwise it will not work.

For Making more complicated List, it is required to do 2 lists and this can be done by doing the loop within the first loop. 
    Example:
        list1 = []          <------ [ First Loop]
    for i in range (10):
        list2 = []    <----------- [ Making the second loop within the first loop]
        for a in range (i+1):            <---------Since range is 10, it means 1-9 and i+1
            list2.append(str(a))                   would mean 0+1, 0+2 and the list goes on
        list1.append(list2)
    return list1

str(), int(), creating range between numbers are all solutions to be used for lists.

Important Notes
 1. Always remember to put : otherwise will result in syntax error
 2. == basically means is 
 3. Spacing is crucial
 4. INT is required to do number_of_items
 5. Harder loops sometimes require Mathematics solutions to complete them
 6. Always should return the Answer in order to make it function
 7. To create something in capital letter, it can be done by a_string.upper()
 8. To add another expression onto the current capital letter string, you must do the string + '!'

-------------------------------------Exercise #1-----------------------------------------------

Get_Some_Details:
        Doing the details one were quite straight forward after receiving help from Ben and his tips. In order to do it step by step
        
        1. Start with opening the Json file which is given in the script
        2. Load the data by doing data = json.loads(json_data)
        3. Get the format ready -> something = data["results"[0]["name"]["last"]
        4. Use the information given from the website and complete the lastname and password.
        5. Post code is a little bit different as it required 2 data to integer to create together followed by the final postcodePlusID
        6. Finally return everytjhing we have gotten with the names and it's finished

    Notes: 
    -> Json_data should have been in the first line which allows us to use it to continue.
    -> There's a [0] because it is the category [0] that we get from randomname.org
    -> The ["name"] and ["last"] are just the names and variables given to us from the website
    -> Postcode required 2 things which is

            A = data["results"][0]["location"]["postcode"]
            B = data["results"][0]["id"]["value"]
            PostcodePlusID = Int(A) + Int(B) 

Summary: The reason i wrote step by step is because i found W4 extremely hard to cope with so i made this step by step so i can do it easier with more logical thinkings the next time i do it.


Pokedex:

        Doing the Pokedex was hard at first but after doing research online as well as using the Get_some_Details as an example helped me eventually finish this part of the exercise.
        
        1. Get the template of the Pokemon link
        2. Make a variable of Weight and height and make it equal to any integers 
        3. We need a name for the "unknown" pokemon so make a name = ""
        4. Creating a Range function so (low,high)
        5. Now make a similar URL request similar to Get_details and also status code
        6. Load up the text by doing the_json = json.loads(r.text)
        7. Create a if function of he two and followed by height and weight
        8. Then name = the_json["name"] which will name the pokemon
        6. Finally return everything we have gotten with the names and it's finished

    Notes: 
    -> Need to find the Weight and height so we need it in the beginning 
    -> We need the status code from the website otherwise it won't load


Important Notes
 1. Json requires importing first before doing anything else.
 2. 
 3. 
 4. 
 5. 
 6. 
 7. 
 8. 
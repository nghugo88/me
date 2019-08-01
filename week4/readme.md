#Exercise #1

##Get_Some_Details:
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


##Pokedex:
        
        1. Put the template of the Pokemon link
        2. Make a variable of Weight and height and make it equal to any integers 
        3. Creating a Range function so (low,high)
        4. Now make a similar URL request similar to Get_details and also status code
        5. Load up the text by doing the_json = json.loads(req.text)
        6. Create a if function of the two and followed by height and weight
        7. Then name = the_json["name"] which will name the pokemon
        8. Finally return everything we have gotten with the names and it's finished

    Notes: 
    -> Need to find the Weight and height so we need it in the beginning 
    -> We need the status code from the website otherwise it won't load


##Diarist
    - The diarist pretty much involved knowledge from Week 3's exercise 1 as well as previous exercises listed on Week 4's exercise 1. Going through it was ok but it took time to understand each concept by concept.


#Important Notes
 1. Json requires importing first before doing anything else.
 2. Useful tools for Importing json -> jsoneditoronline.org

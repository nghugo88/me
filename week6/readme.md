
Machine Learning can be done in a varieties of way, i think using the If Loop is one of the best method to do it as we have learnt it before in tutorial and during lab. This can be done by stating the statement "If your arms are higher than your neck" Print the hail taxi image. Another statement can be seen as "If your elbow are higher than your shoulder" call taxi. Etc.

            NeckY = 0      
            RElbowY = 0
            LElbowY = 0
            for k,v in human.body_parts.items():
                print([(POSE_COCO_BODY_PARTS[k], v.x, v.y)])
                if POSE_COCO_BODY_PARTS[k] == "Neck":
                    NeckY = v.y
                if POSE_COCO_BODY_PARTS[k] == "RElbow":
                    RElbowY = v.y
                if POSE_COCO_BODY_PARTS[k] == "LElbow":
                    LElbowY = v.y
            if RElbowY < NeckY:
                hail_taxi(image)
            elif LElbowY < NeckY:
                hail_taxi(image)

    So first i created the Neck, elbows as the main parts of the code, then followed by the human parts as well as printing of the x and y coordinates. After that, i basically wrote how each body parts is which and how their coordinates. Finally i've used a If/Else statement which means If the right elbow is above the neck, it will print TAXI or else if the left elbow is above the neck it will also print the taxi image. 


    Update: I am not sure why i have only received 4 marks for ML on the marking of google spreadsheet when everything was working.
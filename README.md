<<<<<<< HEAD
# project-chatbot-rasa

### Requirements:
-rasa 3.x </br>
-tensorflow </br>
-ujson

## How to run nlu server to parse text

1) rasa run --enable-api -m nlu-20220323-135458-moist-supervisor.tar.gz
2) send *POST* request to http://localhost:5005/model/parse in **JSON** format
</br></br>
Examples:</br>
![image](https://user-images.githubusercontent.com/54878524/156889864-5ba8b350-f957-4e21-8ae0-23a4574aff0a.png)</br>
Response:</br>
![image](https://user-images.githubusercontent.com/54878524/156889907-6e68ab80-8268-49f4-8fa6-89237f9e4430.png)
=======
# Project_Chatbot_w-_RASA
Chatbot for Compensation Fund Services Project
student name
- Ratchanon Kitcharoen DSBA KMITL
- Rung Khonyuen DSBA KMITL 

# Requirements
- tensorflow
- rasa 3.x
- ujson

# running an nlu server (run model)
  first, run the model that you want by copy a name at "models" file and run in cmd
  for an example: rasa run --enable-api -m models/nlu-20220322-140907-rude-buyer.tar.gz
 
  second, send POST request to http://localhost:5005/model/parse in JSON format
  
>>>>>>> 7394a7896b5728cebd4948445a453188825f0192

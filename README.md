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
  

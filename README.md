# DL_ML_Chatbot

# the three Main files here is 1st of intents.json, that collect data structure as tag, pattern and responses in obj of intents
# fist of all thing, import all of libraries framework model
# in internal>Botchat> pip install ........

________________

# open and Run TrainData_Data_NueralNetwoerk.py
# this file.py will save additional files as word.pkl, classes.pkl and chatbot_model.h5

# last open and run BotTrainChat_ML.py
# this file will open model from chatbot_model.h5 then use it as variable model
# this BotTrainChat.py have function to clean_up_sentence(sentence), bag_of_words(sentence), show_details=True), predict_class(sentence), getResponse(intents_list, intents_json) and last combine those in one function bot_to_chat

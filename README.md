# Chat_Bot
Rasa based Chatbot with the 
pipeline:
 - name: "intent_featurizer_count_vectors"
   token_pattern: '(?u)\b[a-zA-Z][a-zA-Z]+\b'
 - name: "intent_classifier_tensorflow_embedding"
   intent_tokenization_flag: true
   intent_split_symbol: "+"


# Chatbot_Langchain

1. mental_health_training.csv is the CSV file containing the mental health dialogue training data.
   During the project, we put it into the vector database to form the RAG system, split the data inside into chunks, and then use text embedding model to transform them into vector. 
2. chatbot_openAI.ipynb is the openAI model version of the chatbot, where we use openAI GPT 4 model to text embed the CVS dialogue data, generate conversation based on user's input. And e use GPT 4 model to form a prescription based on the dialogue between the user and the chatbot, to show what is the cause of user's mental problem, what is the symptom, and how to solve it. We also use NTLK package to define a sentiment analysis tool, and integrate it into the chatbot pipeline. If the user's input is too negative, the chatbot will raise the message like "please find professional mental assistance!". 
3. openai_chatbot_demo.txt contains the demo of the open version of the chatbot. 
4. chatbot_hugging_face.ipynb is the hugging face version of the chatbot. We use hugging face model to do the text embedding, dialogue generation and we use BART model to generate prescription. Since hugging face model cannot be combined with own-defined tools, in this version there is no sentiment analysis tool. 
5. huggingface_chatbot.demo.txt contians the demo of the hugging face version of the chatbot.
6. The dox file shows the basic pipeline of the Langchian_RAG_LLM chatbot  workflow. 



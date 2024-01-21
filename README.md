
# Generative AI : Question Anserwing App using Atlas Vector Search + RAG Architecture

### Steps:
- We Use load_data.py file to load the sample text file into to vector store to create vector embeddings in Mongo DB
- Then we use extract_information.py file for further processing
- We use LangChain to implement RAG
- We sent the previously generated embeddings as context along with the query to generate the output
- we use gradio to create the UI. The application will run in, http://127.0.0.1:7860/


![Model](https://github.com/sufHub/gen_ai_QnA/blob/master/RAG.JPG)

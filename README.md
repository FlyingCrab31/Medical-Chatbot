# Medical-Chatbot

This project implements a medical chatbot using a combination of powerful technologies for natural language processing (NLP) and generative AI. 

### Features

* **Informative Responses:** Leverages the Meta Llama-2 large language model to understand user queries and provide informative answers on various medical topics.
* **Pinecone Integration:** Utilizes Pinecone's vector database for efficient retrieval of relevant medical information based on user input.
* **User-Friendly Interface:** Built with a Flask framework for a web-based interface, featuring HTML and CSS for a clean and intuitive user experience.

### Technologies Used

* Programming Language: Python
* Backend Framework: Flask
* NLP & Generative AI: Meta Llama-2
* Deep Learning Framework: PyTorch (for Meta Llama-2)
* Vector Database: Pinecone
* Frontend: HTML, CSS

### Installation

1. create a virtual environment(use anaconda)
2. clone the repository and open in terminal
3. run command 'pip install -r requirements.txt'
4. create a .env file at the root directory and add your pinecone credentials as :
        PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
        PINECONE_API_ENV = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
5. download 'llama-2-7b-chat.ggmlv3.q4_0.bin' from the link : https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
        and create a folder in root directory named 'mode' and paste the downloaded file inside this model folder.

### Running the Chatbot

1. run command 'python store_index.py'
2. run command 'python app.py'
3. the above command will create a link open it on your browser and you are ready to chat. 

**Note:** This is a basic setup guide. Refer to the project code for more specific instructions and potential configuration options.

### Disclaimer

This medical chatbot is intended for informational purposes only and should not be used as a substitute for professional medical advice. Always consult with a licensed physician for any health concerns.

# Chatbot Implementations with Langchain & Streamlit  

This is my personal side project where I explore chatbot implementations using **Langchain** and **Streamlit**. Langchain provides a powerful framework for building AI-driven applications with Language Models (LLMs), while Streamlit helps create interactive web-based interfaces for these chatbots.  

## 💡 Chatbot Use Cases  

I've implemented various chatbot functionalities to test and expand Langchain's capabilities. Here are some of them:  

- **Basic Chatbot** – A simple chatbot that interacts with users using an LLM.  
- **Context-Aware Chatbot** – Maintains conversation history for more meaningful interactions.  
- **Chatbot with Internet Access** – Fetches real-time information from the web.  
- **Chat with Your Documents** – Allows users to upload documents and ask questions based on their content.  
- **Chat with SQL Database** – Interacts with databases using natural language queries.  
- **Chat with Websites** – Retrieves and summarizes website content based on user queries.  

## 🚀 Streamlit App  

I built a multi-page **Streamlit** app showcasing these chatbot implementations. You can try it out here:  
🔗 [Try it here](https://hemanth-thaluru-llm.streamlit.app)  


## 🛠️ Running the Project Locally  

If you want to run the chatbot locally, follow these steps:  

```shell
# Start the Streamlit app
streamlit run Home.py
```

## 🐳 Running with Docker  

To containerize and run the chatbot using Docker:  

```shell
# Build the Docker image
docker build -t langchain-chatbot .

# Run the Docker container
docker run -p 8501:8501 langchain-chatbot
```
# LoLytics
# LoLytics: Generative AI Analytics for League of Legends

### Concept and Aspiration of LoLytics

LoLytics is at the beginning of its journey to become a sophisticated analytics platform that compiles vast amounts of data, including matchID and RiotID, linked to players' PUUIDs. The purpose of gathering this information is to create a solid foundation for advanced machine learning models. These models are designed to extract significant insights from various data features. The insights will then be integrated into Llama3, an open-source Large Language Model (LLM), with the aim of transforming it into a virtual coach tailored for players in lower elo brackets.

The application has several components. Initially, I need to determine the features to build into a Deep Neural Network. Considering much of the data will be unsupervised, it is also crucial to figure out how to interpret the model's findings in a coherent way. My plan involves utilizing high elo gameplay metrics as a benchmark and comparing them with the outcomes from my Deep Neural Network. Following this, I intend to implement a Retrieval-Augmented Generation (RAG) framework using tools like LangChain and vector databases such as Pinecone. This will enable us to perform searches that are semantically similar to user queries.

By combining these technologies, LoLytics will be able to process user inquiries with remarkable semantic accuracy, providing advice that is highly relevant to each player's distinct experiences and challenges. Ultimately, I am building this repository to serve as an attempt to create an AI coach that offers guidance as insightful and individualized as that of a human mentor, aiming to enhance the strategic skill set of league players.

## Getting Started
To get started with LoLytics, clone the repository and follow the setup instructions below:

```bash
git clone https://github.com/yourusername/LoLytics.git
cd LoLytics
# Follow setup instructions for your project

# LoLytics
# LoLytics: Generative AI Analytics for League of Legends

### Concept and Aspiration of LoLytics

LoLytics is currently in its initial development phase, however it is envisioned to be a sophisticated analytics platform that is  designed to compile an extensive amount of matchID and RiotID data associate with various PUUID's. The goal of aggregating all this infomration serves as the base for advanced machine learning models that are engineered to derive meaningful outputs from that different features. These results will be infused into a Llama3, an open source Large Language Model (LLM), by a Retrieval-Augmented Generation (RAG) framework with the goal of transforming it into a virtual coach for low elo players.

There are multiple pieces to this application. First I need to figure out which features I plan on building a Deep-Neural Network. Since a lot of this data will be unsupervised, I also need to figure out how to translate model results to something that makes sense. I currently am aiming to utilize high elo gameplay metrics and ideal results and comparing that to the metrics from my DNN. Once I have successfully done this I need to use these results and implement RAG functionality with LangChain and vector databases like Pinecone to perform similary searches based on user queries. 

This combination will enable LoLytics to process user inquiries with unparalleled semantic precision, offering responses that resonate deeply with the player's unique experiences and challenges. In essence, it's about crafting an AI coach whose guidance is as perceptive and personalized as that of a human mentor, dedicated to elevating the player's strategic finesse in League of Legends.

## Getting Started
To get started with LoLytics, clone the repository and follow the setup instructions below:

```bash
git clone https://github.com/yourusername/LoLytics.git
cd LoLytics
# Follow setup instructions for your project

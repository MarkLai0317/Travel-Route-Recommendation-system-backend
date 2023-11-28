# Backend of the system 
* node.js source code
  * autocomplete service
  * direction and tourist spot recommendation service
    
* This repository contains Python code for constructing the data layer of a recommendation system. The focus is on enhancing the quality and relevance of data used for making recommendations, particularly in the context of tourist attractions.

  * Features
    * Sentence Embedding using SpaCy: We leverage SpaCy, a powerful NLP library, to obtain sentence embeddings. This approach enables us to capture the semantic richness of user comments, which is crucial for accurate recommendations.
    
    * Comment Filtering: To ensure the reliability of our recommendation system, we implement a sophisticated filtering mechanism. This process involves identifying and excluding comments about tourist spots that are not pertinent to the decision-making process of the recommendation system. By doing so, we maintain a high standard of data relevance and quality.

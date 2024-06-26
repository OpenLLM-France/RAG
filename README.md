# RAGondin 

RAGondin is the project dedicated to experiment with advanced RAG (Retrieval-Augmented Generation) techniques to improve the quality of such systems. We start with vanilla implementation and will build up to more advanced techniques to address many challenges and edge-cases of RAG applications.  

![](RAG_architecture.png)

## Goals

- Experiment with advanced RAG techniques
- Develop evaluation metrics for RAG applications
- Collaborate with the community to innovate and push the boundaries of RAG applications

## Usage

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/OpenLLM-France/RAGondin.git
   ```

2. Install the necessary dependencies listed in the requirements.txt file:

   ```
   pip install -r requirements.txt
   ```

3. Run the Qdrant docker container:

   ```
   docker run -p 6333:6333 -v $(pwd)/data/qdrant/storage:/qdrant/storage    qdrant/qdrant
   ```

4. Experiment with implementations and contribute back to the repository.

## Contribute

Contributions to this repository are welcomed and encouraged!

## Disclaimer

This repository is for research and educational purposes only. While efforts are made to ensure the correctness and reliability of the code and documentation, the authors cannot guarantee its fitness for any particular purpose. Use at your own risk.

## License

This repository is licensed under the MIT License  - see the [LICENSE]() file for details.

# Vertex AI experiments with LangChain

- Basic experiments using LangChain with Vertex AI
- [hello world example](https://github.com/ryanmark1867/vertexai_langchain/blob/master/hello_world.py), based on [LangChain documentation](https://python.langchain.com/en/latest/modules/models/llms/integrations/google_vertex_ai_palm.html) shows how you can invoke the PaLM 2 model in the context of Vertex AI.
- To run this example directly from Cloud Shell, enable the Vertex AI API in the project you are using and install the prerequisites:

 ```
 pip install langchain
 pip install 'google-cloud-aiplatform>=1.25.0'
 ```
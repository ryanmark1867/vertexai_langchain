# Vertex AI experiments with LangChain

- Basic experiments using LangChain with Vertex AI
- [hello world example](https://github.com/ryanmark1867/vertexai_langchain/blob/master/hello_world.py), based on [LangChain documentation](https://python.langchain.com/en/latest/modules/models/llms/integrations/google_vertex_ai_palm.html) shows how you can invoke the PaLM 2 model in the context of Vertex AI.
- To run this example directly from Cloud Shell, enable the Vertex AI API in the project you are using and install the prerequisites:

 ```
 pip install langchain
 pip install 'google-cloud-aiplatform>=1.25.0'
 ```

 output is:  
 
 ```
 Liam Gallagher was born on September 21, 1972. The 1972 Stanley Cup Finals was a best-of-seven series between the Boston Bruins and the New York Rangers. The Bruins won the series 4-3.
The final answer: Boston Bruins.
```

[Related article](https://markryan-69718.medium.com/hello-world-for-vertex-ai-generative-ai-with-langchain-5a98efdd37e0?sk=1437689fe2dd3e772dc6b89554d7a170)
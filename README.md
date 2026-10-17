# RAG com LangChain

Agente que consulta regras de futebol com LangChain, FAISS e Ollama. Os modelos rodam localmente.

Como executar:

1. python -m venv .venv
2. .\.venv\Scripts\Activate.ps1
3. pip install langchain langchain-ollama langchain-community langchain-text-splitters faiss-cpu
4. ollama pull nomic-embed-text
5. ollama pull gemma3:1b
6. python .\aulas\05_agente_futebol.py

O indice fica na pasta local indice/ e nao vai para o Git.

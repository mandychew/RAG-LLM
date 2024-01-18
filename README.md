# Using LLM to answer public's queries about Singapore Laws
This is only a demo. It has only been fine-tuned on 2 of Singapore's acts (click to view original PDFs):
- [Intellectual Property Office of Singapore Act 2001](https://sso.agc.gov.sg/Act/IPOSA2001?ViewType=Pdf&_=20231228160854)
- [Residential Property Act 1976](https://sso.agc.gov.sg/Act/RPA1976?ViewType=Pdf&_=20220917002255)  
  
## Dependencies
Ollama, langchain, chromadb, BeautifulSoup4, gpt4all, langchainhub, pypdf, chainlit  
  
## How to use
1. Add PDF(s) of Singapore laws into `data` folder
2. On terminal, run ```python3 load_data_vdb.py```
3. On terminal, run ```chainlit run RAG.py```  
  
## Resources:  
- [Retrieval Augmented Generation (RAG)](https://stackoverflow.blog/2023/10/18/retrieval-augmented-generation-keeping-llms-relevant-and-current/)  
- PDFs of Singapore laws: [Singapore Statutes Online](https://sso.agc.gov.sg/Browse/Act/Current)  
- Code: [Article by Plaban Nayak](https://medium.aiplanet.com/implementing-rag-using-langchain-ollama-and-chainlit-on-windows-using-wsl-92d14472f15d)
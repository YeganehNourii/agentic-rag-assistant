# Agentic RAG Assistant

A retrieval-augmented assistant that answers questions from technical PDFs and always cites the file and page it used, and says "not in these documents" when the answer is not there. Built in Python with a vector database, hybrid keyword and semantic retrieval with re-ranking, and a FastAPI service; extended with a tool-using agent and an MCP server so other assistants can query the same corpus, and evaluated on a hand-written 30-question benchmark. Started September 2026 and actively in development.

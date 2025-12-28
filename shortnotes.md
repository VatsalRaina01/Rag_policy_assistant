What you’re most proud of:

I’m most proud of adapting a RAG system to run entirely in a stateless, serverless environment on Vercel. Instead of using heavy persistent vector databases, I built a lightweight in-memory vector store that allows users to upload and query documents instantly. This helped me deploy a live, zero-cost web application and demonstrate full end-to-end GenAI engineering beyond a local script.

One thing you’d improve next:

The next improvement would be adding conversation history and persistence. Since the app runs on a stateless server, the memory resets when the function sleeps. I would integrate a persistent vector database and conversation memory so users can ask follow-up questions without losing context.
### Commands: 

```bash
# Start Inngest Dev Server
npx inngest-cli@latest dev -u http://127.0.0.1:8000/api/inngest --no-discovery

# Start FastAPI Server
uv run uvicorn main:app

# Run Qdrant locally 

# Run a Qdrant database container in the background, name it qdrant, expose it on port 6333, and store its data permanently in a folder on my Mac. 

docker run -d --name qdrant -p 6333:6333 -v "$(pwd)/qdrant_storage:/qdrant/storage" qdrant/qdrant
```
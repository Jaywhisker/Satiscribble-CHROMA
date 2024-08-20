# Satiscribble-CHROMA
This is the repository for Satiscribble CHROMA. This chroma DB is the vector database to store the vector embeddings of the minutes for retrieval with documentQnA. Each collection is defined as 1 instance of meeting minutes with each topic being a document inside this collection.

# Setup
This github is hosted on Docker. To set up your docker image, please follow the following steps after you git clone.
```
cd build
docker compose up
```
There will be a chroma folder in your root directory upon startup. This is to store all the data, you should not be interacting with that folder.




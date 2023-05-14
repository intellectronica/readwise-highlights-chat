See [notebook: ReadwiseChat.ipynb](ReadwiseChat.ipynb)

Readwise ( http://readwise.io/ ) is a wonderful app that makes it easy to read 
books and articles and highight parts of the text that are interesting for later
reference or review. I've been using it for a few years and over that time have
ammased a huge library of highlights on many topics. I review some random
highlights daily, and also sync them as markdown to read in my text editor. But
wouldn't it be awesome to chat with an AI that has access to the entire library?

... enter Open AI, LangChain, and Chroma ...

In this sample, we read the highlights from Readwise using the API, index the
highlights with their embeddings for semantic retrieval with the ChromaDB vector
database, and connect the vector database to a chat model using LangChain.

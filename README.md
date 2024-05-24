# Flowise document chatflow

This a sample project to start using flowise with documents in memory vector store.

## Requirements

1. docker
```
https://www.docker.com/
```
2. docker-compose
```
https://docs.docker.com/compose/install/
```

## Installation

1. Clone the repository:
```
git clone https://github.com/balataca/flowise-docker.git
```
2. Change directory:
```
cd flowise-docker
```
3. Run docker-compose:
```
docker-compose up -d
```
4. After the server is up access the admin panel:
```
http://localhost:3000
```
5. Login with credentials:
* username: admin
* passowrd: admin
6. Go to `Chatflows` > `Add new`
7. Click on the cog icon on top right
8. Select `Load Chatflow`
9. Select the file `document-chatflow.json` in this directory.

## Usage

1. Run the `docker-compose` command and open the admin:
```
http://localhost:3000
```
2. Go to `Chatflows` and select the chatflow you imported.
3. Add you `OpenAI` api key to the `OpenAI Embeddings` and `ChatOpenAI` nodes.
4. Click on `Upload File` button on `Text File` node.
5. Click on the green button with a database icon to `upsert` documents to the store.
6. Click on the chat icon (purple) to start chating about your documents.
version: '3.8'

services:
  app:
    image: my-node-app
    build:
      context: .
      dockerfile: Dockerfile
    ports:
      - "3000:3000"
    volumes:
      - .:/usr/src/app
    depends_on:
      - db

  db:
    image: mongo
    ports:
      - "27017:27017"## Hi there 👋

<!--
**michaeldavis246611119/michaeldavis246611119** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on building my family
- 🌱 I’m currently learning ai intelligence 
- 👯 I’m looking to collaborate on anything 
- 🤔 I’m looking for help with easy to remember pathways
- 💬 Ask me about ...
- 📫 How to reach me: email 
- 😄 Pronouns: Him
- ⚡ Fun fact: I still have a baby tooth


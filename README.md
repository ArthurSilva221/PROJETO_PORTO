# PROJETO_PORTO

Projeto feito usando Node.js em conjunto com React e Express para front-end e back-end respectivamente. Criação de API modular com interligação e suporte para ambientes de desenvolvimento e produção.

Para usar instale o Concurrently, após baixar e deixe a seguinte configuração:

"start": "concurrently \"npm run start:api\" \"npm run start:app\"",
"start:api": "cd packages/api && npm start",
"start:app": "cd packages/app && npm start"

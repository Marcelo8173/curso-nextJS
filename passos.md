### instalando o typeScript
- yarn add typescript @types/react @types/node -D

### inicializar o projeto
- yarn dev

### chamadas
- numa aplicação react tradicional todas as renderizações são feitas no navegador
- numa aplicação em nextJS é do lado do servidor do next

### rotas
- não precisa de uma lib de rotas o proprio next a rota é o nome do arquivo 
- caso ela esteja em pastas ela é o nome da pasta e o nome do arquivo
- /pasta/arquivo
- pastas e aquivos com _ na frente o nextJS ignora
- as rotas com parametros são criadas dinamicamente pelo nome do arquivo [qualquercoisa].tsx
- para pegar a informação é usado o useRouter de dentro do next/router

### aquivos de estilo 
- os arquivos de estilo não podem ir juntos com arquivos de script
- crio na raiz do projeto um aquivo babel.config.js
- instalo o puglin yarn add babel-plugin-styled-components -D

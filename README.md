Projeto AWS Serverless computing

> Arquitetura da aplicação

A arquitetura da aplicação usa o AWS Lambda, o Amazon API Gateway, o Amazon DynamoDB, o Amazon Cognito e o console do AWS Amplify. O console do Amplify fornece implantação e hospedagem de recursos web estáticos, incluindo HTML, CSS, JavaScript e arquivos de imagem que são carregados no navegador do usuário. O JavaScript executado no navegador envia e recebe dados de uma API de back-end pública criada usando o Lambda e o API Gateway. O Amazon Cognito oferece funções de autenticação e gerenciamento de usuários para proteger a API do back-end. Por fim, o Amazon DynamoDB fornece uma camada de persistência onde os dados podem ser armazenados pela função do Lambda da API.

# Projeto Node utilizando Prisma
- Desenvolvido no curso DEV-TI da Unoesc

## Como rodar
- Para rodar o projeto, é necessário ter o MySQL e seus drivers instalados
- Necessário incluir arquivo .env dentro da back-end-prisma com a variável: 
  DATABASE_URL=mysql://test:test@localhost:3306/test (exemplo url de conexão)

- Executar os comandos no terminal:
```
npm install (instala os módulos node)
npx prisma migrate dev (inclui a tabela de usuarios)
npm run devP (executa o servidor)
```

- Rotas da API Rest:
```
/ <-- Página inicial do servidor 
/api/usuarios <-- Lista de todos os usuários
/api/usuarios/{id} <-- Lista de um usuário específico pelo ID
```
## Tecnologias
- HTML, CSS (Com Bootstrap e FontAwesome)
- Node.js 
- Prisma ORM (para persistir dados no banco)
- Axios (para requisições HTTP)

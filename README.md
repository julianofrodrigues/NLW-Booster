"# NLW-Booster" 

<h1>Instalando Projeto</h1>
<p>Primeiro entre nas pastas e instale suas dependencias...</p>

```bash
# Entre no repositório
$ cd next-level-week-1

# Instale as dependências dentro do diretório server
$ cd server
$ npm install

# Instale as dependências dentro do diretório web
$ cd web
$ npm install

# Instale as dependências dentro do diretório mobile
$ cd mobile
$ npm install

### Importante modificar o arquivo
Todos os arquivos onde estiver escrito seu IP coloque o IP da sua maquina
```

### Backend
```bash
# Executar para criar o banco de dados
$ npx knex migrate:latest

# Popular banco de dados com as informações fixas dos itens coletados
#ATENÇÃO: Antes de rodar esse comando, cópie os arquivos da pasta assets para a pasta upload do backend
$ npx knex seed:run

# Rodar o backend
$ npm run dev
```
### Frontend
```bash
# Rodar aplicação web (cd web)
$ npm start

# Rodar aplicação mobile (cd mobile)
$ npm start
```

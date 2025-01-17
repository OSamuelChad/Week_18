# Passos necessários para instalar o sistema

1. Descompacte o arquivo zip e entre na pasta criada
2. Digite: npm install
3. Edite o arquivo knextfile.js e coloque suas configurações do banco de dados.
4. No mysql crie um banco de dados chamado pettopstore com as permissões todais para o usuárioo configurado.
5. digite: npm exec knex migrate:latest
6. digite: npm exec knex seed:run
7. didite: npm start

Esses passos acima são necessários somente na primeira vez que for executar o sistema. Nas próximas vezes que for executar o sistema, basta digitar:

npm start

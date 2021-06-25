Como executar a Api Sistema cade meu Bicho:

Para executar o projeto em Lavarel precisa ter o gerenciador de pacotes Composer installado.
execute o arquivo sql cade_meu_bicho.sql em algum sgbd de sua preferencia, eu utilizo o heidisql.
abra o projeto em algum editor de texto de sua preferencia, e procure pelo arquivo .env, nele estará todas as configurações da conexão com o banco de dados.
utilize as suas configurações do seu banco de dados, o projeto é rodado em mysql.
Use um terminal de comandos de preferência o terminal do editor de texto visual studio code, acessa até a pagina do projeto chamada de cade_meu_bicho.
Logo depois execute a criação das Migrations, no seu terminal execute a linha de comando php artisan migrate.
utilize qualquer programa para teste de api, eu utilizei uma extensão do proprio visual studio code chamado de thunder client
as rotas para teste são: List global = method get http://127.0.0.1:8000/api/animals listagem show = method get http://127.0.0.1:8000/api/animals/id create store = method post http://127.0.0.1:8000/api/animal/ update update = method put http://127.0.0.1:8000/api/animal/id update delete = method delete http://127.0.0.1:8000/api/animal/id
pronto para teste

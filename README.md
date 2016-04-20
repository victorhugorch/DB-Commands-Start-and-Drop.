# DB-Commands-Start-and-Drop.

Nesse repositório você encontrará os arquivos necessários para instalar em sua aplicação laravel os comandos DB:start e DB:drop. Eles auxiliam o gerenciamento do seu Banco de Dados pela facilidade no reinicio do Banco de Dados da aplicação durante o desenvolvimento do projeto. Para usá-la você precisa clonar esse repositório.

`git clone https://github.com/victorhugorch/DB-Commands-Start-and-Drop..git`

Depois você precisa colocar os arquivos dentro do seu projeto. Seguindo o caminho de pastas do Laravel será em: *Your-project > app > Console*. Para utilizar os comandos abra o terminal e digite o comando abaixo.

`php artisan db:start`
`php artisan db:drop`

O comando start irá criar o seu Banco caso ele não exista com base nos dados colocados no seu arquivo *.env* previamente criado, ele automaticamente rodará os comandos migration e seed e seu banco de dados já estará pronto para ser utilizado. O comando drop derruba o banco de dados previamente criado. 

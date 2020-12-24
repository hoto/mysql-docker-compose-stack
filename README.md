# MySql docker-compose stack

For fun, for work, for life.


Nodejs:

    const mysql = require('mysql')

    const connection = mysql.createConnection({
        host: 'localhost',
        port: '5000',
        user: 'root',
        password: 'root',
        database: 'my_schemaname'
    })

#Para trabalhar com banco de dados vou utilizar o SEQUELIZE que é uma ORM
#Junto já está instalado o SGDB MySQL com MySQl WORKBANCH


#Comando via terminal para instalar o sequelize no projeto
     #-->  npm install --save sequelize
#Comando para instalar o reconhecimento do MySQL (biblioteca)
     #-->  npm install --save mysql2
#Comando para deixar a aplicação ativa toda vez que o servidor (DigitalOcean) ligar
     #--> sudo npm install -g pm2
          #Para inicializar
               #--> pm2 start index.js

#Comando MySQl para em alguns casos resolver problema de atualização do banco. 
     #--> alter user 'root'@'localhost' identified with mysql_native_password by 'Senha'

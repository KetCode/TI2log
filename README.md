# TI2log
Seguindo as aulas da universidade foi possivel criar esse projeto que armazena o ip address e o nome do pc na tabela do banco de dados em mysql

## Para funcionamento:
É preciso criar uma tabela no mysql da seguinte forma
```
create table projetoint1.log (
	idlog int not null auto_increment primary key,
    acesso_tm varchar(45), 
    acesso_pc varchar(45),
    acesso_ip varchar(45)
);
```

No vscode rodar ```npm install``` e ```npm run dev / yarn dev```

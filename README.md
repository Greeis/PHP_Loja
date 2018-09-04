# Loja

## BD
loja

## Tabelas
create table categorias (id integer auto_increment primary key, nome varchar(255));
create table produtos (id integer auto_increment primary key, nome varchar(255), descricao text, preco decimal(10,2), categoria_id integer, usado boolean default false);

## Insert
insert into categorias (nome) values ("esporte"), ("escola"), ("mobilidade"), ("guloseimas");

create database vendas_sucos;
create database vendas_sucos2 default character set utf8;
create database if not exists vendas_sucos2;
drop database if exists vendas_sucos2;


create table produtos
(codigo varchar(10) not null,
descritor varchar (100) null,
sabor varchar (50) null,
tamanho varchar (50) null,
embalagem varchar (50) null,
preco_lista float null,
primary key (codigo));

create table vendedores
(matricula varchar(5) not null,
nome varchar (100) null,
bairro varchar (50) null,
comissa float null,
data_adimissao date null,
ferias bit(1)
primary key (matricula));

alter table vendedores rename column data_adimissao to data_adimissao;


use vendas_sucos;

create table tabela_de_vendas

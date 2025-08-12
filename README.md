-- Criar o banco de dados "meu_banco" se ele não existir
CREATE DATABASE IF NOT EXISTS meu_banco
DEFAULT CHARACTER SET utf8
DEFAULT COLLATE utf8_general_ci;

-- ... (fazer outras coisas, como criar tabelas, etc.) ...

-- Apagar o banco de dados "meu_banco" se ele existir
DROP DATABASE IF EXISTS meu_banco;

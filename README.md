CREATE TABLE pessoas (
    id INT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    idade INT,
    endereco_id INT,
    FOREIGN KEY (endereco_id) REFERENCES enderecos(id)
);

CREATE TABLE enderecos (
    id INT PRIMARY KEY,
    rua VARCHAR(255),
    cidade VARCHAR(255)
);

INSERT INTO enderecos(rua, cidade) VALUES
('Rua dos Girassóis', 'Nova Esperança');

INSERT INTO enderecos(rua, cidade) VALUES
('Rua das Acácias', 'Montanha Azul');

INSERT INTO enderecos(rua, cidade) VALUES
('Avenida das Rosas', 'Cidade Primavera');

INSERT INTO enderecos(rua, cidade) VALUES
('Rua dos Ipês', 'Vila Verde');

INSERT INTO enderecos(rua, cidade) VALUES
('Avenida das Palmeiras', 'Sol Nascente');

INSERT INTO enderecos(rua, cidade) VALUES
('Rua das Orquídeas', 'Céu Azul');

INSERT INTO enderecos(rua, cidade) VALUES
('Avenida das Violetas', 'Paraíso do Norte');

INSERT INTO enderecos(rua, cidade) VALUES
('Rua das Hortênsias', 'Terra Encantada');

INSERT INTO enderecos(rua, cidade) VALUES
('Avenida dos Lírios', 'Jardim das Flores');

INSERT INTO enderecos(rua, cidade) VALUES
('Rua das Tulipas', 'Vale Encantado');

INSERT INTO enderecos(rua, cidade) VALUES
('Avenida das Margaridas', 'Alvorada');

INSERT INTO enderecos(rua, cidade) VALUES
('Rua dos Jasmins', 'Rosa Branca');

INSERT INTO enderecos(rua, cidade) VALUES
('Avenida das Camélias', 'Estrela Cadente');

INSERT INTO enderecos(rua, cidade) VALUES
('Rua das Dálias', 'Praia do Sol');

INSERT INTO enderecos(rua, cidade) VALUES
('Avenida das Bromélias', 'Luar Encantado');

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('João Silva', 30, 1);

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('Maria Santos', 25, 2);

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('Pedro Almeida', 40, 3);

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('Ana Oliveira', 35, 4);

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('Carlos Pereira', 28, 5);

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('Juliana Fernandes', 33, 6);

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('Fernando Costa', 27, 7);

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('Mariana Sousa', 22, 8);

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('Ricardo Nunes', 38, 9);

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('Catarina Martins', 29, 10);

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('Gustavo Santos', 31, 11);

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('Lúcia Oliveira', 26, 12);

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('Rodrigo Ferreira', 36, 13);

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('Beatriz Silva', 23, 14);

INSERT INTO pessoas(nome, idade, endereco_id) VALUES
('Alexandre Pereira', 37, 15);

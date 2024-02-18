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

INSERT INTO enderecos(id, rua, cidade) VALUES (1, 'Rua dos Girassóis', 'Nova Esperança');

INSERT INTO enderecos(id, rua, cidade) VALUES (2, 'Rua das Acácias', 'Montanha Azul');

INSERT INTO enderecos(id, rua, cidade) VALUES (3, 'Avenida das Rosas', 'Cidade Primavera');

INSERT INTO enderecos(id, rua, cidade) VALUES (4, 'Rua dos Ipês', 'Vila Verde');

INSERT INTO enderecos(id, rua, cidade) VALUES (5, 'Avenida das Palmeiras', 'Sol Nascente');

INSERT INTO enderecos(id, rua, cidade) VALUES (6, 'Rua das Orquídeas', 'Céu Azul');

INSERT INTO enderecos(id, rua, cidade) VALUES (7, 'Avenida das Violetas', 'Paraíso do Norte');

INSERT INTO enderecos(id, rua, cidade) VALUES (8, 'Rua das Hortênsias', 'Terra Encantada');

INSERT INTO enderecos(id, rua, cidade) VALUES (9, 'Avenida dos Lírios', 'Jardim das Flores');

INSERT INTO enderecos(id, rua, cidade) VALUES (10, 'Rua das Tulipas', 'Vale Encantado');

INSERT INTO enderecos(id, rua, cidade) VALUES (11, 'Avenida das Margaridas', 'Alvorada');

INSERT INTO enderecos(id, rua, cidade) VALUES (12, 'Rua dos Jasmins', 'Rosa Branca');

INSERT INTO enderecos(id, rua, cidade) VALUES (13, 'Avenida das Camélias', 'Estrela Cadente');

INSERT INTO enderecos(id, rua, cidade) VALUES (14, 'Rua das Dálias', 'Praia do Sol');

INSERT INTO enderecos(id, rua, cidade) VALUES (15, 'Avenida das Bromélias', 'Luar Encantado');

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (1, 'João Silva', 30, 1);

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (2, 'Maria Santos', 25, 2);

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (3, 'Pedro Almeida', 40, 3);

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (4, 'Ana Oliveira', 35, 4);

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (5, 'Carlos Pereira', 28, 5);

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (6, 'Juliana Fernandes', 33, 6);

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (7, 'Fernando Costa', 27, 7);

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (8, 'Mariana Sousa', 22, 8);

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (9, 'Ricardo Nunes', 38, 9);

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (10, 'Catarina Martins', 29, 10);

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (11, 'Gustavo Santos', 31, 11);

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (12, 'Lúcia Oliveira', 26, 12);

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (13, 'Rodrigo Ferreira', 36, 13);

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (14, 'Beatriz Silva', 23, 14);

INSERT INTO pessoas(id, nome, idade, endereco_id) VALUES (15, 'Alexandre Pereira', 37, 15);

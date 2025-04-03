### COMO RODAR PROJETO 

Executar o MySQL atraves do XAMPP

Utilizar o VS CODE para editar os codigos e visualizar melhor as pastas 

Criar banco de dados "crud"
'''
CREATE DATABASE crud;
'''

Criar tabela chamada "alunos"

CREATE TABLE crud.alunos (
    id INT NOT NULL AUTO_INCREMENT,
    nome VARCHAR(225) NOT NULL,
    email VARCHAR(50) NOT NULL,
    telefone VARCHAR(50) NOT NULL,
    data_nascimento DATE NOT NULL,
    PRIMARY KEY (id)
) ENGINE=InnoDB;

INSERT INTO alunos (nome, email, telefone, data_nascimento) 
VALUES 
('Lucas Silva', 'lucas.silva@email.com', 987654321, '1998-05-12'),
('Ana Costa', 'ana.costa@email.com', 912345678, '2000-02-25'),
('Carlos Pereira', 'carlos.pereira@email.com', 981234567, '1997-11-30'), 
('Fernanda Almeida', 'fernanda.almeida@email.com', 923456789, '2001-03-14'),
('Marcos Oliveira', 'marcos.oliveira@email.com', 991234567, '1995-07-22'),
('Camila Souza', 'camila.souza@email.com', 970123456, '1999-08-18'),
('Rafael Santos', 'rafael.santos@email.com', 938234567, '1996-01-09'),
('Juliana Lima', 'juliana.lima@email.com', 974567890, '2002-04-16'),
('Felipe Rocha', 'felipe.rocha@email.com', 962345678, '1997-09-27'),
('Mariana Fernandes', 'mariana.fernandes@email.com', 955678912, '2000-06-05'),
('Paulo Costa', 'paulo.costa@email.com', 930987654, '1998-10-12'),
('Tatiane Gomes', 'tatiane.gomes@email.com', 965432109, '2001-12-03'),
('Gustavo Martins', 'gustavo.martins@email.com', 949823567, '1996-11-16'), 
('Beatriz Costa', 'beatriz.costa@email.com', 978654123, '1997-03-22'),
('Andre Silva', 'andre.silva@email.com', 936544321, '1995-02-14'),
('Renata Oliveira', 'renata.oliveira@email.com', 920123456, '1999-09-10'),
('Diego Almeida', 'diego.almeida@email.com', 980123456, '2002-08-30'),
('Sandra Pereira', 'sandra.pereira@email.com', 911223344, '1996-07-14'), 
('Vinicius Souza', 'vinicius.souza@email.com', 918734521, '2000-05-18'),
('Juliano Santos', 'juliano.santos@email.com', 961234321, '1997-12-09'),
('Luana Ferreira', 'luana.ferreira@email.com', 976543210, '2001-04-21'), 
('Marcelo Lima', 'marcelo.lima@email.com', 943567890, '1998-11-15'),
('Roberta Rocha', 'roberta.rocha@email.com', 954321876, '1997-01-27'),
('Mauricio Costa', 'mauricio.costa@email.com', 930865432, '1999-06-07'),
('Carla Souza', 'carla.souza@email.com', 973654123, '2000-12-12'),
('Jonas Almeida', 'jonas.almeida@email.com', 922345678, '1996-04-28'),
('Jessica Oliveira', 'jessica.oliveira@email.com', 988765432, '1998-02-02'), 
('Robson Ferreira', 'robson.ferreira@email.com', 970987654, '1995-10-03'),
('Fabiana Silva', 'fabiana.silva@email.com', 965432098, '1999-07-11'),
('Paula Souza', 'paula.souza@email.com', 977543210, '2002-11-20'),
('Rogerio Santos', 'rogerio.santos@email.com', 930876543, '1997-09-05'),
('Cintia Pereira', 'cintia.pereira@email.com', 917654321, '2000-03-16'), 
('Mario Lima', 'mario.lima@email.com', 998732654, '1996-10-22'),
('Sonia Rocha', 'sonia.rocha@email.com', 944321765, '1998-08-13'),
('Claudia Costa', 'claudia.costa@email.com', 975312468, '2002-05-29'),
('Fabio Almeida', 'fabio.almeida@email.com', 937654210, '1999-04-01'), 
('Flavia Pereira', 'flavia.pereira@email.com', 968741236, '1996-03-09'),
('Leandro Ferreira', 'leandro.ferreira@email.com', 975431234, '2001-06-23'),
('Aline Santos', 'aline.santos@email.com', 961234567, '2000-02-09'),
('Breno Lima', 'breno.lima@email.com', 919876543, '1997-04-25'), 
('Vania Rocha', 'vania.rocha@email.com', 930876543, '1999-01-17'),
('Rita Costa', 'rita.costa@email.com', 973456789, '2001-07-11'),
('Joao Oliveira', 'joao.oliveira@email.com', 912345678, '1995-12-15');

Criar uma pasta na raiz do projeto chamada "frontend"

Criar uma pasta na raiz do projeto chamada "node"
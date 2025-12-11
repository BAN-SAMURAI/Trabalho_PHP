# Trabalho_PHP
Trabalho institucional do curso Tecnico em Informatica da EEEP MANOEL MANO da disciplina de Banco de Dados, ministrada pelo professor Adeilson Sales Aragão.

# *Introdução ao Sistema ADR:*
O Sistema ADR foi desenvolvido para armazenar, cadastrar, editar e organizar os dados de alunos, bem como possibilitar o usuario realizar buscas, consultas e filtragem dos dados dos alunos cadastrados, permitindo um dinamismo e praticidade na utilização de dados.

Todo o front-end é pensado seguindo os padrões de uma GUI (Graphical User Interface). Como visto nas 3 imagens abaixo, toda a interface foi desenvolvida em facilitar e simplificar o maximo possivel a utilização do sitema pelo usuário sem prejudicar a eficiencia total entregue pelo sistema.
Segue abaixo as imagens das paginas de 'Home' (página inicial e Dashboard), 'Cadastro' (página de cadastro dos alunos) e 'Listar' (página que contém a lista de alunos cadastrados e funcionalidades de editar e excluir os dados), respectivamente.

imagem 1

imagem 2

imagem 3

# *Tecnologias Utilizadas:*

* **Back-end:** PHP;
* **Banco de Dados:** MySQL;
* **Front-end:** HTML5, CSS3 e Bootstrap;
* **Servidor:** Apache XAMPP.

# *Codigo SQL:*
Criação da tabela users:
'''CREATE TABLE users (
    user_id INT AUTO_INCREMENT PRIMARY KEY,
    user_name VARCHAR(100) NOT NULL,
    user_email VARCHAR(150) NOT NULL UNIQUE,
    user_password VARCHAR(255) NOT NULL
);'''

Criação da tabela alunos:
'''CREATE TABLE alunos (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    data_nascimento DATE NOT NULL,
    cidade VARCHAR(100),
    rua VARCHAR(255),
    bairro VARCHAR(100),
    numero VARCHAR(20),
    cep VARCHAR(10),
    nome_responsavel VARCHAR(255),
    tipo_responsavel VARCHAR(50),
    curso VARCHAR(100) NOT NULL,
    data_cadastro TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);'''

# *Consultas:*

* Consulta 1:
  
* Consulta 1:

* Consulta 1:
   
* Consulta 1:
  
* Consulta 1:
   
* Consulta 1:
  
* Consulta 1:
  
* Consulta 1:
   
* Consulta 1:
   
* Consulta 1:
  


# *Conclusão:*



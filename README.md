Atividade Prática Residencia em Software - Aplicação Web Full Stack com Docker
Este projeto consiste na configuração e deploy de uma infraestrutura completa para uma aplicação web full-stack utilizando Docker.
A aplicação inclui um backend desenvolvido em Flask (Python), um banco de dados MySQL para persistência de dados, e um frontend servido pelo Nginx.

Tecnologias Utilizadas:

Flask (Python): O backend foi desenvolvido utilizando o microframework Flask, que fornece a API REST para a aplicação. 
Essa API permite realizar operações de CRUD (Create, Read, Update, Delete) sobre os dados de usuários, que são armazenados no banco de dados.

MySQL 8.0: O banco de dados relacional MySQL é utilizado para armazenar os dados da aplicação (usuários, contendo nome e idade).

Nginx: O Nginx é utilizado como servidor web para servir os arquivos estáticos do frontend (HTML, CSS e JavaScript) e também como proxy reverso para redirecionar as requisições para o backend.

Docker: A aplicação é containerizada utilizando Docker, o que garante que todos os componentes (frontend, backend e banco de dados) possam ser executados de forma isolada e reproduzível em qualquer ambiente.

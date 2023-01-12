<h1>CURSO PROGRAMADORES CARIOCAS</h1>
PROJETO INDIVIDUAL
Módulo 4 – Resilia

CONTEXTO: A Resilia está pensando em lançar um novo sistema de acompanhamento e para isso precisa de ajuda para modelar um banco de dados que vai armazenar seus cursos, turmas e alunos.

⇨ Existem outras entidades além dessas três?
Resposta: Sim. É possível pensar em uma tabela para armazenar dados dos professores.


⇨ Quais são os principais campos e tipos?


⇨ Como essas entidades estão relacionadas?



Abaixo consta o script de criação do banco de dados proposto de acordo com o diagram.

CREATE DATABASE db_resilia;

USE db_resilia;

CREATE TABLE cursos (id_curso INT, nome_curso VARCHAR(100), turno_curso VARCHAR(50));


CREATE TABLE turmas (id_turma INT, nome_turma VARCHAR(80), matriculas_turma VARCHAR(50), turno_turma VARCHAR(50));


CREATE TABLE alunos (id_aluno INT, nome_aluno VARCHAR(80), sobrenome_aluno VARCHAR(80), cpf_aluno VARCHAR(50), matricula_aluno VARCHAR(50), email_aluno VARCHAR(50));


CREATE TABLE professores (id_professor INT, nome_professor VARCHAR(80), obrenome_professor VARCHAR(80), cpf_professor VARCHAR(50), matricula_professor VARCHAR(50));

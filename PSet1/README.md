# PSet 1
## Design e Desenvolvimento de Banco de Dados - UVV
---
### Um desafio de estudo sobre Git, projetos lógicos e uso de SGBD relacionais.
---
#### **Aluno: Calebe Rodor Nardo**
#### **Professor: Abrantes Araujo Silva Filho**
#### **Monitora: Suellen Miranda Amorim**
#### **Turma: CC1M**
---
## 1. Introdução
Este PSet teve como foco desafiar os alunos e incentivá-los a aprender novos conteúdos importantes para a matéria de _Design e Desenvolvimento de Banco de Dados_.

Os alunos tiveram como objetivos aprender a utilizar o **GIT**, a implementar um **projeto lógico** e a utilizar diferentes **SGBD relacionais** como o **PostgreSQL** e o **MariaDB**.

## 2. Git e GitHub
O Git é um **_Sistema de Controle de Versão_**, conhecido também como _VCS_ (em inglês, _Version Control System_). Um _VCS_ é um sistema que registra alterações feitas em um código fonte, com ele podemos saber quem, quando e porquê tal mudança foi feita, mantendo assim um histórico recuperável de todo o código fonte.
O **GitHub** é uma plataforma de hospedagem de código fonte que utiliza o Git como _VCS_.

Dentro do GitHub possuímos algumas funções que vale destacar:

- **Repositório:** onde os arquivos ficam armazenados, com as opções de depósito do GitHub ou no próprio computador.
- **Branch:** cópia do diretório para desenvolvimento isolado, sem afetar o repositório central ou outros _branches_.
- **Forking:** é a criação de um novo projeto com base em um repositório já existente, fazendo as mudanças como quer e armazenando em um novo repositório.

## 3. Projeto Lógico
Para a implementação do projeto lógico foi proposto a criação do projeto apresentado nos cápitulos 5 e 6 do livro **_Sistemas de Banco de Dados_**, 7ª edição, dos autores **_Elmasri & Navathe_**. _Livro que está sendo a base de estudo para este período na disciplina de Design e Desenvolvimento de Bancod e Dados_.

Para a criação do projeto lógico denominado `elmasri` nós tivemos que utilizar o _SQL Power Architect_, uma aplicação de modelagem de tabelas que torna mais visível as mudanças que estão sendo feitas.

![projeto-elmasri](https://raw.githubusercontent.com/caleber9/uvv_bd_1_cc1m/main/PSet1/images/elmasri.png)

Este projeto pode ser visualizado dentro deste repositório, ou clicando [aqui](https://github.com/caleber9/uvv_bd_1_cc1m/blob/main/PSet1/elmasri.architect).

Com o projeto lógico pronto no _SQL Power Architect_ utilizamos ele para criar dois _scripts_, um para o **_PostgreSQL_** e outro para o **_MariaDB_**.

## 4. PostgreSQL

O PostgreSQL é um sistema de gerenciamento de banco de dados relacional (SGBD), desenvolvido como projeto de código aberto. Atualmente ele é um dos SGBD mais utilizados e por isso foi escolhido para fazer parte do nosso estudo.

A implementação no PostgreSQL começou com o login pelo terminal utilizando as senhas da máquina virtual fornecida pelo orientador do curso (pode ser encontrada no [site](https://www.computacaoraiz.com.br/) computação raiz), assim que conectado o terminal ao PostgreSQL fazemos a implementação dos [_scripts_](https://github.com/caleber9/uvv_bd_1_cc1m/blob/main/PSet1/scriptpostgresql.txt).

![postgres-login](https://raw.githubusercontent.com/caleber9/uvv_bd_1_cc1m/main/PSet1/images/postgres.png)

## 5. MariaDB

MariaDB é um sistema de gerenciamento de banco de dados que surgiu como fork do MySQL, criado pelo próprio fundador do projeto após sua aquisição pela Oracle. A intenção principal do projeto é manter uma alta fidelidade com o MySQL.

A implementação no MariaDB começou da mesma maneira que o PostgreSQL, começamos com o login pelo terminal utilizando as senhas da máquina virtual. Após isso conectamos o MariaDB ao terminal, e fazemos a implementação dos [_scripts_](https://github.com/caleber9/uvv_bd_1_cc1m/blob/main/PSet1/scriptmariadb.txt).

![mariadb-login](https://raw.githubusercontent.com/caleber9/uvv_bd_1_cc1m/main/PSet1/images/mariadb.png)

## 6. Conclusão

Com a conclusão do projeto concluí o porquê de um prazo tão extenso, e me encontrei diante de diversos desafios. Durante a duração desse _PSet_ eu tive que aprender mais sobre _VCS_, entender o **_Git_** e o **_GitHub_**, aprender sobre o funcionamento do **PostgreSQL** e como exportar _scripts_ do **_SQL Power Architect_**.

Foi um aprendizado árduo, difícil, e complexo, e sei que apesar de ser o primeiro foi uma introdução, mas isso me faz ficar ansioso pelo que vem a seguir.

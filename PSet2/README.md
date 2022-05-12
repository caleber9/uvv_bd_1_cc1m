# PSet 2
## Design e Desenvolvimento de Banco de Dados - UVV
---
### Um PSet para estudo e treinamento em relatórios SQL.
---
#### **Aluno: Calebe Rodor Nardo**
#### **Professor: Abrantes Araujo Silva Filho**
#### **Monitora: Suellen Miranda Amorim**
#### **Turma: CC1M**
---
## 1. Introdução
Este PSet teve como foco desafiar os alunos e incentivá-los a aprender novos conteúdos importantes para a matéria de _Design e Desenvolvimento de Banco de Dados_.

Dentro desse PSet os alunos tiveram o objetivo de gerar **relatórios SQL** com base na tabela do **PSet 1** (disponível para consulta [aqui]()).

## 2. Questões para os relatórios
Aqui apresento as questões e seus respectivos relatórios formados pelos [scripts]() SQL. 












### **Questão 1:**
Prepare um relatório que mostre a média salarial dos funcionários
de cada departamento.

| nome_departamento | media_salario |
|:---:|:---:|
| Administração     | R$ 31000.00   |
| Matriz            | R$ 55000.00   |
| Pesquisa          | R$ 33250.00   |

### **Questão 2:**
Prepare um relatório que mostre a média salarial dos homens e das
mulheres.

| media_salario | sexo |
|:---:|:---:|
| R$ 31000.00   | F    |
| R$ 37600.00   | M    |

### **Questão 3:**
Prepare um relatório que liste o nome dos departamentos e, para
cada departamento, inclua as seguintes informações de seus funcionários: o nome
completo, a data de nascimento, a idade em anos completos e o salário.

| nome_departamento | nome             | data_nascimento | idade | salario     |
|:---:|:---:|:---:|:---:|:---:|
| Administração     | André V Pereira  | 1969-03-29      |    53 | R$ 25000.00 |
| Administração     | Alice J Zelaya   | 1968-01-19      |    54 | R$ 25000.00 |
| Administração     | Jennifer S Souza | 1941-06-20      |    80 | R$ 43000.00 |
| Matriz            | Jorge E Brito    | 1937-11-10      |    84 | R$ 55000.00 |
| Pesquisa          | Fernando T Wong  | 1955-12-08      |    66 | R$ 40000.00 |
| Pesquisa          | Joice A Leite    | 1972-07-31      |    49 | R$ 25000.00 |
| Pesquisa          | João B Silva     | 1965-01-09      |    57 | R$ 30000.00 |
| Pesquisa          | Ronaldo K Lima   | 1962-09-15      |    59 | R$ 38000.00 |

### **Questão 4:**
Prepare um relatório que mostre o nome completo dos funcionários, a idade em anos completos, o salário atual e o salário com um reajuste que
obedece ao seguinte critério: se o salário atual do funcionário é inferior a 35.000 o
reajuste deve ser de 20%, e se o salário atual do funcionário for igual ou superior a
35.000 o reajuste deve ser de 15%.

| nome             | idade | salario     | reajuste |
|:---:|:---:|:---:|:---:|
| Jorge E Brito    |    84 | R$ 55000.00 | 63250.00 |
| Jennifer S Souza |    80 | R$ 43000.00 | 49450.00 |
| Fernando T Wong  |    66 | R$ 40000.00 | 46000.00 |
| Ronaldo K Lima   |    59 | R$ 38000.00 | 43700.00 |
| João B Silva     |    57 | R$ 30000.00 | 36000.00 |
| Alice J Zelaya   |    54 | R$ 25000.00 | 30000.00 |
| André V Pereira  |    53 | R$ 25000.00 | 30000.00 |
| Joice A Leite    |    49 | R$ 25000.00 | 30000.00 |

### **Questão 5:**
Prepare um relatório que liste, para cada departamento, o nome
do gerente e o nome dos funcionários. Ordene esse relatório por nome do departamento (em ordem crescente) e por salário dos funcionários (em ordem decrescente).

| nome_departamento | gerente  | funcionario | salario     |
|:---:|:---:|:---:|:---:|
| Administração     | Jennifer | Jennifer    | R$ 43000.00 |
| Administração     | Jennifer | André       | R$ 25000.00 |
| Administração     | Jennifer | Alice       | R$ 25000.00 |
| Matriz            | Jorge    | Jorge       | R$ 55000.00 |
| Pesquisa          | Fernando | Fernando    | R$ 40000.00 |
| Pesquisa          | Fernando | Ronaldo     | R$ 38000.00 |
| Pesquisa          | Fernando | João        | R$ 30000.00 |
| Pesquisa          | Fernando | Joice       | R$ 25000.00 |

### **Questão 6:**
Prepare um relatório que mostre o nome completo dos funcionários que têm dependentes, o departamento onde eles trabalham e, para cada funcionário, também liste o nome completo dos dependentes, a idade em anos de cada
dependente e o sexo (o sexo NÃO DEVE aparecer como M ou F, deve aparecer
como “Masculino” ou “Feminino”).

| funcionario      | nome_departamento | dependente        | idade_dependente | sexo_dependente |
|:---:|:---:|:---:|:---:|:---:|
| João B Silva     | Pesquisa          | Alicia B Silva    |               33 | Feminino        |
| João B Silva     | Pesquisa          | Elizabeth B Silva |               55 | Feminino        |
| João B Silva     | Pesquisa          | Michael B Silva   |               34 | Masculino       |
| Fernando T Wong  | Pesquisa          | Alicia T Wong     |               36 | Feminino        |
| Fernando T Wong  | Pesquisa          | Janaína T Wong    |               64 | Feminino        |
| Fernando T Wong  | Pesquisa          | Tiago T Wong      |               38 | Masculino       |
| Jennifer S Souza | Administração     | Antonio S Souza   |               80 | Masculino       |

### **Questão 7:**
Prepare um relatório que mostre, para cada funcionário que NÃO
TEM dependente, seu nome completo, departamento e salário.

| nome_funcionario | nome_departamento | salario     |
|:---:|:---:|:---:|
| Joice A Leite    | Pesquisa          | R$ 25000.00 |
| Ronaldo K Lima   | Pesquisa          | R$ 38000.00 |
| Jorge E Brito    | Matriz            | R$ 55000.00 |
| André V Pereira  | Administração     | R$ 25000.00 |
| Alice J Zelaya   | Administração     | R$ 25000.00 |

### **Questão 8:**
Prepare um relatório que mostre, para cada departamento, os projetos desse departamento e o nome completo dos funcionários que estão alocados
em cada projeto. Além disso inclua o número de horas trabalhadas por cada funcionário, em cada projeto.

| nome_departamento | nome_projeto     | nome             | horas |
|:---:|:---:|:---:|:---:|
| Pesquisa          | ProdutoX         | João B Silva     | 32.5h |
| Pesquisa          | ProdutoX         | Joice A Leite    | 20.0h |
| Pesquisa          | ProdutoY         | João B Silva     | 7.5h  |
| Pesquisa          | ProdutoY         | Fernando T Wong  | 10.0h |
| Pesquisa          | ProdutoY         | Joice A Leite    | 20.0h |
| Pesquisa          | ProdutoZ         | Fernando T Wong  | 10.0h |
| Pesquisa          | ProdutoZ         | Ronaldo K Lima   | 40.0h |
| Pesquisa          | Informatização   | Fernando T Wong  | 10.0h |
| Administração     | Informatização   | André V Pereira  | 35.0h |
| Administração     | Informatização   | Alice J Zelaya   | 10.0h |
| Pesquisa          | Reorganização    | Fernando T Wong  | 10.0h |
| Matriz            | Reorganização    | Jorge E Brito    | 0.0h  |
| Administração     | Reorganização    | Jennifer S Souza | 15.0h |
| Administração     | Novosbenefícios  | Jennifer S Souza | 20.0h |
| Administração     | Novosbenefícios  | André V Pereira  | 5.0h  |
| Administração     | Novosbenefícios  | Alice J Zelaya   | 30.0h |

### **Questão 9:**
Prepare um relatório que mostre a soma total das horas de cada
projeto em cada departamento. Obs.: o relatório deve exibir o nome do departamento, o nome do projeto e a soma total das horas.

| nome_departamento | nome_projeto     | total_horas |
|:---:|:---:|:---:|
| Administração     | Informatização   |        55.0 |
| Administração     | Novosbenefícios  |        55.0 |
| Pesquisa          | ProdutoX         |        52.5 |
| Pesquisa          | ProdutoY         |        37.5 |
| Pesquisa          | ProdutoZ         |        50.0 |
| Matriz            | Reorganização    |        25.0 |

### **Questão 10:**
Prepare um relatório que mostre a média salarial dos funcionários
de cada departamento.

| nome_departamento | media_salario |
|:---:|:---:|
| Administração     | R$ 31000.00   |
| Matriz            | R$ 55000.00   |
| Pesquisa          | R$ 33250.00   |


### **Questão 11:**
Considerando que o valor pago por hora trabalhada em um projeto
é de 50 reais, prepare um relatório que mostre o nome completo do funcionário, o
nome do projeto e o valor total que o funcionário receberá referente às horas trabalhadas naquele projeto.

| funcionario      | nome_projeto     | total_recebido |
|:---:|:---:|:---:|
| Ronaldo K Lima   | ProdutoZ         | R$ 2000.0      |
| André V Pereira  | Informatização   | R$ 1750.0      |
| João B Silva     | ProdutoX         | R$ 1625.0      |
| Alice J Zelaya   | Novosbenefícios  | R$ 1500.0      |
| Joice A Leite    | ProdutoX         | R$ 1000.0      |
| Joice A Leite    | ProdutoY         | R$ 1000.0      |
| Jennifer S Souza | Novosbenefícios  | R$ 1000.0      |
| Jennifer S Souza | Reorganização    | R$ 750.0       |
| Fernando T Wong  | Reorganização    | R$ 500.0       |
| Alice J Zelaya   | Informatização   | R$ 500.0       |
| Fernando T Wong  | ProdutoZ         | R$ 500.0       |
| Fernando T Wong  | Informatização   | R$ 500.0       |
| Fernando T Wong  | ProdutoY         | R$ 500.0       |
| João B Silva     | ProdutoY         | R$ 375.0       |
| André V Pereira  | Novosbenefícios  | R$ 250.0       |
| Jorge E Brito    | Reorganização    | R$ 0.0         |

### **Questão 12:**
Seu chefe está verificando as horas trabalhadas pelos funcionários
nos projetos e percebeu que alguns funcionários, mesmo estando alocadas à algum
projeto, não registraram nenhuma hora trabalhada. Sua tarefa é preparar um relatório que liste o nome do departamento, o nome do projeto e o nome dos funcionários
que, mesmo estando alocados a algum projeto, não registraram nenhuma hora trabalhada.

| nome_departamento | nome_projeto    | funcionario | horas |
|:---:|:---:|:---:|:---:|
| Matriz            | Reorganização   | Jorge       | 0.0h  |

### **Questão 13:**
Durante o natal deste ano a empresa irá presentear todos os funcionários e todos os dependentes (sim, a empresa vai dar um presente para cada
funcionário e um presente para cada dependente de cada funcionário) e pediu para
que você preparasse um relatório que listasse o nome completo das pessoas a serem
presenteadas (funcionários e dependentes), o sexo e a idade em anos completos
(para poder comprar um presente adequado). Esse relatório deve estar ordenado
pela idade em anos completos, de forma decrescente.

| nome              | sexo      | idade |
|:---:|:---:|:---:|
| Jorge E Brito     | Masculino |    84 |
| Jennifer S Souza  | Feminino  |    80 |
| Antonio S Souza   | Masculino |    80 |
| Fernando T Wong   | Masculino |    66 |
| Janaína T Wong    | Feminino  |    64 |
| Ronaldo K Lima    | Masculino |    59 |
| João B Silva      | Masculino |    57 |
| Elizabeth B Silva | Feminino  |    55 |
| Alice J Zelaya    | Feminino  |    54 |
| André V Pereira   | Masculino |    53 |
| Joice A Leite     | Feminino  |    49 |
| Tiago T Wong      | Masculino |    38 |
| Alicia T Wong     | Feminino  |    36 |
| Michael B Silva   | Masculino |    34 |
| Alicia B Silva    | Feminino  |    33 |

### **Questão 14:**
Prepare um relatório que exiba quantos funcionários cada departamento tem.

| nome_departamento | numero_de_funcionarios |
|:---:|:---:|
| Administração     |                      3 |
| Matriz            |                      1 |
| Pesquisa          |                      4 |



### **Questão 15:**
Como um funcionário pode estar alocado em mais de um projeto,
prepare um relatório que exiba o nome completo do funcionário, o departamento
desse funcionário e o nome dos projetos em que cada funcionário está alocado.
Atenção: se houver algum funcionário que não está alocado em nenhum projeto,
o nome completo e o departamento também devem aparecer no relatório.

| nome             | nome_departamento | nome_projeto     |
|:---:|:---:|:---:|
| Alice J Zelaya   | Administração     | Informatização   |
| Alice J Zelaya   | Administração     | Novosbenefícios  |
| André V Pereira  | Administração     | Informatização   |
| André V Pereira  | Administração     | Novosbenefícios  |
| Fernando T Wong  | Pesquisa          | Reorganização    |
| Fernando T Wong  | Pesquisa          | ProdutoZ         |
| Fernando T Wong  | Pesquisa          | Informatização   |
| Fernando T Wong  | Pesquisa          | ProdutoY         |
| Jennifer S Souza | Administração     | Novosbenefícios  |
| Jennifer S Souza | Administração     | Reorganização    |
| João B Silva     | Pesquisa          | ProdutoY         |
| João B Silva     | Pesquisa          | ProdutoX         |
| Joice A Leite    | Pesquisa          | ProdutoX         |
| Joice A Leite    | Pesquisa          | ProdutoY         |
| Jorge E Brito    | Matriz            | Reorganização    |
| Ronaldo K Lima   | Pesquisa          | ProdutoZ         |

## 3. Conclusão
Esse PSet comparado ao primeiro foi mais simples, mas ainda houve algumas questões que me travaram durante um bom tempo. O que me surpreendi foi com alguns erros "bobos" de digitação no primeiro PSet que acabaram me afetando nesse e que ao longo dos relatórios me dificultaram em algumas partes.

Conclui com esse PSet a importância das tabelas estarem bem feitas e escritas corretamente, e o quanto um "simples" erro pode significar 40 minutos refazendo do início. Aprendi mais sobre os conceitos de álgebra relacional e como há diversos caminhos para um mesmo relatório.
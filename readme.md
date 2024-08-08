# TRABALHO 01:  Título do Trabalho
Trabalho desenvolvido durante a disciplina de BD1

# Sumário

### 1. COMPONENTES<br>
Integrantes do grupo<br>
Brayan Mazega de Freitas Souza - brayanmazega@gmail.com...<br>
Irene Schmidt da Silva Alves -  irenealvesbsi@gmail.com...<br>
Irlane Schmidt da Silva Alves -  irlanesilvabsi@gmail.com...<br>


### 2.MINI-MUNDO<br>

Descrever o mini-mundo! (Não deve ser maior do que 30 linhas, se necessário resumir para justar) <br>
Entrevista com o usuário e identificação dos requisitos.(quando for o caso de sistemas com cliente  real)<br>
Descrição textual das regras de negócio definidas como um  subconjunto do mundo real 
cujos elementos são propriedades que desejamos incluir, processar, armazenar, 
gerenciar, atualizar, e que descrevem a proposta/solução a ser desenvolvida.

> O sistema proposto para uma rede de academias conterá as informações aqui detalhadas. De uma franquia, serão armazenados o código da franquia, a localização, o horário de abertura e o horário de fechamento. É válido ressaltar que a rede de academias possui alunos e professores, que, por sua vez, são pessoas. De uma pessoa, deseja-se saber o código, o nome, o CPF e a data de nascimento. De um aluno, deseja-se saber também a altura e o peso. Já de um professor, deseja-se saber a especialidade. Um professor pode trabalhar em uma ou mais franquias e pode auxiliar em uma ou mais atividades, sendo necessário saber a data e o horário de início e de fim do trabalho. De uma atividade, é desejável saber o código e o nome. Um aluno assina um e somente um plano. De um plano, deve-se saber o código, o nome, o período de duração do plano e o valor mensal. Uma atividade pode ser oferecida em nenhuma ou mais de uma franquia. Um aluno pode frequentar nenhuma ou mais franquias, desejando-se saber a data e o horário de entrada e de saída.

### 3.PERGUNTAS A SEREM RESPONDIDAS<br>
#### 3.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?
    a) O sistema proposto poderá fornecer quais tipos de relatórios e informaçes? 
    b) Crie uma lista com os 5 principais relatórios que poderão ser obtidos por meio do sistema proposto!
    
> A academia precisa inicialmente dos seguintes relatórios:

> Relatório de Alunos por Plano: Detalhando o nome, CPF, peso, data de nascimento, altura e o plano assinado por cada aluno.
> Relatório de Professores por Especialidade: Listando o nome, CPF, data de nascimento e especialidade de cada professor, incluindo as franquias em que trabalham.
> Relatório de Utilização das Academias: Informando a localização das academias, horários de abertura e fechamento, quantidade de alunos e as franquias associadas.
> Relatório Financeiro dos Planos: Incluindo nome, valor e período de cada plano, com análise de receitas geradas.
> Relatório de Atividades: Detalhando o nome da atividade, o professor responsável e as franquias onde são oferecidas.


    
### 5.MODELO CONCEITUAL<br>
    A) Utilizar a Notação adequada (Preferencialmente utilizar o BR Modelo 3)
    B) O mínimo de entidades do modelo conceitual pare este trabalho será igual a 3 e o Máximo 5.
        * informe quais são as 3 principais entidades do sistema em densenvolvimento<br>(se houverem mais de 3 entidades, pense na importância da entidade para o sistema)       
    C) Principais fluxos de informação/entidades do sistema (mínimo 3). <br>Dica: normalmente estes fluxos estão associados as tabelas que conterão maior quantidade de dados 
    D) Qualidade e Clareza
        Garantir que a semântica dos atributos seja clara no esquema (nomes coerentes com os dados).
        Criar o esquema de forma a garantir a redução de informação redundante, possibilidade de valores null, 
        e tuplas falsas (Aplicar os conceitos de normalização abordados).   
        
![Modelo conceitual](https://github.com/user-attachments/assets/cb547b1d-fe63-49eb-8c9e-03e7345d3730)
    
    
#### 5.1 Validação do Modelo Conceitual
    [Grupo01]: [Nomes dos que participaram na avaliação]
    [Grupo02]: [Nomes dos que participaram na avaliação]

#### 5.2 Descrição dos dados 
ALUNO: Tabela que armazena as informações relativas aos alunos.<br>

    NOME: Campo que armazena o nome completo do aluno.<br>
    CPF: Campo que armazena o número de Cadastro de Pessoa Física para cada aluno.<br>
    PESO: Campo que armazena o peso do aluno.<br>
    DATA DE NASCIMENTO: Campo que armazena a data de nascimento do aluno.<br>
    ALTURA: Campo que armazena a altura do aluno.<br>

PROFESSOR: Tabela que armazena as informações relativas aos professores.<br>

    NOME: Campo que armazena o nome completo do professor.<br>
    CPF: Campo que armazena o número de Cadastro de Pessoa Física para cada professor.<br>
    DATA DE NASCIMENTO: Campo que armazena a data de nascimento do professor.<br>
    ESPECIALIDADE: Campo que armazena a especialidade do professor.<br>

FRANQUIA: Tabela que armazena as informações relativas às academias.<br>

    LOCALIZAÇÃO: Campo que armazena a localização da academia.<br>
    HORÁRIO DE ABERTURA: Campo que armazena o horário de abertura da academia.<br>
    HORÁRIO DE FECHAMENTO: Campo que armazena o horário de fechamento da academia.<br>

PLANO: Tabela que armazena as informações relativas aos planos oferecidos.<br>

    NOME: Campo que armazena o nome do plano.<br>
    VALOR: Campo que armazena o valor mensal do plano.<br>
    PERÍODO: Campo que armazena o período de duração do plano.<br>

ATIVIDADE: Tabela que armazena as informações relativas às atividades oferecidas.<br>

    NOME: Campo que armazena o nome da atividade.<br>
    

># Marco de Entrega 01: Do item 1 até o item 5.2 (5 PTS) <br> 

### 6	MODELO LÓGICO<br>
        a) inclusão do esquema lógico do banco de dados
        b) verificação de correspondencia com o modelo conceitual 
        (não serão aceitos modelos que não estejam em conformidade)

 ![image](https://github.com/user-attachments/assets/45f4b03f-a2d1-4e31-9a9b-b692a77cf74d)


### 7	MODELO FÍSICO<br>
        a) inclusão das instruções de criacão das estruturas em SQL/DDL 
        (criação de tabelas, alterações, etc..) 

 Link do arquivo SQL: https://drive.google.com/file/d/1S4HYxToX4RqePdT1QIH37pUuOmP0g7R6/view?usp=drive_link

CREATE TABLE PESSOA (
    codigo INTEGER PRIMARY KEY,
    nome VARCHAR,
    cpf VARCHAR,
    data_nascimento DATE
);

CREATE TABLE ATIVIDADE (
    codigo INTEGER PRIMARY KEY,
    nome VARCHAR
);

CREATE TABLE ALUNO (
    altura FLOAT,
    peso FLOAT,
    FK_PESSOA_codigo INTEGER PRIMARY KEY
);

CREATE TABLE PROFESSOR (
    especialidade VARCHAR,
    FK_PESSOA_codigo INTEGER PRIMARY KEY
);

CREATE TABLE FRANQUIA (
    codigo INTEGER PRIMARY KEY,
    localizacao VARCHAR,
    hora_abertura TIME,
    hora_fechamento TIME
);

CREATE TABLE PLANO (
    codigo INTEGER PRIMARY KEY,
    nome VARCHAR,
    periodo VARCHAR
);

CREATE TABLE PROFESSOR_FRANQUIA (
    fk_PROFESSOR_FK_PESSOA_codigo INTEGER,
    fk_FRANQUIA_codigo INTEGER,
    data_hora_inicio TIMESTAMP,
    data_hora_fim TIMESTAMP
);

CREATE TABLE ATIVIDADE_FRANQUIA (
    fk_ATIVIDADE_codigo INTEGER,
    fk_FRANQUIA_codigo INTEGER
);

CREATE TABLE PROFESSOR_ATIVIDADE (
    fk_ATIVIDADE_codigo INTEGER,
    fk_PROFESSOR_FK_PESSOA_codigo INTEGER
);

CREATE TABLE ALUNO_FRANQUIA (
    fk_FRANQUIA_codigo INTEGER,
    fk_ALUNO_FK_PESSOA_codigo INTEGER,
    data_hora_inicio TIMESTAMP,
    data_hora_fim TIMESTAMP
);

CREATE TABLE ALUNO_PLANO (
    codigo INTEGER PRIMARY KEY,
    FK_PLANO_codigo INTEGER,
    FK_ALUNO_FK_PESSOA_codigo INTEGER,
    valor NUMERIC (5,2),
    data DATE
);
 
ALTER TABLE ALUNO ADD CONSTRAINT FK_ALUNO_2
    FOREIGN KEY (FK_PESSOA_codigo)
    REFERENCES PESSOA (codigo)
    ON DELETE CASCADE;
 
ALTER TABLE PROFESSOR ADD CONSTRAINT FK_PROFESSOR_2
    FOREIGN KEY (FK_PESSOA_codigo)
    REFERENCES PESSOA (codigo)
    ON DELETE CASCADE;
 
ALTER TABLE PROFESSOR_FRANQUIA ADD CONSTRAINT FK_PROFESSOR_FRANQUIA_1
    FOREIGN KEY (fk_PROFESSOR_FK_PESSOA_codigo)
    REFERENCES PROFESSOR (FK_PESSOA_codigo)
    ON DELETE RESTRICT;
 
ALTER TABLE PROFESSOR_FRANQUIA ADD CONSTRAINT FK_PROFESSOR_FRANQUIA_2
    FOREIGN KEY (fk_FRANQUIA_codigo)
    REFERENCES FRANQUIA (codigo)
    ON DELETE RESTRICT;
 
ALTER TABLE ATIVIDADE_FRANQUIA ADD CONSTRAINT FK_ATIVIDADE_FRANQUIA_1
    FOREIGN KEY (fk_ATIVIDADE_codigo)
    REFERENCES ATIVIDADE (codigo)
    ON DELETE RESTRICT;
 
ALTER TABLE ATIVIDADE_FRANQUIA ADD CONSTRAINT FK_ATIVIDADE_FRANQUIA_2
    FOREIGN KEY (fk_FRANQUIA_codigo)
    REFERENCES FRANQUIA (codigo)
    ON DELETE RESTRICT;
 
ALTER TABLE PROFESSOR_ATIVIDADE ADD CONSTRAINT FK_PROFESSOR_ATIVIDADE_1
    FOREIGN KEY (fk_ATIVIDADE_codigo)
    REFERENCES ATIVIDADE (codigo)
    ON DELETE RESTRICT;
 
ALTER TABLE PROFESSOR_ATIVIDADE ADD CONSTRAINT FK_PROFESSOR_ATIVIDADE_2
    FOREIGN KEY (fk_PROFESSOR_FK_PESSOA_codigo)
    REFERENCES PROFESSOR (FK_PESSOA_codigo)
    ON DELETE CASCADE;
 
ALTER TABLE ALUNO_FRANQUIA ADD CONSTRAINT FK_ALUNO_FRANQUIA_1
    FOREIGN KEY (fk_FRANQUIA_codigo)
    REFERENCES FRANQUIA (codigo)
    ON DELETE CASCADE;
 
ALTER TABLE ALUNO_FRANQUIA ADD CONSTRAINT FK_ALUNO_FRANQUIA_2
    FOREIGN KEY (fk_ALUNO_FK_PESSOA_codigo)
    REFERENCES ALUNO (FK_PESSOA_codigo)
    ON DELETE CASCADE;
 
ALTER TABLE ALUNO_PLANO ADD CONSTRAINT FK_ALUNO_PLANO_1
    FOREIGN KEY (FK_PLANO_codigo)
    REFERENCES PLANO (codigo)
    on delete RESTRICT;
 
ALTER TABLE ALUNO_PLANO ADD CONSTRAINT FK_ALUNO_PLANO_3
    FOREIGN KEY (FK_ALUNO_FK_PESSOA_codigo)
    REFERENCES ALUNO (FK_PESSOA_codigo)
    on delete CASCADE;

      
### 8	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
        a) Script das instruções relativas a inclusão de dados 
	Requisito mínimo: (Script dev conter: Drop para exclusão de tabelas + create definição de para tabelas e estruturas de dados + insert para dados a serem inseridos)
        OBS
	1) Criar um novo banco de dados para testar a restauracao (em caso de falha na restauração o grupo não pontuará neste quesito)
        2) script deve ser incluso no template em um arquivo no formato .SQL

Link do arquivo SQL: https://drive.google.com/file/d/1u_U50AiRucYDfsYLh5BSO2fm2RawzTmN/view?usp=drive_link

INSERT INTO pessoa (codigo, nome, cpf, data_nascimento) 
VALUES 
    (1, 'João Silva', '123.456.789-00', '1990-05-15'),
    (2, 'Maria Santos', '987.654.321-00', '1985-07-20'),
    (3, 'Pedro Souza', '456.789.123-00', '1998-02-10'),
    (4, 'Ana Oliveira', '321.654.987-00', '1977-11-25'),
    (5, 'José Pereira', '789.123.456-00', '2000-09-05'),
    (6, 'Felipe Azevedo', '855.584.588-00', '1986-10-12'),
    (7, 'Bruna Gomes', '168.846.752-00', '1995-02-06');
    
INSERT INTO aluno (altura, peso, fk_pessoa_codigo) 
VALUES 
    (1.75, 70.5, 1),   
    (1.68, 65.0, 2),  
    (1.80, 80.2, 3);   

INSERT INTO professor (especialidade, fk_pessoa_codigo) 
VALUES 
    ('Educação Física', 4),   
    ('Nutrição', 5),
   	('Musculação',6),
    ('Fit dance', 7);
    
INSERT INTO plano (codigo, nome, periodo)
VALUES
    (1, 'bronze', 'mensal'),
    (2, 'silver', 'trimestral'),
    (3, 'gold', 'semestral');
   
INSERT INTO aluno_plano (codigo, fk_plano_codigo, fk_aluno_fk_pessoa_codigo, valor, data)
VALUES
    (1, 1, 1, 80.00, '2024-07-11'),  
    (2, 2, 2, 300.00, '2024-07-11'),  
    (3, 3, 3, 500.00, '2024-07-11'); 

INSERT INTO franquia (codigo, localizacao, hora_abertura, hora_fechamento)
VALUES
    (1, 'Jardim A, 123', '05:00:00', '22:00:00'),
    (2, 'Praça Verde, 456', '06:30:00', '23:30:00');

insert into atividade (codigo, nome)
values
	(1, 'Musculação'),
	(2, 'Zumba'),
	(3, 'crossfit'),
	(4, 'Acompanhamento dieta');
	
insert into atividade_franquia (fk_atividade_codigo, fk_franquia_codigo)
values
	(1,1),
	(2,2),
	(3,2),
	(4,1);

insert into aluno_franquia (fk_franquia_codigo, fk_aluno_fk_pessoa_codigo, data_hora_inicio, data_hora_fim)
values
	(1,1,'2024-07-11 18:00:00', '2024-07-11 19:30:00'),
	(2,2,'2024-05-10 14:00:00', '2024-05-10 15:30:00'),
	(1,3,'2024-03-02 07:00:00', '2024-03-02 08:00:00');

insert into professor_franquia (fk_professor_fk_pessoa_codigo,fk_franquia_codigo,data_hora_inicio,data_hora_fim)
values
	(4,2,'2024-07-11 06:30:00', '2024-07-11 14:30:00'),
	(5,1,'2024-05-10 14:00:00', '2024-05-10 22:00:00'),
	(6,1,'2024-05-10 05:00:00', '2024-05-10 14:00:00'),
	(7,2,'2024-07-11 14:30:00', '2024-07-11 23:30:00');

insert into professor_atividade (fk_atividade_codigo,fk_professor_fk_pessoa_codigo)
values
	(1,6),
	(2,7),
	(3,4),
	(4,5);

### 9	TABELAS E PRINCIPAIS CONSULTAS<br>
    OBS: Usa template da disciplina disponibilizado no Colab.<br>
#### 9.1	CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS (Todas) <br>

#### 9.2	CONSULTAS DAS TABELAS COM FILTROS WHERE (Mínimo 4)<br>

#### 9.3	CONSULTAS QUE USAM OPERADORES LÓGICOS, ARITMÉTICOS E TABELAS OU CAMPOS RENOMEADOS (Mínimo 11)
    a) Criar 5 consultas que envolvam os operadores lógicos AND, OR e Not
    b) Criar no mínimo 3 consultas com operadores aritméticos 
    c) Criar no mínimo 3 consultas com operação de renomear nomes de campos ou tabelas

#### 9.4	CONSULTAS QUE USAM OPERADORES LIKE E DATAS (Mínimo 12) <br>
    a) Criar outras 5 consultas que envolvam like ou ilike
    b) Criar uma consulta para cada tipo de função data apresentada.

># Marco de Entrega 02: Do item 6. até o item 9.1 (5 PTS) <br>

#### 9.5	INSTRUÇÕES APLICANDO ATUALIZAÇÃO E EXCLUSÃO DE DADOS (Mínimo 6)<br>
    a) Criar minimo 3 de exclusão
    b) Criar minimo 3 de atualização

#### 9.6	CONSULTAS COM INNER JOIN E ORDER BY (Mínimo 6)<br>
    a) Uma junção que envolva todas as tabelas possuindo no mínimo 2 registros no resultado
    b) Outras junções que o grupo considere como sendo as de principal importância para o trabalho

#### 9.7	CONSULTAS COM GROUP BY E FUNÇÕES DE AGRUPAMENTO (Mínimo 6)<br>
    a) Criar minimo 2 envolvendo algum tipo de junção

#### 9.8	CONSULTAS COM LEFT, RIGHT E FULL JOIN (Mínimo 4)<br>
    a) Criar minimo 1 de cada tipo

#### 9.9	CONSULTAS COM SELF JOIN E VIEW (Mínimo 6)<br>
        a) Uma junção que envolva Self Join (caso não ocorra na base justificar e substituir por uma view)
        b) Outras junções com views que o grupo considere como sendo de relevante importância para o trabalho

#### 9.10	SUBCONSULTAS (Mínimo 4)<br>
     a) Criar minimo 1 envolvendo GROUP BY
     b) Criar minimo 1 envolvendo algum tipo de junção

># Marco de Entrega 03: Do item 9.2 até o ítem 9.10 (10 PTS)<br>

### 10 RELATÓRIOS E GRÁFICOS

#### a) análises e resultados provenientes do banco de dados desenvolvido (usar modelo disponível)
#### b) link com exemplo de relatórios será disponiblizado pelo professor no AVA
#### OBS: Esta é uma atividade de grande relevância no contexto do trabalho. Mantenha o foco nos 5 principais relatórios/resultados visando obter o melhor resultado possível.

    

### 11	AJUSTES DA DOCUMENTAÇÃO, CRIAÇÃO DOS SLIDES E VÍDEO PARA APRESENTAÇAO FINAL <br>

#### a) Modelo (pecha kucha)<br>
#### b) Tempo de apresentação 6:40 

># Marco de Entrega 04: Itens 10 e 11 (20 PTS) <br>
<br>
<br>




### 12 FORMATACAO NO GIT:<br> 
https://help.github.com/articles/basic-writing-and-formatting-syntax/
<comentario no git>
    
##### About Formatting
    https://help.github.com/articles/about-writing-and-formatting-on-github/
    
##### Basic Formatting in Git
    
    https://help.github.com/articles/basic-writing-and-formatting-syntax/#referencing-issues-and-pull-requests
    
    
##### Working with advanced formatting
    https://help.github.com/articles/working-with-advanced-formatting/
#### Mastering Markdown
    https://guides.github.com/features/mastering-markdown/

    
### OBSERVAÇÕES IMPORTANTES

#### Todos os arquivos que fazem parte do projeto (Imagens, pdfs, arquivos fonte, etc..), devem estar presentes no GIT. Os arquivos do projeto vigente não devem ser armazenados em quaisquer outras plataformas.
1. <strong>Caso existam arquivos com conteúdos sigilosos<strong>, comunicar o professor que definirá em conjunto com o grupo a melhor forma de armazenamento do arquivo.

#### Todos os grupos deverão fazer Fork deste repositório e dar permissões administrativas ao usuário do git "profmoisesomena", para acompanhamento do trabalho.

#### Os usuários criados no GIT devem possuir o nome de identificação do aluno (não serão aceitos nomes como Eu123, meuprojeto, pro456, etc). Em caso de dúvida comunicar o professor.


Link para BrModelo:<br>
http://www.sis4.com/brModelo/download.html
<br>


Link para curso de GIT<br>
![https://www.youtube.com/curso_git](https://www.youtube.com/playlist?list=PLo7sFyCeiGUdIyEmHdfbuD2eR4XPDqnN2?raw=true "Title")

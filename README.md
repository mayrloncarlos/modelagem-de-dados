# Sistema Acadêmico de Pós-Graduação

**DESCRIÇÃO WEB AULA**  
A Federação Internacional de Pós-Graduação (FIP) identificou que parte dos problemas no atendimento a alunos e professores acontece pelas inconsistências das tarefas feitas manualmente. Você foi convidado a analisar o Setor de Serviços Acadêmicos (SSA) e propor um modelo de dados que os auxilie.

**OBJETIVO**  
Analisar um minimundo e propor um modelo conceitual que o represente.  

**COMPETÊNCIA/HABILIDADE**  
- Analisar um minimundo.  
- Aplicar os conceitos de modelagem conceitual de dados    

**DESENVOLVIMENTO**  
Mini-mundo: O Setor de Serviços Acadêmicos (SSA) da Federação Internacional de Pós-Graduação (FIP) possui como principal objetivo fornecer cursos de pós-graduação para qualquer pessoa já formada. Atualmente o controle acadêmico dos alunos e professores é feito de forma manual, acarretando muitas inconsistências e demoras. O principal objetivo do sistema é realizar esse controle acadêmico, contemplando principalmente as atividades abaixo relacionadas.  
Existem vários cursos oferecidos pela FIP. Cada curso é composto de várias disciplinas e existem disciplinas comuns a vários cursos. Todos os professores só são contratados se possuem em seu currículo um título de pós-graduação (mestrado ou doutorado) ou foi responsável em alguma área de interesse do SSA em alguma instituição de ensino superior (não há registro sobre essas instituições). Possuem também um registro no MEC e são habilitados para lecionar pelo menos uma matéria (normalmente possuem habilitação para mais de uma) e só lecionam se possuem a devida habilitação. Os professores que já lecionaram em mais de quatro períodos podem pedir bolsa integral para se inscrever como aluno de um curso do FIP.  
Cada vez que uma pessoa se inscreve em um curso, passa a ser considerado aluno FIP, ganha uma nova matrícula (única para aquele curso). Em qualquer curso do FIP o aluno só poderá se matricular na mesma cadeira cinco vezes, e só poderá realizar no máximo 12 disciplinas diferentes.  
A média mínima para aprovação  em qualquer disciplina é 7 (sete), e o aluno só em uma poderá se matricular disciplina se tiver sido aprovado  nas disciplinas que são pré-requisitos desta (no curso onde está inscrito). Finalmente, nesta instituição, o aluno pode refazer uma disciplina, que já foi aprovado, com o intuito de aumentar a média (vale sempre a maior média).
O sistema também deve ser capaz de emitir:  
**a)**	Relação de todos os professores (CPF, nome, registro no MEC, título e/ou responsabilidade e a descrição da área) que já lecionaram uma determinada disciplina em um determinado período.  
**b)**	Relatório estatístico de aprovações e reprovações de uma determinada disciplina, ao longo do tempo.  
**c)**	Relação das disciplinas (sigla, nome, carga horária) que tem o índice de reprovação maior que um percentual específico.  
**d)**	Relação dos alunos que já cursaram mais de quatro disciplinas em um curso e sempre foram aprovados, contendo para cada aluno seu CPF, nome, bairro  e, para cada curso onde tenha alcançado este quesito, o nome do curso e sua matrícula neste curso.  
**e)**	Relatório contendo os cursos (sigla e nome do curso) e os alunos inscritos (CPF, nome, bairro e matrícula) em um período.  
**f)**	Histórico Escolar de um aluno, contendo: nome do curso, nome do aluno, matrícula e uma relação contendo todas as disciplinas cursada (nome da disciplina, período, média final da disciplina) e média final do curso até o momento (média aritmética).  

Para efeitos de simplificação, vamos desconsiderar outros aspectos envolvidos como: trancamento, cancelamento, desligamento, alterações, turno, turma, horários, pagamento, validade (da habilitação e inscrição) CPF fantasma ou duplicado, mudanças no currículo de um curso, limpeza de informações etc.  

**PRODUTO/RESULTADO**  
Parte 1:  
1)	MER  Conceitual Completo (entidades, relacionamentos, atributos, atributo identificador, cardinalidades)  
2)	Justificativa das cardinalidades de, pelo menos, dois relacionamentos (mínimo e máximo)  

Parte 2:  
A partir do MER construído na Parte 1, efetue o mapeamento do esquema de Banco de Dados Relacional.  

# -sintaxy_sql_atv03_04
ALTER TABLE alunos ADD COLUMN favorites VARCHAR(3);
UPDATE alunos SET favorites = 'SIM' WHERE ID <= 10;


SELECT nome
FROM AlunosSala.alunos
WHERE favorites = 'SIM'
LIMIT 10;


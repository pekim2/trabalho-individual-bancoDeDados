# trabalho-individual-bancoDeDados

- Existem outras entidades além dessas três? Sim, existem as matrículas e facilitadores.


Os principais campos e tipos e como as entidades estão relacionadas está logo abaixo:

Case de uma instituição educacional - Resília
A resilia irá ter alunos, facilitadores, cursos, turmas e matrículas
- Um curso possui nome, carga horária e preço. Carga horária é o tempo de curso e o preço é o valor a ser pago.
- Para a matrícula foi feito um registro para turma e alunos, de tal forma que é necessário uma turma aberta e alunos cadastrados.
- A carga horária foi replicada na entidade de turmas apesar de ja está relacionado com o curso, pois caso durante o curso a carga horária da turma modifique não prejudique as informações.
- Um curso pode ter um ou várias turmas e um facilitador também.
- E por fim, as matrículas podem ter várias turmas e alunos registrados.

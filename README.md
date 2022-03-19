# Revisão de modelagem de banco de dados

O objetivo aqui é relembrar o que aprendi na disciplina de modelagem quando a cursei alguns semestres atrás na faculdade. 
E, finalmente, implementar um banco de dados passando pelas etapas de modelagem conceitual, lógica e física.


 - Conceitual
    - Entidade
    - Atributos
    - Relacionamentos (ainda sem especificação de cardinalidade)
    - Nos relacionamentos N:M, criar entidades associativas

    Por exemplo, curso (1, n) ------------possui-------------- (1, n) disciplina    


    Fazemos, então:

    curso (1, 1) -----possui---- (1, n)curso_disciplina (1, n) -----pertence---- (1, 1)disciplina


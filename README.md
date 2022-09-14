## Atividade: Utilizando o like (para titulo e sinopse)

Você deverá criar uma consulta nos livros, buscando por:

1. Título
2. Título e Sinopse
3. Categoria
4. Titulo, Sinopse e Categoria
5. Autor
6. Titulo, sinopse e Autor
7. Titulo, Sinopse, Categoria e Autor

## Consultas

Consultas | Código
--------- | ------
Título | SELECT * FROM vwLivros WHERE titulo LIKE '%Aj%';
Título e Sinopse | SELECT * FROM vwLivros WHERE titulo LIKE '%Ajax%' and sinopse LIKE '%A%';
Categoria | SELECT * FROM vwLivros WHERE genero LIKE '%Poe%';
Titulo, Sinopse e Categoria | SELECT * FROM vwLivros WHERE titulo LIKE '%Ajax%' and sinopse LIKE '%a%' and genero LIKE '%poesia%';
Autor | SELECT * FROM vwLivros WHERE autor LIKE '%Hugo%';
Titulo, sinopse e Autor | SELECT * FROM vwLivros WHERE titulo LIKE '%Java%' and sinopse LIKE '%linguagem%' and autor LIKE '%Hugo%';
Titulo, Sinopse, Categoria e Autor | SELECT * FROM vwLivros WHERE titulo LIKE '%Ajax%' and sinopse LIKE '%a%' and genero LIKE '%poesia%' and autor LIKE '%Love%';

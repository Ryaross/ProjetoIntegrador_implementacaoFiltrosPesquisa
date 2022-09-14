## Atividade: Utilizando o like (para titulo e sinopse)

Você deverá criar uma consulta nos livros, buscando por:

- [x] Título
- [x] Título e Sinopse
- [x] Categoria
- [x] Titulo, Sinopse e Categoria
- [x] Autor
- [x] Titulo, sinopse e Autor
- [x] Titulo, Sinopse, Categoria e Autor

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

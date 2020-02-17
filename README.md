## End Points configurados

- `/noticias`:
  - **GET**: devolve lista com todas as notícias salvas.
  - **POST**: salva notícia e a retorna com o id gerado.

- `/noticias/{id}`: as operações são feitas apenas com ids existentes.
  - **PUT**: altera notícia e a retorna com as alterações realizadas
  - **DELETE**: remove notícia

O objeto de uma notícia segue o seguinte modelo:

```
{
    "id": "1",
    "titulo": "Novos Apps estão sendo desenvolvidos em Kotlin",
    "texto": "Após anúncio da Google sobre o desenvolvimento de Apps Android por meio da linguagem Kotlin...",
}
```
# app-kotlin-lifecycle-aware

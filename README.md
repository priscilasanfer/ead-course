# EAD Course

### Anotações

- *@EntityGraph(attributePaths = {"course"})*: Alterna de lazy para eager ou seja é uma feature para consultas de subrecursos 
de forma a forçar o carregamento eager de entidades relacionadas e ainda evitando o problema de N+1 e não substitui o jpql
  
- *@Fetch(FetchMode.SUBSELECT)* = Faz uma consulta para o curso e uma consulta para os modulos desse curso respeitando o FetchType
- *@Modifying + @Query* = Quando precisa deletar ou atualizar um dado de forma customizada 

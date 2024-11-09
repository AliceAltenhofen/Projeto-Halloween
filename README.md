# BancoFilmeCorra //#significa titulo
## Banco de dados para inserção de informações sobre o filme Corra
### Esse banco de dados é dividido em 5 tabelas. A primeira é chamada contexto_sociocultural e é usada para descrever o contexto cultural que cada familia esta inserida, tendo como atributos principais a descriçao desse contexto, a classe social, o nome desse contexto e a sua respectiva familia. A tabela familia é utilzada para inserir somente o nome da familia e seu numero id para fazer relação com as demais tabelas. A tabela membrofamilia_constitui é usada para mostrar quais persoagens fazem parte de cada familia, tendo como principais atributos as id's de cada personagem e familia e sua respectiva função nessa familia. A tabela personagem .tratamento

Tabela: contexto_sociocultural. Descrição: armazena informaçôes referentes ao contexto sociocultural em que cada familia esta inserida.
Coluna:id_contexto_sociocultura: identificador do contexto. descrição_contexto_sociocultura: usuado para descrevre a descrição do contexto. classe_contexto_sociocultura:identifica a condição economica de cada familia. nome_contexto_sociocultural: é o nome dado para descrever o contexto da familia. fk_familia_id_familia:chave estrangeira usada para identificar a familia inserida naquele contexto. 
Tabela: familia. Descrição: é usada somente para inserir o nome da familia. 
Coluna: id_familia: numero identificador de cada familia. nome_familia: nome dado a familia
_


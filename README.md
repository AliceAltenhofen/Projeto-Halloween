# BDFilmeCorra

# Descrição
Esse é um banco de dados com o objetivo de armazenar dados sobre o filme Corra (2017).

# Estrutura do Banco de Dados
Esse banco de dados é dividido em 5 tabelas. 
Tabela: contexto_sociocultural Descrição: Armazena a descrição do contexto cultural em que cada família está inserida. Colunas: - 'origem': Identifica a condição econômica do personagem. -'classe_social': A posição econômica do personagem/família na sociedade. -'crenca': Religião seguida pelo personagem/família. -'fk_familia_familia_id': Chave estrangeira da tabela família. -'fk_personagem_personagem_id': Chave estrangeira da tabela personagem.
Tabela: tratamento Descrição: Tratamento aplicado pela família a um personagem. Colunas: -'tratamento_id': Identificador únio do tratamento. -'tratamento_nome': Nome da etapa do tratamento. -'descricao': Descrição da etapa do tratamento aplicado por um membro da família a um personagem.
Tabela: familia. Descrição: Usada para inserir uma família do filme. Colunas: -'familia_id': Identificador único família. -'familia_nome': Sobrenome da família do personagem.
Tabela: Personagem. Descrição: Tabela utilizada para inserir os dados dos personagens do filme. Colunas: -'personagem_id': Identificador único do personagem. -'personagem_nome': Primeiro nome do personagem. -'etnia': Para classificar a etnia do personagem. -'genero': Identificador do gênero do personagem. -'fk_tratamento_tratamento_id': Chave estrangeira do tratamento aplicado no personagem, podendo ou  não ser nulo.
Tabela: MembroFamilia. Descrição: Identifica os membros de determinada família. Colunas: -'estado_psicologico': Identifica se o personagem é controlador ou espectador. -'fk_personagem_personagem_id': Chave estrangeira usada para identificar o personagem. -'fk_familia_familia_id': Chave estrangeira para identificar a família a qual o personagem pertence.

# Diagrama ER
<img src=".\FilmeCorraConceitualImg.png">

# Instruções de Configuração
## 1. Instale o PostgreSQL:
https://www.enterprisedb.com/postgresql-tutorial-resources-training-1?uuid=d0ed4d28-191f-4273-b6a9-427ab0b4c448&campaignId=Product_Trial_PostgreSQL_15
## 2. Crie o banco de dados
```SQL
CREATE DATABASE FilmeCorraExport
```

# Licença
MIT License

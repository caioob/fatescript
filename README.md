## Descrição do projeto

Timeline de lançamento de banners para personagens de Fate
O usuário escolhe personagens que ele deseja adquirir no ano
A aplicação retorna uma linha do tempo contendo os banners e a ordem que eles serão lançados

## Modelagem de dados

Principais tipos de dados que são pertinentes ao projeto

### Banner
Contém:
- Duração
- Personagem

Ações possíveis:
- Summon: abrir um banner

### Usuário
Contém:
- Personagens que ele escolher
- Timeline própria

### Personagem
Contém:
- Id
- Nome
- Imagem

### Timeline
Contém:
- Usuário
- Período de tempo
- Banners

Ações:
- Timeline/Create
- Timeline/Read
- Timeline/Update
- Timeline/Delete

- Timeline/Export - exportar a timeline em outro formato


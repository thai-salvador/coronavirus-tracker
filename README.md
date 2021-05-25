# Coronavirus Tracker 📊

Usando o ASP .NET Core Web API, foi criada uma API onde seria possível ter um mapeamento de pessoas infectadas com base na localização, bem como, faixa etária e sexo biológico.

Configuramos um banco NoSQL (MongoDB), permitindo que tivéssemos documentos BSON, ao invés de tabelas. Foi optado pelo automapping para mapear as nossas entidades no banco de dados. 

Tratamos a dependency injection do nosso banco e fizemos uso de uma DTO com o objetivo de controlar as informações que os usuários veem. Foi utilizado o Postman para teste e desenvolvimento da nossa API.

É possível criar dashboards com charts diretamente no MongoDB Atlas, o que facilitaria o monitoramento de dados importantes, com atualização automática à medida que os dados forem sendo inseridos no banco. Existem alguns pontos a serem melhor implementados futuramente. 


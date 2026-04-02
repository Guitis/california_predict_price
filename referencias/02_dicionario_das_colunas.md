# Dicionário das colunas

- `median_income`: renda mediana no grupo de blocos (em dezenas de milhares de dólares) - *PODE SER QUE TENHA TIDO UM CORTE MANUAL (ALGUÉM ALTEROU OS DADOS)* *IREMOS TER CERTEZA OBSERVANDO OS DADOS*
- `housing_median_age`: idade mediana das casas no grupo de blocos
- `total_rooms`: número cômodos no grupo de blocos - *MUITO ASSIMÉTRICO* Os Quartiz indicam números muito altos.
- `total_bedrooms`: número de quartos no grupo de blocos
- `population`: população do grupo de blocos
- `households`: domicílios no grupo de blocos
- `latitude`: latitude do grupo de blocos
- `longitude`: longitude do grupo de blocos
- `ocean_proximity`: proximidade do oceano - *COLUNA CATEGÓRICA* *SEMPRE QUE TIVER COLUNA CATEGÓRICA REALIZAR UMA ANÁLISE ESPECÍFICA PARA ELAS* 
  - `NEAR BAY`: perto da baía
  - `<1H OCEAN`: a menos de uma hora do oceano
  - `INLAND`: no interior
  - `NEAR OCEAN`: perto do oceano
  - `ISLAND`: ilha *EM ESPECÍFICO NESSA COLUNA, TEMOS APENAS 5 REGISTROS. POSSIVELMENTE TEREMOS QUE TOMAR ALGUMA DECISÃO*
  -  Sempre que tiver uma coluna categórica, realizar uma análise específica para elas verificando a contagem de valores. Essa coluna está bem desbalanceada pela questão de ter categorias com contagens muito   diferentes.
- `median_house_value`: valor mediano das casas no grupo de blocos (em dólares) *POSSÍLMENTE TAMBÉM TEVE UM CORTE MANUAL*

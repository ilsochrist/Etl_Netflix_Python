https://github.com/ilsochrist/netflix-dataset

### Para ativar o ambiente
# python -m venv venv
# venv/scripts/activate

# raw - dado bruto, antes de qualquer processo de polimento e processamento. Inicio de um processo
# ready - é quando o dado passou pelo seu processo de refinamento. Final de um processo. Não necessariamente que o dado não vai passar por outros processos de refinamento.

# Um único script main.py
# Mais de um script criar pasata scripts

## pacotes utilizados

## pip install pandas
## pip install openpyxl
## pip install Xlswriter

# Tratamento regras
# Prezar pela confiabilidade e reastrabilidade dos dados.

# ETL
# Extract, algum sistema depositar de algum servidor, ex: file server, que fica salvo na nuvem os arquivos chegando diariamente. Dados extraídos de outro lugar.
# Transform, tratamento e transformações.
# Load, carregar. Dar um destino. Pode ser carregado em um banco de dados, pode ser carregado em um novo arquivo csv, pode ser mandado para outro file server(driver na nuvem).

# glob serve para manipular diretórios e nomes de arquivos em massa.
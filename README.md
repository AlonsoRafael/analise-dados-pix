# Tema 8 – “Finanças Pessoais e Pix”

## Integrantes do Grupo
* Arthur
* Augusto de Faria Pereira
* Patrícia Fernandes Dornelas
* Rafael Alonso Marques
* Rodrigo Martins

# Etapa 1

## Como reproduzir esta etapa

### Vídeo: [Acessar vídeo ](https://drive.google.com/file/d/1mcrr-MDuMVSRlBoQkueJ6xNmZt1gc_kt/view?usp=sharing)

### Estrutura da Etapa 1
* `pipeline_pre_processamento.ipynb`: Notebook Jupyter contendo todas as etapas de coleta, limpeza, tratamento de atributos e padronização.
* `comprovantes_pix_10000_anomalias.csv`: Base de dados original utilizada no projeto.
  
Para executar o pipeline e reproduzir os nossos resultados, siga os passos abaixo:

1. **Download dos Dados:** Clone este repositório ou baixe o arquivo `comprovantes_pix_10000_anomalias.csv` diretamente desta página.
2. **Ambiente de Execução:** Recomendamos a utilização do Google Colab para evitar problemas de dependências.
3. **Upload dos Dados:** Abra o arquivo `.ipynb` no Colab. Antes de executar as células, faça o upload do arquivo `.csv` no painel de arquivos lateral do Colab (ícone de pasta).
4. **Execução:** Execute as células do notebook sequencialmente. O código está estruturado nas seguintes etapas:
   * Carregamento, inspeção e limpeza de datas inválidas.
   * Criação de novas variáveis temporais (Feature Engineering).
   * Remoção de outliers (método IQR na coluna de Valor).
   * Transformação de atributos categóricos (LabelEncoder).
   * Padronização e Normalização (StandardScaler e MinMaxScaler).

## Tecnologias Utilizadas
* Python 3
* Pandas & NumPy (Manipulação de dados)
* Scikit-Learn (Pré-processamento)

# Etapa 2



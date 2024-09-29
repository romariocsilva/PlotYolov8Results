# PlotYolov8Results

Código utilizado para plotagem dos gráficos de resultados para o algoritmo yolov8. 

Para plotar o gráfico, é necessário realizar o pré-processamento do arquivo results.csv gerado na saída de treinamento da rede.

## Pré-processamento

Converter o arquivo .csv para .xlsx, renomear as colunas para remover espaços ou adequar o nome das métricas.

## Plot

Para plotagem foram utilizadas as bibliotecas python Pandas e Matplotlib.

pip install -r requirements.txt

Um If foi inserido na parte inicial do código para verificar se as colunas com os nomes informados de fato existem. Caso contrário, os resultados não serão gerados e o usuário será informado sobre a inexistência das colunas.

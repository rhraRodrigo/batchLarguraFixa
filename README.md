# batchLarguraFixa
Leitura de arquivo com largura fixa em Spring Batch

#Informações para que o projeto consiga ser rodado:

1. Configurar sua conexão MySQL no arquivo application.properties

2. Configurar o caminho do arquivo de teste no arquivo "LeituraArquivoLarguraFixaReaderConfig", método leituraArquivoLarguraFixaReader.
  2.1 Definir o parâmetro do job 'arquivoClientes' em Run > Run Configurations > Spring boot application >  Arguments > Program Arguments:
    
    arquivoClientes=file:files/clientes.txt

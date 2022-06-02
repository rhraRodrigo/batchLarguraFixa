# batchLarguraFixa
Leitura de arquivo com largura fixa em Spring Batch

- Pt-BR

Informações para que o projeto consiga ser rodado:

1. Configurar sua conexão MySQL no arquivo application.properties

2. Configurar o caminho do arquivo de teste na classe "LeituraArquivoLarguraFixaReaderConfig", método "leituraArquivoLarguraFixaReader".
  2.1 Definir o parâmetro do job 'arquivoClientes' em Run > Run Configurations > Spring boot application >  Arguments > Program Arguments:
    
    arquivoClientes=file:files/clientes.txt

- En-US

Instructions to compile your project:

1. Configure your MySQL connection properties in application.properties

2. Configure location test file in class "LeituraArquivoLarguraFixaReaderConfig", method "leituraArquivoLarguraFixaReader".
  2.1 Define job parameter 'arquivoClientes' on Run > Run Configurations > Spring boot application > Arguments > Program Arguments:
  
    arquivoClientes=file:files/clientes.txt

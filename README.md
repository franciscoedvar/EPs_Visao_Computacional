# EPs da disciplina de Visão e Processamento de Imagens
## (MAC5768/MAC0417 -- 2020)

|Nomes:                        | N° USP:|
|------------------------------|--------|
|Alana Ilen Cermak             | 10737967|
|Francisco Edvar da Cunha Filho | 10656115|
|Marcos Markevich              | 11373435|


<p>Link para pasta no drive: https://drive.google.com/drive/folders/1Qc0gAhNhfqMOcWeW5aDH7WcEgftJjq12?usp=sharing<br>
<p>Link para o github do grupo: https://github.com/franciscoedvar/EPs_Visao_Computacional<br>

<p>O trabalho que segue é uma base de dados com 888 imagens, realizado como EP1 da matéria MAC0417/5768 - Visão e Processamento de Imagens, ministrada pelo professor Roberto Marcondes Cesar Junior, IME-USP. As imagens correspondem a 10 classes diferentes de objetos cotidianos. O programa faz um apêndice das fotos e gera uma tabela mnist aleatória com a nossa base de dados.<br>
    
   O trabalho que segue é uma composição de base de dados de 4440 imagens, realizado como EP2.1 da matéria MAC0417/5768 - Visão e Processamento de Imagens, ministrada pelo professor Roberto Marcondes Cesar Junior, IME-USP. As imagens correspondem a 5 versões de 10 classes diferentes de objetos cotidianos, sendo elas: níveis de cinza, soma de fundo com gradiente de níveis de cinza, filtro logaritimico, filtro exponencial, filtro da média. O programa faz um apêndice das fotos e gera uma tabela mnist aleatória por versão, com a nossa base de dados.
   Na primeira parte desse EP2 fizemos funções de data augmentation, criando 4440 imagens novas. Nessa parte vamos criar mais 4440 fotos, normalizando por equalização as fotos obtidas por data augmentation. Além disso, vamos fazer algumas funções de análise para aplica-las sobre as novas imagens criadas. São essas o protótipo médio, o histograma médio e a variança média de cada classe dentro de cada dataset.

# Requeriments
Instalação da biblioteca Google Drive Downloader:

    pip install googledrivedownloader
     
Fonte: https://github.com/ndrplz/google-drive-downloader
    

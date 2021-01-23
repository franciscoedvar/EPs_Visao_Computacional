# EPs da disciplina de Visão e Processamento de Imagens
## (MAC5768/MAC0417 -- 2020)

|Nomes:                        | N° USP:|
|------------------------------|--------|
|Alana Ilen Cermak             | 10737967|
|Francisco Edvar da Cunha Filho | 10656115|
|Marcos Markevich              | 11373435|


<p>Link para pasta no drive: https://drive.google.com/drive/folders/1Qc0gAhNhfqMOcWeW5aDH7WcEgftJjq12?usp=sharing<br>
<p>Link para o github do grupo: https://github.com/franciscoedvar/EPs_Visao_Computacional<br>

<p>A primeira parte do trabalho que segue é uma base de dados com 888 imagens, realizado como EP1, da matéria MAC0417/5768 - Visão e Processamento de Imagens, ministrada pelo professor Roberto Marcondes Cesar Junior, IME-USP. As imagens correspondem a 10 classes diferentes de objetos cotidianos. O programa faz um apêndice das fotos e gera uma tabela mnist aleatória com a nossa base de dados.<br>
    
  <p>A segunda parte do trabalho é uma composição de base de dados com 4440 imagens, realizado como EP2, que se segmenta em duas partes: <br>
    
* EP2.1 - Criar um data augmentation a partir de 5 versões de imagens de 10 classes diferentes de objetos cotidianos, sendo elas: níveis de cinza, soma de fundo com gradiente de níveis de cinza, filtro logaritmo, filtro exponencial e filtro da média; 
    
* EP2.2 - Normalizar por equalização as fotos obtidas no data augmentation e aplicar algumas funções de análise em cada classe do dataset: protótipo médio, histograma médio e variãncia média.
    
<p> O EP3, parte final do trabalho, foi separado em duas partes: <br>
    
* EP3.1 - Construir um conjunto de imagens segmentadas de forma binária manualmente, após isso, com um algoritmo de nossa escolha, realizamos a segmentação automática das imagens restantes. O trabalho disso pode ser encontrado no primeiro notebook do EP3. O algoritmo escolhido foi uma rede inteiramente convolucional chamada U-Net. O artigo de origem encontra-se no final do notebook; 
    
* EP3.2 - A segunda parte tinha como objetivo a classificação dos objetos de interesse. Essa se encontra no segundo notebook desta seção do trabalho, onde além disso há também os pipelines para as duas partes, envolvendo o blob e feretbox. Finalmente, encontra-se um relatório de perfomance, nesse mesmo notebook, com relação às duas partes finais do projeto.
    
    
# Requeriments
Instalação da biblioteca Google Drive Downloader:

    pip install googledrivedownloader
     
Fonte: https://github.com/ndrplz/google-drive-downloader

# Requeriments EP03

No arquivo 3.1.requeriments.txt encontra-se as versões dos pacotes usados no primeiro notebook desse EP03.

    pip install /path/para/3.1.requeriments.txt


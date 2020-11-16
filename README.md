# Departamento Médico

-   **IA/ML/DL tem revolucionado a área da medicina e saúde:**
    -   Imagens médicas
    -   Novos medicamentos
    -   Pesquisas relacionadas ao genoma
-   **Deep learning tem provado ser superior na detecção e  classificação de doenças usando imagens médicas.**
-   **Câncer de pele pode ser detectado com maior precisão por  modelos de Deep Learning do que por dermatologistas  experientes (2018).**
    -   Dermatologistas = 86.6%
    -   Deep learning = 95%
Referência: "Computer learns to detect skin cancer  more accurately than doctors". The Guardian. 29 May  2018
-   **Nesse estudo de caso, vamos assumir que somos consultores de  Deep Learning.**
-   **Fomos contratados por um hospital para automatizar o processo  de detectar e classificar doenças pulmonares, reduzindo o custo e  tempo da detecção.**
-   **Os profissionais da saúde coletaram várias imagens de raio-x, 133  imagens que pertencem a 4 classes:**
    -   Healthy (saudável)
    -   Covid-19
    -   Bacterial Pneumonia
    -   Viral Pneumonia
**REDES NEURAIS CONVOLUCIONAIS**
-   **As primeiras camadas convolucionais são utilizadas para extrair características  gerais das imagens (bordas, linhas).**
-   **As últimas camadas são utilizadas para classificação.**
-   **As “bordas/linhas” são utilizadas nas camadas seguintes para formar  características mais complexas (olhos, boca, nariz).**
![redes Neurais](https://github.com/callacius/Data_Science_Medico/blob/main/images/01.png?raw=true)
![redes Neurais](https://github.com/callacius/Data_Science_Medico/blob/main/images/02.png?raw=true)
-   **Existem diversas arquiteturas de redes neurais convolucionais  treinadas e disponíveis para uso:**
    -   LeNet-5 (1998): 7 níveis de convolução aplicada na classificação de dígitos manuscritos.
    -   AlexNet (2012): apresentou melhorias, reduzindo o erro de 26%  para 15.3%.
    -   ZFNEt (2013): erro de 14.8%.
    -   Googlenet/Inception (2014): erro de 6.67% (similar a precisão humana).
    -   VGGNet (2014).
    -   ResNet (2015): Residual Neural Network com a inclusão do  conceito de “skip connection” que permitiu o treinamento de  152 camadas. Erro de 3.57% (superior aos humanos).
**RESNET (RESIDUAL NETWORK)**
-   **Problema do gradiente desaparecendo (vanish gradient  problem)**
-   **Conceito de “skip connection” (usada na arquitetura YOLO)**
-   **A base de dados ImageNet contém 11 milhões de imagens e 11.000 categoriais**
-   **Essa base de dados é utilizada para treinar a arquitetura ResNet**
![redes Neurais](https://github.com/callacius/Data_Science_Medico/blob/main/images/03.png?raw=true)
**TRANSFERÊNCIA DE APRENDIZAGEM**
-   **É uma técnica na qual uma rede neural foi treinada para realizar uma determinada tarefa e é reusada como ponto de partida para uma tarefa similar.**
-   **Muito útil porque reduz drasticamente o tempo de treinamento.**
![redes Neurais](https://github.com/callacius/Data_Science_Medico/blob/main/images/04.png?raw=true)
![redes Neurais](https://github.com/callacius/Data_Science_Medico/blob/main/images/05.png?raw=true)

Fonte: **https://www.udemy.com/course/ciencia-de-dados-para-empresas-e-negocios**

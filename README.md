# [CarVision](https://image-classify.vercel.app/predictions)

## Equipe 👷‍♂️

- Bruno Henrique Miranda de Oliveira (25459333)
- Raul Semicek Coelho (25891651)
- Bruno Vinicius Martins Faria (25806939)
- Nicolas Fernandes (26387085)

## Tema 🚗

- Sistema de classificação de carros

## Objetivos 🎯
- Criar um sistema que classifique marcas de carros

## Banco de dados 📝
- <b>URL</b>: [stanford-cars-dataset](https://www.kaggle.com/datasets/jessicali9530/stanford-cars-dataset)
- <b>Número de classes/marcas</b>: 196
- <b>Número de imagens</b>: 16.185

## Revisão da literatura 📖

### Artigo 1
[Reconhecimento de silhueta de automóveis para carros autônomos utilizando aprendizado de máquina](https://wiki.sj.ifsc.edu.br/images/e/e8/TCC1_Tamara_Arrigoni.pdf)

### Objetivos 
<p>Os objetivos do artigo foi desenvolver um sistema para investigar e aplicar técnicas e algoritmos de aprendizado de máquina, analisar o desempenho das técnicas de acordo com um conjunto de dados pré-definido e definir, a partir dos resultados de testes, as técnicas que mais se adéquam ao objetivo geral do projeto.<p/>

### Banco de dados utilizado
<p>Para o desenvolvimento deste trabalho uma base de dados disponível no repositório de aprendizado de máquina da Universidade da Califórnia, Irvine, foi utilizada<p/>

### Modelos utilizados
Foram utilizados alguns modelos para verificar a acurácia do sistema:
- Modelo baseado em Redes Neurais Artificiais
- Modelo baseado em Máquina de Vetores de Suporte
- Modelos baseados em Árvores de Decisão (C5.0/CART)
- Modelo baseado em Random Forest
- Modelo baseado em K-Nearest Neighbors (k-NN)
- Modelo baseado em Naive Bayes
- Modelo baseado em K-means

### Resultados obtidos
A acurácia de cada modelo foi dada por:
- Redes Neurais Artificiais: 83,33%
- Máquina de Vetores de Suporte: 79,17%
- Árvores de Decisão(C5.0): 72,62%
- Árvores de Decisão(CART): 69,05%
- Random Forest: 71,43%
- K-Nearest Neighbors(k-NN): 74,40%
- Naive Bayes: 62,50%
- K-means: 41,07%

  <hr>

### Artigo 2
[Técnicas de PDI e Inteligência Artificial Aplicadas ao Reconhecimento de placas de Carro nos Padrões Brasileiros](https://www.researchgate.net/profile/Edson-Cavalcanti-Neto/publication/262956949_TECNICAS_DE_PDI_E_INTELIGENCIA_ARTIFICIAL_APLICADAS_AO_RECONHECIMENTO_DE_PLACAS_DE_CARRO_NOS_PADROES_BRASILEIROS/links/0c96053970df6e1d49000000/TECNICAS-DE-PDI-E-INTELIGENCIA-ARTIFICIAL-APLICADAS-AO-RECONHECIMENTO-DE-PLACAS-DE-CARRO-NOS-PADROES-BRASILEIROS.pdf)

### Objetivos 
Este trabalho tem como objetivo o desenvolvimento de técnicas de Processamento Digital de Imagem e Inteigência Computacional com o foco em sistema de detecção e reconhecimento de placas de veículos nos padrões brasileiros.

### Banco de dados utilizado
Não informado

### Modelos utilizados
- Filtros operadores gradiente (Roberts, Prewwit, Sobel)
- Filtro de Canny
- Transformada de Hough
- RNA MLP (Rede Neural Artificial / Multi Layer Perceptron)

### Resultados obtidos
<p>No teste do sistema foi utilizado 700 vídeos e a partir destes foram extraídas 12000 imagens.</p>
<p>A etapa do PDI desta forma obteve uma taxa de acerto de 97.02%.</p>
<p>A etapa de reconhecimento uma taxa de acerto de 97.7% em relação aos números das placas e 96.4% em relação as letras.</p>
<p>No processo inteiro obteve-se <b>97.3%</b> de acerto na extração e reconhecimento dos números e <b>96.16%</b> nos caracteres</p>

<hr>

### Artigo 3
[TÉCNICAS DE CLASSIFICAÇÃO DE IMAGENS PARA ANÁLISE DE COBERTURA VEGETAL](https://www.scielo.br/j/eagri/a/NfyXzM9DZsx5g3gnCQgCSsg/?lang=pt)

### Objetivos 
O artigo defende e explica as técnicas de sensoriamento remoto para subsidiar decisões na área agrosilvopastoral, com ênfase na compreensão dos processos envolvidos e na comunicação dos resultados de forma acessível.
### Banco de dados utilizado
Imagens retiradas com sensores e satélites
### Modelos utilizados
Modelo de classificação supervisionada;
Modelo de classificação não-supervisionada;
Modelo de classificação híbrida;

### Resultados obtidos
Melhora na análise de ocupação do solo
<hr>

### Artigo 4

CLASSIFICAÇÃO DE IMAGENS DERMATOSCÓPICAS COM MACHINE LEARNING (https://bdtd.ucb.br:8443/jspui/bitstream/tede/2802/2/JulioCezarDissertacao2020.pdf)

### Objetivos 
O artigo tem como objetivo detalhar o desenvolvimento de um aplicativo utilizando machine learning para auxiliar no diagnóstico precoce de melanoma. Para alcançar os objetyivos do trabalho deve ser considerado os seguintes objetivos.

1. Realizar uma revisão de literatura sobre o emprego de machine learning na identificação de melanoma utilizando imagens dermatoscópicas;
2. Identificar bancos de imagens dermatoscópicas para treinar e validar o modelo de machine learning;
3. Desenvolver um modelo de machine learning para classificar imagens dermatoscópicas em duas categorias: Melanoma e Não Melanoma;
4. Desenvolver uma aplicação para viabilizar o uso do modelo;
5. ProporumprotocolodeutilizaçãodoclassificadorpelosDermatologistas.

### Banco de dados utilizado

Identificar bancos de imagens dermatoscópicas para treinar e validar o modelo de machine learning;

### Modelos utilizados

Modelo de machine learning

### Resultados obtidos

Foi possível obter um modelo de machine learning capaz de classificar imagens dermatoscópicas para detecção de melanoma. O modelo obteve a precisão de 94% no processo de treinamento e validação.

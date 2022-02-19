<h1 align="center">Matriz esparsa</h1>


## Breve descrição 
<p align="center">A ideia principal do projeto é a implementação da estrutura de dados matriz esparsa utilizando-se de listas encadeadasc circulares</p>

## Requisitos da aplicação 
Para executar a aplicação, basta ter um editor de texto ou uma IDE que execute o código C++. Dentro da pasta principal execute o arquivo "main.cpp" junto com "Matrix.h" e "Matrix.cpp" 


## O que é a estrutura de dados matriz esparsa ? 
Na programação uma das maiores preocupações é o uso de memória pois, após utilizá-la, é preciso desalocar visto que todo espaço de memória é finito. Na programação existe uma estrutura chamada matriz esparsa que é uma matriz na qual a grande maioria de seus elementos possui um valor padrão (por exemplo zero) ou são nulos ou faltantes. Com isso, as matrizes esparsas, para que não haja utilização desnecessária de memória, irá alocar apenas valores que forem diferentes deste valor padrão ou que tenham sido colocados pelo usuário. 

## Sobre a aplicação
Como dito anteriormente, é feita a implementação de um arranjo onde o usuario tem a capacidade de armazenar valores em uma estrutura matricial. De acordo com a inserção dos valores, o algoritmo aloca esses dados utilizando-se das listas encandeadas circulares. As listas organizam esses valores relacionando suas linhas e colunas conforme o usuário requisita e fazem o endereçamento correto das informações. Para isso, é inicializado, no começo a aplicação, duas listas iniciais no sentido vertical e horizontal onde parte a relação de linha e coluna como também as referências para os dados que serão armazenados. 



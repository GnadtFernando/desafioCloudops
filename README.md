# DesafioCloudops


//Caminho utilizado onde estavam os arquivos do index e Dockerfile

docker build -t desafio C:\Users\gnadt\Downloads\desafio

//Executa pagina index.html
 
 docker run -p 80:80 desafio
 

Foi utilizado porta 80 pois 8080 estava em uso por outra aplicação sendo assim necessária seguinte link http://localhost:80/


Nesse desafio foi utilizado o NGINX pois mesmo consegue lidar com conexões simultaneas e utiliza o minimo de memoria possivel sendo assim um dos servidores web mais eficientes no mercado.

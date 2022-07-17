# API-Livraria

Neste projeto Criei uma API para cadastro de Livros utilizando a linguagem Python com o Django Rest Framework:

![image](https://user-images.githubusercontent.com/104043012/179402521-c689891f-7f09-4402-a3dc-8226e9b0a1ec.png)

Nesta API o cliente cadastra livros com o título, nome do autor, estado, número de páginas, data  e publicadora.
Os dados cadastrados são armazenados no Banco de dados, nesse momento estou usando o SQlite3 que já vem por padrão no
Django Rest Framework:

![image](https://user-images.githubusercontent.com/104043012/179402797-96ccd942-8a72-430b-aea9-9b977696b1cc.png)


Por padrao o Django Rest Framework já cria todos os méthodos HTTP, se eu quiser usar o DELETE por exempro, para
escluir qualquer livro, é só colocar o ID desse livro e ficará disponível a opção DELETE:

![image](https://user-images.githubusercontent.com/104043012/179402820-b8732c3c-db00-4e0b-85df-11463bdbf9ce.png)

Esse projeto foi um tanto quanto simples, mas me ajudou a criar uma base em criação de API's e a entender 
alguns conceitos importantes no desenvolvimento Back-End.

# User Register
Este Projeto é um protótipo do curso de C# do torne se um programador, Ele ilustra uma aplicação 3 camadas, com criação de usuários e salvando os Dddos no banco SQL ou .CSV(planilha Excel)



## Começando...

- [.NET Framework 4.8: Necessário para executar o projeto .NET](https://dotnet.microsoft.com/download/dotnet-framework/net48)
- [Servidor Apache: Necessário para salvar os dados no banco de dados MySql](https://www.apachefriends.org/pt_br/download.html)
- [Visual Studio: Para desenvolvimento do projeto](https://visualstudio.microsoft.com/pt-br/downloads/)





## Desenvolvimento

Para iniciar o desenvolvimento, é necessário clonar o projeto do GitHub num diretório de sua preferência:


```shell
cd "diretorio de sua preferencia"
git clone https://github.com/venilson1/-app-3-layers
```


Abra o XAMPP e inicie o servidor apache e o Mysql que estará no http://localhost/phpmyadmin/index.php
Crie um novo banco de dados com o nome 3camadas e escreva a seguinte QUERIE para criaar o modelo do banco dedados 



```shell
CREATE TABLE usuarios (
    ID INT(11) NOT NULL AUTO_INCREMENT PRIMARY KEY,
    nome varchar(255) NOT NULL,
    telefone varchar(11) NOT NULL,
    cpf varchar(15) UNIQUE
);
```


![users](https://user-images.githubusercontent.com/57969262/105092724-61ea7080-5a80-11eb-92cc-efed9a88caeb.PNG)

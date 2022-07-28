# DotNetApiWithDocker
Exemplo de uma API .Net Utilizando Docker

Neste exemplo foi utilizado o template do .NET 6 com Minimal API para exemplificar como utilizar o docker numa API .NET !

Comandos utilizados para criar a imagem:

docker build . -t dotnetapi1

Comando utilizado para criar o conteiner e executá-lo:

docker run -p 8081:5000 -e ASPNETCORE_ENVIRONMENT=Development dotnetapi1 --name dotnetapi2

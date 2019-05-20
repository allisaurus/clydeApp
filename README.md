# Clyde App

A simple .NET core application that displays picutres of a specific pup.


## Run this app locally

From within the project root, run:
```console
dotnet run
```

## Build and run as a container

From within the project root, run:

```console
docker build -t clydeapp .

docker run -d -p 8080:80 --name clyde clydeapp
```

## Usage

```docker
docker run --name [ContainerName] -p 8080:80 [imageName:Tag]  => Container oluşturur.
docker run --name [ContainerName] -p 8080:80 -p 8081:443 => Https için Container oluşturur.
docker container rm [ContainerName] => Container'ı kaldırır.
docker container ls => Bütün Containerları gösterir.
docker ps => Aktif çalışan Containerları gösterir.
docker image ls => Bütün Imageleri gösterir.
docker rmi [ImageId] => Image'i kaldırır.
```

## Contributing
dotnet dev-certs https -ep $env:USERPROFILE\.aspnet\https\WeatherAPI.pfx -p pas55w0rd! => local de sertifika oluşturur.
NOT: Sertifikayı oluştururken powershell'i yönetici olarak çalıştırıp açın.

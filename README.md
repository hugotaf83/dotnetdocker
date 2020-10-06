docker build -t dotnet-redis .
docker run -it --rm -p 5000:80 --name aspnetcore_sample dotnet-redis
docker build -t dotnetmvc .

docker run -it --rm -p 5000:80 --name aspnetcore_mvc_sample dotnetmvc
# netcore API

## Docker support
This project can be hosted in an aspnetcore docker container.
Just type `docker build . -t netcoreapi` after the application was built using `dotnet publish -o ./dist`.
Run the container using `docker run -p 8082:80 -d netcoreapi`.
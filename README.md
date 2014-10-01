# docker-ratticdb

Something I hacked together to experiment with RatticDB. This is purely for expiermental purposes and **NOT** fit for production use (yet) as there's no SSL and it's configured to use an SQLite database.

To run, clone this project and build the docker image. Then do:

docker run -p 80:80 your-ratticdb-image-name

Then browse to http://localhost.

The default credentials are admin / rattic.

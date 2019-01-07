****** Docker ******

# docker build -t nodecosmos:linux .

# docker run -p 5000:3000 -d -e COSMOSDB_CONNSTR={Conn string} -e COSMODDB_USER={username} -e COSMOSDB_PASSWORD={password} -e COSMOSDB_DATABASE_NAME={database name} nodecosmos:linux
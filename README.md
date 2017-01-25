# dhDatabase
Dream Home Application, creates the MongoDB database and collections.


##Database URL set via 'mongourl' environment variable.
##Example syntax:
###Set these 4 environment variables:

####mongourl=mongoDB://cpoAdmin:enitlavo908#@158.85.248.111:8888/admin
####MONGODB_DATABASE=dhDatabaseName
####MONGODB_USER=cpoUser
####MONGODB_PASSWORD=enitlavo908# 

###The mongourl env MUST be set to connect to the 'admin' DB so it has privilege to create the desired DB

###The three 'MONGODB_...' envs specify the credentials for creating the desired dream home database.

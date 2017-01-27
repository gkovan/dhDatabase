# dhDatabase
Dream Home Application, creates the MongoDB database and collections.


##Database URL set via 'mongourl' environment variable.
##Example syntax:
###Set these 4 environment variables:

####mongourl=mongoDB://cpoAdmin:enitlavo908#@158.85.248.111:8888/admin
####mongoDatabase=dhDatabaseName
####mongoUser=cpoUser
####mongoPassword=enitlavo908# 

###The mongourl env MUST be set to connect to the 'admin' DB so it has privilege to create the desired DB

###The other three 'mongo...' envs specify the credentials for creating the desired dream home database.

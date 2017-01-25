# dhDatabase
Dream Home Application, creates the MongoDB collections.


##Database URL set via 'mongourl' environment variable.
##Example syntax:
###set these environment variables

####mongourl=mongoDB://cpoAdmin:enitlavo908#@158.85.248.111:8888/admin
####MONGODB_DATABASE=dhOpenShift
####MONGODB_USER=cpoUser
####MONGODB_PASSWORD=enitlavo908# 

##The mongourl env MUST be set to connect to the 'admin' DB so it has privilege
to create the desired DB

##The MONGODB_... envs specify the details for creating the actual dream home database.

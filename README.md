# MongoNetworkError-
MongoNetworkError: connect ECONNREFUSED 127.0.0.1:27017

error (Connecting to:		mongodb://127.0.0.1:27017/?directConnection=true&serverSelectionTimeoutMS=2000&appName=mongosh+1.8.0
MongoNetworkError: connect ECONNREFUSED 127.0.0.1:27017)

solve these error only 2  commands i will show u
--------------------------------------------------------------------------------
sudo rm -rf /tmp/mongodb-27017.sock
sudo service mongod start
-----------------------------------------------------------------------------------------------------

wuiiii that solve

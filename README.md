# mongoDb
Learning MongoDb
# To install mongo in C:"New folder named mongodb"
C:\mongodb\bin>mongod --directoryperdb --dbpath C:\mongodb\data\db --logpath C:\mongodb\log\mongo.log --logappend --install
# Mongo Shell //type mongo from within the bin directory
C:\mongodb\bin>mongo
# To show databases available
C:\mongodb\bin>show dbs
# To Create Database // here testdb is the database name
C:\mongodb\bin>use testdb
# To check the current database you are in 
C:\mongodb\bin>db
# To create Tables // in mongo tables are called collections; //userInfo is the name of my table.
C:\mongodb\bin>db.createCollection('userInfo');
# To show Tables available
C:\mongodb\bin>show collections

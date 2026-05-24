# Mongo-Db-Compass

1.show dbs || showdatabases
2.use "Database Name"
3.show collections
4.db.createCollection("Collection Name")
5.db.'old name'.renameCollection('new name')
6.db.dropDatabase()
7.db.Collection Name.insertOne({})
8.db.Collection Name.insertMany({})
9.db.Collection Name.find()
10.db.Collection Name.findOne({_id:ObjectId("'id'")})
11.db.Collection Name.find({category: "News"})
12.db.Collection Name.deleteOne({_id:ObjectId("'id'")})
13.db.Collection Name.updateOne({_id:ObjectId("'id'"},{$set:{}})
14.db.Collection Name.updateMany({_id:ObjectId("'id'"},{$set:{}})

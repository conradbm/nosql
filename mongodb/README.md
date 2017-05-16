<h2> MongoDB </h2>
<h3> Simple examples</h3>
<code>
>> mongo
>> show dbs
>> use UCI-Database
>> show collections
>> db.income.find({“age”:{“$gt”:35}}
>> db.income.find({“age”:{“$lt”:20}, “education”:”Some-college”})
</code>

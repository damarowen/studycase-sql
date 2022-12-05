### *** Tolong tuliskan SQL query untuk mendapatkan data berisi: ID, UserName, ParentUserName 
#### Kolom ParentUserName adalah UserName berdasarkan value Parent
___
#### Answer :
First I create table name “user” from database called “altea”, then I using left join method to solve this problem, if we using inner or right join , “budi” data not shown because there are “null” value in “Budi” data, the "null" values happens because parent value budi is zero .

```
SELECT a.Id, a.UserName, b.UserName AS ParentUserName
FROM altea.`user` AS a 
LEFT JOIN altea.`user` AS b
ON b.Id = a.Parent
```

___
### *** Kira2 di Column mana diperlukan Index

___
#### Answer :
I think we don't need indexing that table, because the table just contain small amount of data, but If we want to create Index to speed up query, we can create index to “Id” Column with command

```
CREATE INDEX user_index ON user(id);
```
___

# Thank you.

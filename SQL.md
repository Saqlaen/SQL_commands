<ul>
	<li> CREATE DATABASE name; [will create a new database/ schema]</li>
	<li> DROP DATABASE name; [will delete a database] </li>
	<li> USE name [will go to that database so you can start working on it]</li>
	<li> CREATE TABLE name( 
		 column_name INT[-->type] 
	     ); [will create a table] </li>
	<li> ALTER TABLE name 
		 ADD column2 VARCHAR(255); [255->length] [alter is kinda like editing the table]</li>
	<li> DROP TABLE name; [will delete the table]</li>
	<li> NOT NULL [will always force you to add a value in that col]</li>
	<li> id INT NOT NULL AUTO_INCRERMENT [adding a unique id column if you have more than one tables with same name ]</li>
	<li> (,) [use comma to separate the columns] </li>
	<li> PRIMARY KEY (id) [tells sql that this the key that distinguishes our table from other tables] </li>
	<li> FOREIGN KEY (IdSameAsOtherTableId) REFERENCES OtherTableName(tableId) [will link this table to other table] </li>
	<li> INSERT INTO tableName ( columnName ) 
		 VALUES( 'name1'), ('name2'), ('name2');</li>
	<li> SELECT * FROM tablename [will seclect all colums from that table] </li>
	<li> SELECT * FROM tablename LIMIT 2; [will select only 2 rows] </li>
	<li> SELECT colName FROM tablename;[will select only the col] </li>
	<li> SELECT colname AS 'colName2' FROM tableName [will rename the colname] </li>
	<li> SELECT colname AS 'colName2', otherCol AS 'othercol2' FROM tableName;[will rename two colnames that u mentioned] </li>
	<li> SELECT * FROM tableName ORDER BY colname ASC/DESC; [will give you the list in mentioned ascending or descending order] </li>
	<li> INSET INTO tableName ( col1, col2, col3 )
		 VALUES ('col1data1', col2data1, 'col3data1'),
		        ('col1data2', col2data2, 'col3data2'),
				('col1data3', col2data3, 'col3data3')</li>
	<li> SELECT DISTINCT colName FROM tableName; [will give me a colname which has different row </li>
	<li> UPDATE tableName 
		 SET colName = data; [will update rows in the columns with the mentioned colName ] </li>
	<li> UPDATE tableName 
		 SET colName = data;
		 WHERE id = 1; [will only update the data of the mentioned row in that col]</li>
	<li> SELECT * FROM tableName WHERE colname < value; [will select the col in that table that have the data less that the mentioned value]</li>
	<li> SELECT * FROM tableName WHERE colname LIKE '%er% [will select the col which matches (er) </li>
	<li> SELECT * FROM tableName WHERE  colName LIKE '%er%' OR colName2 = 2; [will slect row which math with character (er) or colName = 2]</li>
	<li> similarly you can use AND </li>
	<li> SELECT * FROM tableName WHERE colName BETWEEN 2000 AND 2018 [will select row where the value is in between 2000 and 2018]</li>
	<li> SELECT * FROM tableName WHERE colName IS NULL [will select row where the data is null ]</li>
	<li> DELETE FROM tableName WHERE id = 5; [will delete the row which has the id = 5] </li>
	<li> SELECT * FROM tableName1 JOIN tableName2 ON tableName1.id = tableName2.id; [will show all the values where both the tables id matched]</li>
	<li> INNER JOIN is same as OUTER JOIN </li>
	<li> LEFT JOIN [will show results of all the col in leftside </li>
	<li> RIGHT JOIN [opposite to right] </li>
	<li> SELECT AVG(colName) FROM tableName; [will give you the average of all the data mentioned in that column] </li>
</ul>

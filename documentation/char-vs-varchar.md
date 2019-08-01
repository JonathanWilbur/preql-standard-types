# Char vs VarChar

From [this page](https://dev.mysql.com/doc/refman/5.6/en/innodb-row-format.html):

> An SQL NULL value reserves one or two bytes in the record directory. An SQL NULL value reserves zero bytes in the data part of the record if stored in a variable-length column. For a fixed-length column, the fixed length of the column is reserved in the data part of the record. Reserving fixed space for NULL values permits columns to be updated in place from NULL to non-NULL values without causing index page fragmentation.

Keep in mind, the above only applies to a specific storage engine used by MySQL.
# update the auto_increment for table `table_name`

alter table table_name auto_incrememt = 0;


# show the auto_incremnt value of a table

select auto_increment from information_schema.tables where table_schema = 'dbname' and table_name = 'table_name';

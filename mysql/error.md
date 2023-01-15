- 1064，则为未选定数据库（database）
  
  通常出现在对table中的数据进行insert，update中
  
  可以将原本的
  
  ```
  UPDATE student
  --->
  UPDATE first_test.student
  
  或者在SCHEMAS中双击，选定要操作的数据表
  ```

- 1062，则为主键重复
  
  通常出现table表中要设置为主键的数值存在重复的数值
  
  可以删除原本重复的部分

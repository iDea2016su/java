## JDBC：for the right syntax to use near '?where id=?' ##
- 在用PrepareStatement进行参数化设置的时候
- 最后执行更新操作
- preparedStatement.executeUpdate(queryString);
- 切记
- preparedStatement.executeUpdate();
- 中不要加sqlString！！！

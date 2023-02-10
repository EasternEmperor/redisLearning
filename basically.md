### 基本使用
1. redis安装好后，默认有16个数据库，**初始默认使用0号库**
2. 添加key-value: [set]
3. 查看当前redis所有的key: [keys *]
4. 获取key对应的值: [get key]
5. 切换redis数据库: [select index]
6. 查看当前数据库的key-value数量: [dbsize]
7. 清空**当前**数据库的key-value和**所有**数据库的key-value: [flushdb], [flushall]
8. 更多操作查看redis技术手册：redisdoc.com

### 支持的数据类型
1. **五大**数据类型：String, Hash, List, Set, zset(sorted set)
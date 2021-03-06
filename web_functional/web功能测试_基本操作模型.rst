web功能测试_基本操作模型
=====================================

单个查询操作
-----------------------
* 分别对单条件进行精确查询
* 输入长度的校验，输入允许的最长值进行查询，是否支持
* 两个查询条件是否是2选1，来回选择是否出现页面错误
* 输入字符
* 输入特殊字符
* 输入汉字
* 输入数字
* 条件中含有空格
* 输入超长字符
* 输入全角字符
* 输入单引号
* 输入单引号引起来的数据
* 输入双引号
* 输入双引号引起来的数据
* 查询结果按照什么顺序排序
* 查询结果是否根据字段显示排序功能
* 查询结果是否有分页，如果有，每页最多多少记录
* 查询结果是否匹配
* 查询结果是否与数据库一致
* 查询结果是精确查询还是模糊查询
* 输入框大小、文字大小是否合适
* 查询处理时间是否能接受
* 数据库存在大量数据时，查询处理时间是否能接受
* 多个用户同时查询时，输入相同或不同的条件查询后系统响应是否及时

级联查询操作
---------------------------
* 所有条件输入空查询
* 只输入一个关键条件查询
* 随机组合条件查询
* 输入所有关键条件查询
* 所有条件都输入查询
* 查询结果按什么顺序排序
* 查询结果是否根据字段显示
* 查询结果是否与数据库一致

新增操作
--------------------------
* 初始化数据正确性
* 进入功能后未修改任何数据项运行新增功能
* 清空功能中所有可删除的数据项后运行新增功能
* 录满功能中所有数据
* 服务器磁盘空间不足，不能新增
* 主键同名，唯一性验证
* 创建时间以服务器的时间为准
* 是否在任何情况下，都可以取消保存
* 如果存在重置功能，重置后是否正常保存
* 提交成功后有返回结果，成功失败页面或实时刷新列表
* 新增提交时间如果长，应出现进度显示表
* 新增的数据是否与数据库一致
* 系统是否有提供数据回显, 那么回显数据与新增数据是一致的
* 如果新增数据后有返回到列表, 则一般是新增的数据排在首页首行

修改操作
--------------------------
* 修改一条记录
* 是否支持同时修改多条记录
* 多用户同时修改同一记录
* 点击“取消”或“返回”是否给予提示
* 提交成功后有返回结果，成功失败页面或实时刷新列表
* 修改提交时间如果长，应出现进度显示
* 修改的数据是否与数据库一致

删除操作
--------------------------
* 删除一条记录
* 是否支持同时删除多条记录
* 一个用户修改，一个用户删除同样的记录
* 无选择记录时删除是否控制
* 提交成功后有返回结果，成功失败页面或实时刷新列表
* 如果节点没有被其它功能关联，可以删除；反之不行
* 级联删除是否成功

数据导入操作
-----------------
* 是否完成数据正常导入功能
* 导入文件的部分数据异常进行导入
* 导入文件的全部数据异常进行导入
* 导入文件的关键字段值在数据中不存在进行导入
* 导入文件的数据格式不符合进行导入
* 数据导入后列表中的显示是否正确
* 数据导入后在数据库中的显示是否正确



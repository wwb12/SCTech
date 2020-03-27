# SCTech
设备管理系统（改版）

2020-03-23至2020-03-27
1.整合了layui的上传组件
	a.实现了上传，尚未实现与数据库交互
2.整合了xmSelect下拉组件
	a.在“维修工单”的查询项“维修分类”、“报修地址”实现了下拉树型的单选
	b.在“维修人员”的“添加”、“修改”的“维修班组”实现了下拉树型的单选
	c.在“受理指派”的“维修人员”实现了下拉树的多选
	d.在“受理指派”的“维修班组”、“维修人员”实现了下拉数的联动
3.优化了“维修管理”模块
	a.针对“维修工单”进行“受理指派”、“维修”
	b.将“维修花费”改为“维修清单”；维修清单的"备品备件"待日后补完
	c.添加了“工单查询”功能
	d.添加了“工单查看”功能
3.优化了“设备管理”模块
	a.增加了“设备查询”的查询项
4.修复了部分Bug、进行了系统优化
5.将首页变为开发时间线

2020-03-16至2020-03-20
1.优化了“维修管理”模块
	a.添加了“维修工单”功能：添加、修改、删除
	b.针对“维修工单”进行“维修花费”、“维修评价”
3.优化了系统部分功能
	a.状态的启用、禁用对上下级的影响
	b.维修班组的组长只可以指定一个人
	c.维修人员在同一班组下不可重复选区
4.修改了系统的部分Bug
	d.批量删除功能失效

2020-03-03至03-13
1.基于设备管理系统Demo版修改了代码的底层结构
	a.更换项目包路径为SCTech
	b.将业务模块单独放置
2.优化了“设备管理”模块
	a.添加了“设备所在区域”功能:添加、修改、删除
	b.添加了“设备位号管理”功能:添加、修改、删除
3.添加了“维修管理”模块
	a.添加了“维修班组”功能:添加、修改、删除
	b.添加了“维修人员”功能:添加、修改、删除
	c.添加了“维修分类”功能:添加、修改、删除

2020-03-03前
1.完成了设备管理系统Demo版的开发


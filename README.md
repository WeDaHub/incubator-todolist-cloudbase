# 2021 TCBC 云开发技术竞赛#-代办清单-干饭团

作者：romeochen

## 作品： todo-list
这是一款管理代办清单的小程序，拥有如下功能：
- 新增代办事项
- 完成代办事项
- 删除代办事项
- 取消完成已完成的代办事项
使用了云开发里的云函数以及云数据库功能。云函数用来获取用户的 openid，云数据库存储数据。

## 部署使用指南
1. 首先需要开通云发开功能
2. 右键 cloudfunctions/login，选择【创建并部署】
3. 打开云开发控制台，在数据库中添加集合【todos】
4. 即可正常运行
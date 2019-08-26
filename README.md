# RedmineNotes
## 第一次修改，整体流程：
1. 创建远程仓库——已经完成
2. 将远程仓库代码pull到windows开发环境，并提交一次更改，验证正常流程是否走通
3. redmine所在服务器应用git clone --mirror  仓库地址命令，将远程仓库pull下来
	作为一个local副本与redmine集成
4. Windows开发环境再提交一次（第二次），验证redmine服务器的local代码库是否能够监测到第二次提交，观察结果再做下一步计划.
## 第二次提交，window开发环境
## 实验结果：开发环境提交完直接在redmine上查看，不能查看到最新提交
## 第三次提交，首先更改此文本格式，使其符合markdown语法格式
- Windows开发环境提交此次commit
- redmine所在服务器增加crontab 定时任务，定期从remote仓库 fetch更新local仓库内容来实现redmine能够查看最新在提交内容（伪实时）

## GitHub帮助中有[同步代码仓库方法](https://help.github.com/en/articles/duplicating-a-repository)

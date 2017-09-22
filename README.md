# ff14_bot_task
ff14自动任务

## ff14_bot_1_0:
-----------------------------------------
### 功能说明
1. 自动登录功能
2. 自动1小时自由任务
3. 自动18小时平原任务最后一项

### 优化及bug处理
1. 处理基址未找到弹出框bug
2. 处理雇员菜单信息与任务完成情况不一致情况


## ff14_bot_1_1:
-----------------------------------------
### 优化及bug处理
1. 处理同服务器多人选择时混乱的问题
2. 处理传唤铃旁边人多的问题，尝试18次，原来为10次

## ff14_bot_1_2:
-----------------------------------------
### 功能说明
1. 任务终止
2. 任务可以从中间启动

## ff14_bot_1_3:
-----------------------------------------
### 功能说明
1. 1小时循环任务
2. 任务时间记录且根据任务时间判断任务是否完成
3. 任务列表游标会跟随当前任务角色


### 优化及bug处理
1. 处理同账号为开启游戏，继续任务失败的情况

##ff14_bot_1_4:
-----------------------------------------
### 功能说明
1. 新增日志文件，需在exe目录下新建tasklogs目录
2. 任务列表根据不同状态变化颜色
3. 任务列表增加全部删除功能


### 优化及bug处理
无

##ff14_bot_1_5:
-----------------------------------------
### 功能说明
1. 1小时循环任务增加时间判断

### 优化及bug处理
无

##ff14_bot_1_6:
-----------------------------------------
### 功能说明
1. 任务列表当前任务跟随显示 

### 优化及bug处理
1. 修复1小时循环任务增加时间错误


## ff14_bot_1_6_1:
-----------------------------------------
### 功能说明
无

### 优化及bug处理
1. 修复1小时循环任务时间错误


## ff14_bot_1_7:
-----------------------------------------
### 功能说明
1. 连续2次同角色任务失败终止循环任务；
2. 增加对探险币的判断并延时2小时；
3. 增加对不在传唤铃旁边的判断并延时1小时；
4. 日志输出框采用彩色输出；
5. 日志时间格式更为友好；

### 优化及bug处理
1. 增加任务与任务之间间隔时间5秒，防止出现多开;
2. 每次都记录下次任务时间，防止卡在未执行任务的情况。 

## ff14_bot_1_7_1:
-----------------------------------------
### 功能说明


### 优化及bug处理
1. 修复数据库重复打开后关闭的问题。

## ff14_bot_1_7_2:
-----------------------------------------
### 功能说明


### 优化及bug处理
1. 修复状态1识别问题；
2. 修复由于包袱空间不足2引起的中断。


## ff14_bot_1_7_3:
-----------------------------------------
1. 适应ff14 2017.08.08升级

## ff14_bot_1_7_5:
-----------------------------------------
1. 使用线程处理多开


## ff14_bot_1_7_6:
-----------------------------------------
1. 18小时任务可识别雇员等级和装备品级， 并根据数据选最大任务执行；当装备品级不足时输出警告的日志，但不影响做任务。

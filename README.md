# HASS-Blueprints/Home Assistant 常用的蓝图

所收录的蓝图一部分来自论坛及github，并由我进行汉化，另一部分由我本人创建。由于HASS通过UI创建自动化的指引不是很清楚，而使用Yaml文件创建自动化流程对普通用户要求过高，所以“蓝图”功能的初衷就是降低HASS创建自动化的难度，为了更加方便汉语用户的使用蓝图，此处收录的蓝图中相关说明文字为汉语。

## 设置类-对HASS系统进行设置

- settingAutomatedDailySnapshot：根据指定时间每日创建快照  
- seetingAutomationState：当指定家庭成员到达指定区域后关闭指定的自动化  

## 通知类-向APP推送通知

- NotificationHASSUpdate：HASS有新版版本可以更新时推送通知  
- NotificationMotionPicture：检测到动作传感器前有物体移动时推送含有摄像头截图的通知  
- NotificationZoneLeave：家庭成员离开指定区域时推送通知  

## 告警类-对于特别重大的消息以告警的方式推送
***该类通知会在手机端产生告警提示，即使是手机处于静音状态依然会发出告警提示音***  

## 动作类-完成设备操作动作

- actionBackHomeOpenLight：天黑回家后自动打开灯  
- actionMotionLight：指定区域检测到有人活动时自动打开对应的灯，指定时间后自动关闭  

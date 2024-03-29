# Sun Yat-Sen University Course Register Tool

中山大学辅助选课工具

## 如何安装

1. 安装[TamperMonkey插件](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
2. 安装[中山大学选课辅助脚本](https://greasyfork.org/scripts/460366-sun-yat-sen-university-course-registering-tool/code/Sun%20Yat-Sen%20University%20Course%20Registering%20Tool.user.js)
3. 参考下文说明使用即可

## 使用说明

1. 进入可选课程预览页面，将想要辅助选课的课程收藏，注意不要超过一页能显示的量（10门）
2. 回到“选课”，刷新页面（很重要）
3. 进入你要抢的课程类型的列表并且选择显示收藏+隐藏已选
4. 点击课程右侧的“抢课”按钮添加到选课单
5. 点击“开始抢课”按钮开始
6. 成功后可以点击“停止抢课”结束或是直接关闭窗口

## 常见问题

### 1. 课程右侧没有抢课按钮？

检查课程是否已选，如果确实是未选课程，可能是代码BUG没有及时插入元素，可以点击一次“查询”按钮刷新列表，再看看出现了没有

### 2. 可以同时辅助抢选专选、公选吗？

不可以，目前代码限制只能同时辅助选择同一类型的课程，并且要求待选课程能够在一页查询结果中显示

### 3. 可以保证抢到吗？

不保证一定可以抢到课，如果想要短暂提高成功率，可以调整REFRESH_INTERVAL至较小的数值；同时，更根本地，成功的根本前提在于出现课程空余

> **WARNING: 较短的刷新延迟可能会影响教务系统的正常运行，请在合理范围内设置**

## 免责声明

本脚本仅用于学习交流使用，旨在提供一个教务系统DOM元素操作范例，具体功能仅为演示DOM元素操作撰写，**请勿用于其他用途，并在下载后12小时内删除**。**任何用于除上述用途以外的用途导致的一切后果由用户自行承担**。

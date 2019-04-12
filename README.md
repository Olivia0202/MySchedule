                                                     # Android 日历提醒软件
快要毕业答辩了，课题是做一款Android日历提醒软件，因为这个项目主要以逻辑结构重点，所以在界面和代码编写上参考了很多开源的项目，以实现功能为主。

GitHub项目地址:[https://github.com/Olivia0202/MySchedule](https://github.com/Olivia0202/MySchedule)

### 主界面
* 整体风格是参考Google日历
* 主界面可以根据不同的日期滑动选择查看概要日程信息
* 侧滑菜单可以分类按照某一周或某一天查看日程信息
* 日历和日程的参考GitHub上的开源项目[MyCalendarDemo](https://github.com/werbhelius/MyCalendarDemo)，然后修改了部分代码

<img src="/screenshots/s1.png" alt="screenshot" title="主界面" width="270" height="486" /> <img src="/screenshots/s3.png" alt="screenshot" title="侧滑菜单界面" width="270" height="486" />

### 分类查看(按周或天查看)
<img src="/screenshots/s4.png" alt="screenshot" title="某一天日程信息" width="270" height="486" /> <img src="/screenshots/s5.png" alt="screenshot" title="某一周日程信息" width="270" height="486" />

### 添加日程提醒和日程信息详情界面
* 这里界面完全参考Google日程添加日程界面
* 选择日程活动提醒时间、重复次数、是否震动、提醒铃声、显示颜色等
* 查看详情界面，同时可以删除和修改日程信息

<img src="/screenshots/s2.png" alt="screenshot" title="添加日程提醒" width="270" height="486" /> <img src="/screenshots/s6.png" alt="screenshot" title="日程信息详情界面" width="270" height="486" />

### 日程到点提醒
* 提醒只是调用系统弹窗，伴随震动和铃声
* 这里涉及Android6.0权限问题，代码中已有相应设置，但由于国内厂商对手机权限修改过多，如果存在不能提醒情况，
请手动在设置中打开相应权限

<img src="/screenshots/s7.jpg" alt="screenshot" title="日程到点提醒" width="270" height="486" />

### License
* 再次感谢开源项目[MyCalendarDemo](https://github.com/werbhelius/MyCalendarDemo)的帮助


====



      Copyright 2016 Werb

      Licensed under the Apache License, Version 2.0 (the "License");
      you may not use this file except in compliance with the License.
      You may obtain a copy of the License at

          http://www.apache.org/licenses/LICENSE-2.0

      Unless required by applicable law or agreed to in writing, software
      distributed under the License is distributed on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
      See the License for the specific language governing permissions and
      limitations under the License.



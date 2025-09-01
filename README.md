## Description
English fork of https://github.com/Trizzy33/taobaoTrackingNumberExport all credit goes to https://github.com/Trizzy33
## Usage
1. ~Disable same origin policy~
   ~- Windows: 使用这个 command来打开chrome，一般会安装在`C:\Program Files\Google\Chrome\Application`, 找到后右键open in terminal~
   ~`./chrome.exe --user-data-dir="C:/Chrome dev session" --disable-web-security`~
   ~- Linux https://stackoverflow.com/questions/3102819/disable-same-origin-policy-in-chrome~ (Not needed anymore in 0.1)
2. 油猴 -> 点击plugins里油猴的logo，打开dashboard，installed scripts左边有一个小加号 创建一个空的script，全部粘贴进去保存。
3. 设置chrome pop up: Allow pop up on buyertrade.taobao.com
4. 先添加订单，才能导出。每页大概是50个订单左右，超出需要手动翻页 

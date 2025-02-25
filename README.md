## Description
批量导出淘宝快递单号油猴脚本
因为转运要提供快递单号，但是太多了不想一个一个复制，就在这个油猴脚本[淘宝买家订单导出](https://greasyfork.org/en/scripts/414444-%E6%B7%98%E5%AE%9D%E4%B9%B0%E5%AE%B6%E8%AE%A2%E5%8D%95%E5%AF%BC%E5%87%BA)的基础上改了这个script 用的是笨方法直接打开新页面，本人不懂js这块，大佬可以提pr改好的方法
## Usage
1. Disable same origin policy
   - Windows: 使用这个 command来打开chrome，一般会安装在`C:\Program Files\Google\Chrome\Application`, 找到后右键open in terminal
     `./chrome.exe --user-data-dir="C:/Chrome dev session" --disable-web-security`
   - Linux https://stackoverflow.com/questions/3102819/disable-same-origin-policy-in-chrome
2. 油猴 -> 点击plugins里油猴的logo，打开dashboard，installed scripts左边有一个小加号 创建一个空的script，全部粘贴进去保存。
3. 设置chrome pop up: Allow pop up on buyertrade.taobao.com
4. 先添加订单，才能导出。每页大概是50个订单左右，超出需要手动翻页 

https://greasyfork.org/en/scripts/528003-taobao-orders-export-%E6%B7%98%E5%AE%9D%E8%AE%A2%E5%8D%95%E5%BF%AB%E9%80%92%E5%AF%BC%E5%87%BA

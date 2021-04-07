## 邀请码互助
  - [获取各类活动互助码脚本 jd_get_share_code.js](https://github.com/ww69mm/jc/blob/main/jd_get_share_code.js)
  - [邀请码使用规范](https://github.com/ww69mm/jc/blob/main/githubAction.md#%E4%BA%92%E5%8A%A9%E7%A0%81%E7%B1%BB%E7%8E%AF%E5%A2%83%E5%8F%98%E9%87%8F)(仅限云端)
## 食用方法

### 方法一：本地安装Node.js，下载本库脚本

  - 教程请见：[EvineDeng/jd-base](https://github.com/EvineDeng/jd-base)，适用于以下系统：

    1. Armbian/OpenWrt/Debian/Ubuntu/CentOS/Fedora/RedHat等Linux系统

    2. Android

    3. MacOS

### 方法二：云服务器、腾讯云函数等等

  - 需自行有云服务器，云函数等
  - 腾讯云云函数 [快速部署教程](https://github.com/ww69mm/jc/blob/main/tencentscf.md)（免费）
  - 腾讯云云函数控制台使用 [教程说明](https://github.com/ww69mm/jc/blob/main/iCloud.md#1%E5%AE%89%E8%A3%85-nodejs-%E7%8E%AF%E5%A2%83)
  - 腾讯云云函数 [GitHub Action部署教程](https://github.com/ww69mm/jc/blob/main/tencentscf.md#github-action-%E9%83%A8%E7%BD%B2)
       
 
### 方法三：Docker（NAS或VPS用户）

 - 可以精确控制任务运行时间，有二种办法：[docker办法一](https://github.com/ww69mm/jc/tree/main/docker)、[docker办法二（和本地安装Node.js类似）](https://github.com/EvineDeng/jd-base)
 - [环境变量集合](https://github.com/ww69mm/jc/blob/main/githubAction.md#%E7%8E%AF%E5%A2%83%E5%8F%98%E9%87%8F%E8%AF%B4%E6%98%8E)
 
#### 注：以上三种运行机制都是Node.js，故您需仔细阅读下面几点


  - 如果使用方法一与方法二，需自行提供京东cookie填写到 [jdCookie.js](https://github.com/ww69mm/jc/blob/main/jdCookie.js) 里面

   
  - 获取京东cookie教程可参考 [浏览器获取京东cookie教程](https://github.com/ww69mm/jc/blob/main/GetJdCookie.md) , [插件获取京东cookie教程](https://github.com/ww69mm/jc/blob/main/GetJdCookie2.md)

  - 方法三Docker安装Cookie请见各自的说明。

### 方法四：iOS系统的代理软件（QuantumultX, Surge, Loon, 小火箭）

#### [京东cookie获取脚本](https://github.com/ww69mm/jc/blob/main/JD_extra_cookie.js)

这只是我结合各位大佬整理出给自己方便用的小教程

# 一键启动开发环境
> 每天早上打开电脑，就需要做一系列事情
>1. 打开微信、钉钉、WebStorm
>
>2. 打开`nginx`代理
>
>3. 打开终端，执行`npm run dev:local`

>我感觉这些事情就很繁琐，至少浪费两分钟，于是就写了这个脚本。每天打开电脑只需要点击这个脚本就自动执行这些操作。

## 使用步骤：
1. 克隆该项目
2. 进入该项目，将`setup.sh`文件中的项目路径修改为自己项目的路径。
3. 授权
``` shell
chmod +x ./setup.sh 
```
4. 将这个`shell`脚本的快捷方式放在桌面上。
5. 以上就是准备工作，以后每天就只需要点击这个`shell`脚本。

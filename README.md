[engish README]()
# 台电 X98 Plus WiFi版 平板 安装 archlinux
## 使用本教程时,你需要准备的东西
[台电X98 plus WiFi版](http://item.jd.com/2302510.html)
#
[usb otg线+USB hub分线器+USB hub分线器电源](http://item.jd.com/10445047873.html)

ps:usb hub必须插上外接电源
#
[usb有线网卡](http://item.jd.com/10325708010.html)
#
有线网络+网线+USB键盘+USB鼠标
#
[存储容量大于4GB的U盘](http://search.jd.com/Search?keyword=u%E7%9B%98&enc=utf-8&suggest=1.def.0&wq=upan&pvid=xhw2qiri.qixxuy#keyword=u%E7%9B%98&enc=utf-8&qrst=1&rt=1&stop=1&vt=2&offset=3&psort=3&click=0)
## 制作archlinux U盘启动盘
### 到开源镜像网站下载最新的archlinux镜像
[下载镜像](http://mirrors.163.com/archlinux/iso/)
### 使用镜像制作启动盘
#### linux或者unix bash下执行
sudo dd if=镜像 of=U盘位置
#### win
下载ultraiso 或者unetbootin 把镜像 写入 U盘 
## 启动镜像
1. 把 USB-OTG 插进 平台的microusb(普通安卓数据线)口 
2. USB hub插上USB otg,usb hub 并且接上外接电源
3. USB鼠标+USB键盘+USB有线网卡插上USB hub上
4. USB有线网卡接上网线
5. 平板按电源键开机 键盘一直按delete或者esc进入BIOS
6. 选择启动项usb ****uefi 启动U盘
7. 等待镜像加载 

## 安装archlinux
见[官方教程](http://bbs.archlinuxcn.org/viewtopic.php?id=1037)
## 重启 进入系统 开始享受archlinux吧

 

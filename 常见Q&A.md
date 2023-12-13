# Q&A

## Q：使用无线键鼠时被干扰怎么办？

A：2.4GHz接入USB3.0 TypeA（蓝色内端子）接口时可能会造成串扰问题，可尝试将2.4GHz接入USB2.0 TypeA（白色内端子）接口使用。

## Q：没有浏览器怎么办？

A：可以下载Firfox浏览器，或者使用Chrome浏览器。以FireFox为例，在新打开的终端中输入：

```shell
sudo apt update
sudo apt install firefox
```

等待安装完成，在终端中输入firefox或者在左上角依次点击“Applications->Internet->Firefox Web Browser”即可使用。

## Q：安装软件时报错“E：You don't have enough free space in ...”怎么办？

A：在终端中使用如下命令进行扩容：

```shell
sudo resize2fs /dev/mmcblk0p16
```

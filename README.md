
适用于windows系统
# 背景：
由于Obsidian的各个本地vault的配置设置互相独立
使得每次新建一个vault都得手动同步设置很麻烦（特别是个人配置更新时，需要手动同步所有Vault）

于是我在这里记录我个人用的一个配置
对于以后新的vault，只需要在对应根目录下执行
```shell
cmd /c mklink /d /j .obsidian "D:\Study\Note\个人配置1\.obsidian"
```
即可高效同步

注意：
后面的`"D:\WorkSpace\Note\个人配置1\.obsidian"`应根据个人需求改变

参考资料
![[Pasted image 20251106123014.png]]
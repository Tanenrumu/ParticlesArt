# ParticlesArt
ParticlesArt是一款可以将大多数图片和视频在Minecraft中使用mcfunction并以粒子的形式呈现出来的工具。

![](/ScreenShot.png)
## 运行环境 Environment
  Windows
  
  ffmpeg支持(已包含在库内)
  
  足够的硬盘空间(根据图片像素视频的帧数)
  
  Windows ALL
  
  ffmpeg support(Included in Library)
  
  Enough hard disk space(based on picture pixels and video frames)

## 提示 Notice

请不要直接将像素非常大的视频或图片进行转换，像素非常大的视频或图片在Minecraft中需要非常大的运行内存，如果游戏内存设置不当会造成游戏卡顿甚至崩溃。

## 使用教程

打开软件选择 文件——图片或视频——设置大小和位置方向
——设置/游戏版本——文件/导出为mcfunction
——按提示选择文件夹(1.12是存档下的data\functions文件夹，1.13为存档下的datapacks文件夹)

然后进入游戏输入/reload

接下来有两个情况

1. 如果你生成的类型为图片：
  输入命令/function particlesart:image
  (生成的第二个为particlesart1:image，第三个particlesart2:image...以此类推)

2. 如果你生成的类型为视频：
  请放制一个命令方块并设置为循环模式
  输入命令/function particlesart:main
  (生成的第二个为particlesart1:main，第三个particlesart2:main...以此类推)
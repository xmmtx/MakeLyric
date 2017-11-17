# MakeLyric
支持qrc、krc、trc、网易云音乐的歌词相互转，支持输出krc、qrc、trc、  
网易云音乐、srt、smi、lrc、ksc、ssa、foobar2000插件eslyric格式    


鉴于有些人实在让人生气，所以不再开源了，只提供编译好的二进制下载。  

**本工具免费不收取任何费用，只此一个渠道发布，其它位置下载的请小心使用。**

## 更新日志

>
 2017-11-18  
    v1.2  

1、歌词转换及歌词制作合并为一个程序  
2、歌词制作增加动感歌词“预览”功能   

>
 2017-11-12   
    v1.1.2  

1、可词制作增加重置功能。  
2、增加对foobar2000->ESLyric输出及转换功能  
  
2017-11-12   
    v1.1  

1、修复制作QRC或者转换QRC错误问题  
2、歌词制作工具改为bass.dll解码    
3、歌词制作新增加 左键退回一个字、上键退回一行，并重构右方向键功能  
4、歌词制作和歌词转换工具新增加 SRT、SSA、SMI字幕输出  
5、歌词转换工具增加转换完成后信息框提示。  
6、歌词制作工具“制作动感歌词”页去掉进度条，改为文字显示，并增加制作状态提示、制作提示  
7、歌词制作工具“制作动感歌词”页歌词的每个字调整为在指定矩形居中显示    
 


## 使用方法 

下载最近版本中的“附件： LyricToolsBin.zip”，地址：  https://gitee.com/ying32/MakeLyric/releases   


主界面：   
![主界面](https://gitee.com/ying32/MakeLyric/raw/master/screenshots/1.jpg)    

多格式歌词转换  

将LyricTools.exe与bass.dll放入歌词目录或者将歌词文件放入LyricTools.exe所在目录，然后勾选“输入类型”项和“输出类型”，再点击转换即可。      

![歌词互转工具](https://gitee.com/ying32/MakeLyric/raw/master/screenshots/2.jpg)  

 
动感歌词制作     

制作分四部分:  

* 1、  选择一个音频文件  
* 2、  填入要制作的歌词, 这个暂时自己编辑  
* 3、  填写歌词对应的歌曲信息和输出格式  
* 4、  进入歌词制作页, 以上步骤完成后, 按<空格键>即可播放和暂停, 敲击<右键> 制作,  <左键>退回一个字，<上键>退回一行， <下键> 为停顿 ,  制作方面暂只提供这两个功能     

    完成后点击<输出>按钮即可将歌词输出到软件当前目录(暂不提供其它目录)  

**需要注意的:**  
* 1、  当为歌词最后一个字的时候请多一按下<右键>或者按下<下键>以便结束本次制作  
* 2、  暂只支持制作中文歌词,  这点需要特别注意, 否则别说博主坑你们了。  

相关截图：  

* 1、填写歌词部分  

![步骤一](https://gitee.com/ying32/MakeLyric/raw/master/screenshots/3.jpg)    

* 2、 歌词信息和输出部分   

![步骤二](https://gitee.com/ying32/MakeLyric/raw/master/screenshots/4.jpg)    

* 3、 制作界面    

![步骤二](https://gitee.com/ying32/MakeLyric/raw/master/screenshots/5.jpg)    

预览歌词：  
![预览歌词](https://gitee.com/ying32/MakeLyric/raw/master/screenshots/6.jpg)   

## 其他 

音频解码上使用了免费的bass.dll，[license](http://www.un4seen.com/bass.html#license)  
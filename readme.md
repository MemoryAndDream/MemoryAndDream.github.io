# MP3recorder
A tool for record music in the webpage online.All operations work online,without connect to any server.
Recorder can only run with localhost or https

改编自 https://aws.nlited.org/mp3.htm  
基于lamejs编写 [https://github.com/zhuker/lamejs]
录制功能需要https或者localhost才能运行

TODO:
操作流程优化，需要吧power和record合并
音质好像有点差,可能是因为mp3是个压缩格式

重新录制现在需要power

原音质下载？

qq音乐能自动识别曲子。。。根据名称？

为什么人家的音质就好很多，这边录制结果就是断音的？断音，轻音

是不是还是有奇怪的自动优化？



如果有裁剪，能不能iframe裁剪？

测试wav单声道

似乎一定要有进有出？

貌似中间节点必须有输出，不然就不运行！！

感觉要异步+缓存 就是worklet

要关注录制中不能cpu打断

果然是这样！所以必须录制完再转码！！

转码需要独立啊

优化cpu！！
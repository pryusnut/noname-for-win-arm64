代码源于诗笺windows客户端，项目地址：https://github.com/nonameShijian/noname  
---
通过在**pakage.json**中添加`pakageArm64`选项实现打包arm64客户端    
执行`npm run packageArm64`即可自行完成打包  
**代码未原生适配windows arm，因此产生任何bug都有可能**     
**不想折腾的玩家最好还是安装官方的x64客户端**
---
在release中提供打包好可以**直接游玩**的客户端并内置了v1.10.17完整包（别问为什么不是1.10.17.1，问就是没下到）  
preview版不包含完整包（但客户端相同），启动后需自行导入完整包才能有武将插画和语音。
也可前往https://pan.quark.cn/s/1eba6d7cb69a 下载，提取码Bp5n。（不包含完整包的版本）    
目前已经在搭载win11 24H2的高通8cx gen3上成功运行（未加载任何额外扩展包） 

---
目前已知问题包括：    
- 无名杀启动速度较windows x64或安卓客户端明显变慢（也有可能是windows的锅)；
- **不要使用游戏内生成的快捷方式打开无名杀，这会导致拖拽读取扩展报错，建议在系统中右键无名杀发送快捷方式的方法生成快捷方式**    
- 首次启动无名杀时可能会提示载入失败，是否重置，选择取消即可；    
- 内置的网页版客户端进入时会报错。    
---
**其他注意事项或问题请前往原项目处查看或提问**    
**由于本人对软件编程并不擅长，你有什么问题我也解决不了ㄟ(◑‿◐ )ㄏ**

# BlueTeamTool
此工具是一款蓝队综合工具。界面参考其它工具设计，相关解密操作例如log4j，已经切断jndi的lookup，不会触发漏洞，内存马检测会注入java agent，生产环境谨慎使用，出了事故本人概不负责。

免责声明：
      如您在使用本工具的过程中存在任何非法行为，您需自行承担相应后果，我们将不承担任何法律及连带责任。

下载地址：https://github.com/achiove/BlueTeamTool/releases/tag/v1.0

运行：java -jar BlueTeamTool.jar 

版本：1.0 （仅支持jdk8)
## 反编译
支持Java class反编译、base64解码后反编译、Bytes数组解码后反编译、$$BCEL$反编译、Base64解码Gunzip解码后反编译
内嵌5种反编译工具：1、Procyon 2、CFR 3、FernFlower（IDEA内置) 4、jd-core （jd-gui）5、jdk反编译
![image](https://github.com/achiove/BlueTeamTool/assets/31579519/b82ed8b5-8865-4d49-b6c6-03332504aadb)

## 解密Shiro/Cas/Log4j
Shiro解密支持枚举key、自定义key解密，支持自定义枚举字典
![image](https://github.com/achiove/BlueTeamTool/assets/31579519/dd73e1de-cd64-4480-8103-7d7fe946307c)

## Webshell流量解密
支持冰蝎、哥斯拉3.x-4.x的流量解密
![image](https://github.com/achiove/BlueTeamTool/assets/31579519/354d1817-99b6-45cb-a020-7133fb74087f)

## 内存马检测
1、MemshellScanner
https://github.com/c0ny1/java-memshell-scanner/

2、CopAgent
https://github.com/LandGrey/copagent
![image](https://github.com/achiove/BlueTeamTool/assets/31579519/1a938f28-df19-4f84-ba30-7fc07cfe8e1e)

## HTTP2Curl
支持将http请求转换为curl命令，暂不支持文件上传和二进制流
![image](https://github.com/achiove/BlueTeamTool/assets/31579519/73b6e833-cbfe-4348-a859-c94fc90bf2a2)

## BUG反馈：
https://github.com/achiove/BlueTeamTool/issues

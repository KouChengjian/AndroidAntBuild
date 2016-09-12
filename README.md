# AndroidAntBuild
android 多渠道打包实例

###library
android update lib-project -p ./ <br/>

###project
android update project --name MenudrawSample -p ./ --subprojects  <br/>
android update project -p ./ --subprojects  <br/>

###ant debug
生成一个测试版apk，默认使用 debug key 进行签名，生成的apk（your_project_name-debug.apk）在bin目录下。<br/>

###ant release
生成一个未签名和未aligned的apk包，生成的apk（your_project_name-release-unsigned.apk和your_project_name-release-unaligned.apk）在bin目录下<br/>

###ant deploy
打包渠道包<br/>

# Vue-notes
搭建vue的开发环境：


	1、必须要安装nodejs


	2、搭建vue的开发环境 ，安装vue的脚手架工具   官方命令行工具

		npm install --global vue-cli  /   cnpm install --global vue-cli         （此命令只需要执行一次）

	
	3、创建项目   必须cd到对应的一个项目里面
			
		vue init webpack vue-demo01

		cd  vue-demo01 
		
		cnpm install   /  npm install          如果创建项目的时候没有报错，这一步可以省略。如果报错了  cd到项目里面运行  cnpm install   /  npm install
		
		npm run dev


	
	4、另一种创建项目的方式   （推荐）  ***
		

		vue init webpack-simple vuedemo02

		cd  vuedemo02
		
		cnpm install   /  npm install        
		
		npm run dev

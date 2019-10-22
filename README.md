# template-engine
this repo include a js file,withinwhich has a template-engine object named "Template",you can define yourself template tags(模板标记，界定模板的边界标志符) as follow,eg:
 <h2> <pre>Template.templateTagConfig({//自定义配置模板标签
	 	openTag:"{{",
	 	closeTag:"}}",
	 	assignmentTag:"{{ ="
	 });
</pre>
</h2>
And use the Template.__template method to render your template as follow,eg:
  <h2><pre>document.querySelector("table").innerHTML = Template.__template("#template3",{list:list});</pre></h2>
  
Webpack编译原理  https://www.jianshu.com/p/c9627135312b
配置webpack-chain https://github.com/neutrinojs/webpack-chain
vue-config.js
基于vue-cli3 SSR  https://zhuanlan.zhihu.com/p/64829195 
大搜车技术博客  https://blog.souche.com/
babel发展历程  https://blog.csdn.net/qq_40171039/article/details/78326344
js事件循环  http://lynnelv.github.io/js-event-loop-browser
前端面试与进阶  https://www.cxymsg.com/guide/
前端书籍  https://www.cnblogs.com/dydxw/p/10735955.html

https://cli.vuejs.org/config/#publicpath-------vue cli 3



  

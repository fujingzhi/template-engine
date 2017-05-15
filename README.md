# template-engine
template-engine
this file include a js file,withinwhich has a template-engine object named "Template",you can define yourself template tags as follow:
  eg:Template.templateTagConfig({//自定义配置模板标签
	 	openTag:"{{",
	 	closeTag:"}}",
	 	assignmentTag:"{{ ="
	 });
And use Template.__template function to render your template as follow:
  document.querySelector("table").innerHTML = Template.__template("#template3",{list:list});

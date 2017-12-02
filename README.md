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
  <h2>document.querySelector("table").innerHTML = Template.__template("#template3",{list:list})</h2>;
  

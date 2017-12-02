# template-engine
template-engine
this file include a js file,withinwhich has a template-engine object named "Template",you can define yourself template tags as follow,eg:
 <h1> <pre>Template.templateTagConfig({//自定义配置模板标签
	 	openTag:"{{",
	 	closeTag:"}}",
	 	assignmentTag:"{{ ="
	 });
</pre>
</h1>
And use the Template.__template method to render your template as follow,eg:
  <h1>document.querySelector("table").innerHTML = Template.__template("#template3",{list:list})</h1>;
  

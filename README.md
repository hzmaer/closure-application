# closure-application
闭包各种经典应用

1.闭包结合localStorage计算函数总共被调用多少次

var a = localStorage.getItem('name') || 0;

		function b(){
		
		return a++;	
		
		}
		
b();

localStorage.setItem("name",a);

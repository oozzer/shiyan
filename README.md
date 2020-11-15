# shiyan
disici  
#2020322071 宋纪龙  
#阅读程序  
##实验目的  
1.掌握Java中抽象类和抽象方法的定义  
2.掌握Java中接口的定义，熟练掌握接口的定义形式以及接口的实现方法  
3.了解异常的使用方法，并在程序中根据输入情况做异常处理  
##实验过程  
1.  
##核心方法   
1.  
```  
public class Graduate {	
			String name;
			String sex;
			int  age;
			float pay;
			float fee;
			Graduate(){	
			}
		public Graduate(String name, String sex, int age ) {
			this.name=name;
			this.sex=sex;
			this.age=age;  
```  
2.  
```Graduate  g = new Graduate("宋纪龙","男",20);
		System.out.println("-------个人信息管理-------");
		System.out.println("姓名："+g.getName());
		System.out.println("性别："+g.getSex());
		System.out.println("年龄："+g.getAge());
		System.out.println("-------------------------"+"\n");
		Scanner scanner = new Scanner(System.in);
		System.out.println("请输入月收入：");
		float fee = scanner.nextFloat();
		g.setFee(fee);
		System.out.println("-------------------------"+"\n");		
		System.out.println("请输入学费：");  
``` 
使用scanner输入法  
3.  
```public void setFee(float fee) {
			this.fee = fee;
			System.out.println("学费为：" + this.fee);
		}
		
		public void getFee(float fee) {
			this.fee = fee;
			System.out.println("学费为：" + this.fee);
		}
		public void setPay(float pay) {
			this.pay = pay * 12;       
			System.out.println("年收入为：" + this.pay);
		}
		
		public void getPay(float pay) {
			this.pay = pay * 12;
			System.out.println("学费：" + this.pay);
		}
		public boolean paytaxes(){    
			if ((this.pay - this.fee) < 5000) {
				System.out.println("纳税金额为:"+(this.pay -this.fee)*0.03f+"\n");
				return true;          
			}
			else {
				System.out.println("纳税金额为:"+(this.pay -this.fee)*0.03f+"\n");
			    return false;         
			} 
		}
}  
```   
 
##实验结果  
-------个人信息管理-------
姓名：宋纪龙
性别：男
年龄：20
-------------------------

请输入学费：
4600
学费为：4600.0
-------------------------

请输入月收入：
5000
年收入为：60000.0
-------------------------

纳税金额为:1662.0

您需要纳税！ 
说明：输入学费，显示学费为：XXX。输入月收入，显示年收入为：XXX。判断是否纳税，如需纳税，则显示纳税金额为：XXX。如不需要纳税，显示不需要纳税。  

##实验感想  
通过本次实验我了解了异常处理机制，会简单的处理一些异常，同时也了解了字符串的使用。这仅仅是简单的异常处理，必须进一步对异常熟悉。还有对字符串的其他方法进行练习并熟练掌握。还需要在课下多多练习，熟悉他们。



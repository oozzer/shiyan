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
#实验结果  



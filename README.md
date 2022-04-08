
public  class MethStat {
	
	int one =1;
	static int two =2;
	
	  static {
		System.out.println("This is  1st static block");
	}

	 {
			System.out.println("This is 1st  non-static block");
		}
	 static{
			System.out.println("This is  2nd static block");
		}
	 
	 void met1() {
		 System.out.println("non static method 1");
	 }
		 
    static void met2() {
			 System.out.println(" static method 2");
			 	 
		 
	 }
    
    
	public static void main(String[] args) {
		
		MethStat a = new MethStat();
		met2();
		a.met1();
		met2();
		met2();
		System.out.println(two);
		System.out.println(a.one);
		

	}

}

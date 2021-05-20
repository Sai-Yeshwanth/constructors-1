class Add
{
	int a=5,b=7;
	Add()
	{
		System.out.println(a+b);
	}
	Add(int c)
	{
		System.out.println(a+b+c);
	}
	Add(int c,int d)
	{
		System.out.println(a+b+c+d);
	}
}
class Jala {
	public static void main(String[] args) {
		Add a = new Add();
		Add b = new Add(5);
		Add c = new Add(5,6);
		
	}
}


interface and{
    int a=10;
    public void test();
}
class B
{
    int b=20;
    public void show();
    {
        System.out.println("class method implemented");
        System.out.pritnln("b="+b);
    }
}
class Sample extends B implements A
{
    public void test()
    {
        System.out.println("Interface A Method implemented");
        System.out.println("a="+a);
    }
}
class Interface_example2
{
    public static void main(String args[])
    {
        Sample p=new Sample();
        p.test();
        p.show();

# Overriding
public class Main extends kia
{
void move(){
System.out.println(&quot;KIA is moving&quot;);
}
public static void main(String[] args) {
Main m=new Main();
m.move();
}
}
class kia{
void move(){
System.out.println(&quot;Car is moving&quot;);
}
}

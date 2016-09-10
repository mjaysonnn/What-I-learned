# Java ( Picture will be shown if possible)


<hr/>

> ##중복 없는 난수 만들기 (Random Number with no duplicates)
> **랜덤으로 숫자를 만들때 중복된 난수가 생길수있다. (Same numbers can occur when making random number)
> **There's a way to handle that.


    ArrayList<Integer> ranNumber = new ArrayList<Integer>();

    for(int i=0; i <25;i++){

    ranNumber.add(i);

    }

    Collections.shuffle(ranNumber);

    System.out.println(ranNumber);

> Shuffle로 중복을 없애준다
> **Shuffle is used to remove the same number 

<hr/>
> ##클래스란 무엇인가     What is Class??? 

> 클래스는 타입의 유형이다      Class is a type of data

<hr/>

> ## println을 할 때 일어나는 일         Things about println(a)

> println을 하면 자동으로 toString()을 부른다


> when you type that code
> it automatically calls toString()

<hr/>

> ## 데이터의 타입에 따라서 참고하는 것이 다르다   

> Reference  depending on data types


<hr/>

> ## Things about Constructor

> 1. for example when you call SimpleLocation A = new SimpleLocation();

> in heap there is going to be some information from constructor

> 2. loc1 = loc2  (this is a object)

> loc1's reference will have the same information as loc2's reference.

> Once a  constructor is called and there will be something in local variable. When calling construcotr is done.

> local variable dissappears.

<hr/>

> ## Make a compile in Linux

> javac *java  (compiling)

> java LocationTester   (e.g Run in Eclipse)

<hr/> 

> ## Different types of Data 

> Primitive Type : byte, char, int, double, char

> Object Type: Arrays and Classes

<hr>

> ## List 

> What is definition? 

> Orders List of things of type Feature

> how to use for()?

> for(Marker mark: countryMarkers)
>   Data Type  variable  ListName

<hr/>

> ## pApplet

> This was used for showing map , image in Ecllipse 

> Anyway, When you wanna make something in Picture by rate(?) 

> for example 

     ecllipse(width/4,height/5,width/4,height/4)

> [Example of ecllipse] (https://mjsonblog.wordpress.com/2016/09/10/java-%ea%b3%b5%eb%b6%80)

> Simple Principle can be explained ----> draw()--loop  setup()---initiate
<hr/>

> ## API

> What is it -> Application Programming Interface

> API(Application Programming Interface, 응용 프로그램 프로그래밍 인터페이스)는 응용 프로그램에서 사용할 수 있도록, 운영 체제나 프로그래밍 언어가 제공하는 기능을 제어할 수 있게 만든 인터페이스를 뜻한다. 주로 파일 제어, 창 제어, 화상 처리, 문자 제어 등을 위한 인터페이스를 제공한다.”


> API doesn't show what's inside the code but lets you download or upload or use it 

> That's what api does.

<hr/>

> ## GUI 

> Graphics User Interfae 

> Processing is one of GUI.

> to know about the Processing there is a documnet which you will see while coding 

> make a habit of seeing document when coding.

> [Example of Documentation](https://docs.oracle.com/javase/8/docs/api/)

<hr/>

> ## Coding from Map 

     for (String row : rows) {
       String[] columns = row.split(",");
       if ( ... ) {
          float value = Float.parseFloat(columns[5]);
          lifeExpMap.put(columns[4],value);
       }
     }


<hr/>

> ##Inheritance from Coding

> [Picture of Example] (https://mjsonblog.wordpress.com/2016/09/10/java-%ea%b3%b5%eb%b6%80)
   
     public Student () {
     this("Student");
     System.out.print("#2 ");
     }
     public Student( String n ) {
     super(n);
     System.out.print("#3 ");
     } }

> 	this(“Student”)은 아래에 있는 public Student(String n) 로 가는 것이다
>   this("Studnet") is same as public Student(String n)

     public class Student extends Person { public void method1() {
     System.out.print("Student 1 "); super.method1(); this.method2();
     }
     public void method2() {
     System.out.print("Student 2 ");
    
>    this.method2() what is this ? it is the type of object at runtime
>    which means 'this'  can't be always a object from Student.
>    by the way, super is Person class

<hr/>

> ##Interface

> you use interface when you wanna use a specific method.

> ###Difference between Interface and abstract class

[See] (https://mjsonblog.wordpress.com/2016/09/10/java-%ea%b3%b5%eb%b6%80)

<hr/>

> ## Polymorphism

> you have to thinkg about 2 things

> 1. Runtime

> 2. Compile 

> for example a code can will be okay from Runtime but doesn't work when Compile error

> (i will show an example later.)
 
<hr/>

> ## Sort , Search

> Insertion Sort


> Selection Sort
>starting from left to right
>sort each time (?)

> Binary Search
>faster than Linear search 
>logn
>like binary tree divied by half

<hr/>

> ## Event Driven Programming Example

[See] (https://mjsonblog.wordpress.com/2016/09/10/java-%ea%b3%b5%eb%b6%80)

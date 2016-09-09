 # What-I-learned

# I'm gonna write what i learned in here

## by category e.g example spark , java

<hr/>

> **This is can be wriiten without Git.**

> **By doing this, i am learning MarkDown anyway.**

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

> ## 데이터의 타입에 따라서 참고하는 것이 다르다        Reference  depending on data types

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


> **Shuffle is used to remove the same number 
<hr/>

# Java-Language

package com.apnacollege;

public class Main {

    public static void main(String[] args) {
	// write your code here
        System.out.println("Hello World");
    }
}

//Varibles

package com.apnacollege;

public class Main {

    public static void main(String[] args) {
	// write your code here
        int age= 02;
        //System.out.println("Hello World");
        String name= "Nikhil";
        String neighbour = "Akku";

        String friend= neighbour;
        System.out.println(age);
        System.out.println(name);
        System.out.println(neighbour);
        System.out.println(friend);
    }
}



//Java Types

package com.apnacollege;
// Primitives types
public class Main {

    public static void main(String[] args) {
	// write your code here
       //byte -1 [-128 to 127]
        //short -2
        //int - 4
        //long -8
        //float- 4
        //double- 8
        //char- 2
        //boolean- 1 true/false

        byte age=30;
        int phone=1234567890;
        long phone2=12345678900L;
        float pi=3.14F;
        char letter='@';
        boolean isAdult= true; //because age is 30, which is greater than 18

        System.out.println(phone);
        System.out.println(age);
    }
}




//Non primitives

package com.apnacollege;

public class Main {

    public static void main(String[] args) {
        // write your code here
        //Non-primitive types
       String name= "Nikhil";
        //System.out.println(name.length()); //we can call the functions of non primitives using . operator !!
        String friend= "More";
        System.out.println(name.length());


    }
}


//Strings


package com.apnacollege;

public class Main {

    public static void main(String[] args) {
        // write your code here
        //concatenate
        String name1= "Nikhil";
        String name2= "More";
        String name3= name1 + " " + name2;
        System.out.println(name3);

        System.out.println(name1.charAt(0));


    }
}




# Java-Language

package com.apnacollege;

public class Main {

    public static void main(String[] args) {
	// write your code here
        System.out.println("Hello World");
    }
}

**************************************************************************************************8

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

*****************************************************************************************************

//Java Types

package com.apnacollege;

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




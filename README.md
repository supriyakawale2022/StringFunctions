# StringFunctions

package ex_15_String_Functions;

public class Lab_141_All_String_Functions
{
    public static void main(String[] args)
    {
        String name ="Supriya";
        //1. Char At ()
        System.out.println(name.charAt(6));
       // System.out.println(name.charAt(9));  //StringIndexOutOfBoundsExceptions

        //2.Concat()
        System.out.println(name.concat("Kawale"));

        //3.contains()
        System.out.println(name.contains("priya"));

        //4.equals()
        System.out.println(name.equals("Supriya"));

        //5.equalsIgnoreCase()
        System.out.println(name.equalsIgnoreCase("SUPRIYA"));

        //6.indexof
        String s1="madam";
        //first occurrence of the specified substring
        System.out.println(s1.indexOf("m"));
        System.out.println(name.indexOf("i"));

        //7. length()   it finds the total length of the string
        System.out.println(name.length());

        //8.replacae( , )
        System.out.println(name.replace('a', 'o'));

        //9.split()   to splitup the word.
        String name4="supriya@kawale@1990";
        String[] split=name4.split("@");
        System.out.println(split[0]);
        System.out.println(split[1]);
        System.out.println(split[2]);


        System.out.println("---------------------");

        //10.substrsing()
      //  String name1="supriya";
        System.out.println(name.substring(1,5));

        //11.toLowerCase()
        System.out.println(name.toLowerCase());

        //12.toUpperCase()
        System.out.println(name.toUpperCase());

        //13.startsWith()
        System.out.println(name.startsWith("S"));

        //14.endWith()
        System.out.println(name.endsWith("a"));

        //15.trim()
        String name3="     Maya     ";
        System.out.println(name3.trim());

        //16.compareTo()
        System.out.println(name.compareTo("Supriya"));

        //17.CompareToIngnoreCase
        System.out.println(name.compareToIgnoreCase("SUPRIYA"));




    }
    }

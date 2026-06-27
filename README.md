public class Main {
    public static void main(String[] args) {
        // All primitives except long and double
        char H = 'H';      // char 
        byte three1 = 3;   // byte -> 3 
        byte one1 = 1;     // byte -> 1
        byte one2 = 1;     // byte -> 1
        byte zero1 = 0;    // byte -> 0
        
        char w = 'w';      // char
        byte zero2 = 0;    // byte -> 0 
        char r = 'r';      // char
        char l = 'l';      // char
        char d = 'd';      // char
        
        float twoPointZero = 2.0f; // float -> 2.0
        boolean t = true;  // boolean -> true

        // Concatenate - the "" forces everything after to be String
        String output = H + "" + three1 + one1 + one2 + zero1 + " 
                        + w + zero2 + r + l + d + " 
                        + twoPointZero + " + t;
        
        System.out.print(output); // prints: H3110 w0rld 2.0 true
    }
}

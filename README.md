# A_2_Z_DSA_Sheet
DSA from A to Z:  https://takeuforward.org/strivers-a2z-dsa-course/strivers-a2z-dsa-course-sheet-2/


# Step 1  : Learn the basics
---------------------------------

# Step 1.1 : Things to Know in C++/Java/Python or any language
-----------------------------------------------------------------

#1 ) User Input / Output ->  https://practice.geeksforgeeks.org/problems/java-inputoutput0118/1



    static void printIntString(String S,int N){
        // code here
        System.out.println("The input string :"+S);
        System.out.println("The input integer :"+N);
    }


#2 ) Data Types -> https://practice.geeksforgeeks.org/problems/java-basic-data-types0041/0



    int javaIntType(Scanner sc) {
        // code here
        int intNumber = sc.nextInt();
        return intNumber;
    }
    
    String javaStringType(Scanner sc) {
        // code here
        String str = sc.next();
         return str;
    }
    
    float javaFloatType(Scanner sc) {
        // code here
        float decimalNumber = sc.nextFloat();
        return decimalNumber;
    }


#2) If Else statements -> https://practice.geeksforgeeks.org/problems/java-if-else-decision-making0924/0


    static String compareNM(int n,int m){
        // code here
        if(n==m){
            return "equal";
        }
        else if(n>m){
            return "greater";
        }
        else{
            return "lesser";
        }
    }

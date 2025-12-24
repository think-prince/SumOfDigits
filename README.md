# SumOfDigits
Code that calculates the same of digits
 class SumOfDigits {
    int s=0;
    public int sum(int num){
        if (num<0){
            System.out.println("Invalid Number");
         return 0;
        }
        while(num!=0){
            s =s+ num%10;
            num = num/10;

        } return s;
    }
}

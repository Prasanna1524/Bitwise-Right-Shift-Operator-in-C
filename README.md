# Bitwise-Right-Shift-Operator-in-C

## Program:

        #include <stdio.h>

        int main()
        {
            int val ;
            printf("Enter any Number = ");
            scanf("%d",&val);

            //Given number >> n  So number / (2n) is formula
            printf("\nValue / 2  = %d",val >>1);
            printf("\nValue / 4  = %d",val >>2);
            printf("\nValue / 8  = %d",val >>3);
            printf("\nValue / 10 = %d",val >>4);
            printf("\nValue / 12 = %d",val >>5);


            return 0;
        }
        
## Output:
        Enter any Number = 128

        Value / 2  = 64
        Value / 4  = 32
        Value / 8  = 16
        Value / 10 = 8
        Value / 12 = 4

public class LargestPrime {
    public static int  getLargestPrime(int number){
        int i;
        int max = -1;
        int z ;
        
        if(number > 1 && number != 2)
        {
            for(i = 2 ; i < number/2 ; i ++)
            {
                while(number%i==0)
                {   
                    max = i ;
                    
                    z = number / i ;
                    
                    number = number/i ;
                    if(z==number)
                    {
                        max = number ;
                    }
                }
                if(max==1)
                {
                    return 2 ;
                }
            }
            if(max== -1)
            {
                max = number ;
            }
            
            return max ;
        }else if(number==2)
        {
            return 2 ;
        }
        else
         return -1 ;
        
    }
}public class LargestPrime {
    public static int  getLargestPrime(int number){
        int i;
        int max = -1;
        int z ;
        
        if(number > 1 && number != 2)
        {
            for(i = 2 ; i < number/2 ; i ++)
            {
                while(number%i==0)
                {   
                    max = i ;
                    
                    z = number / i ;
                    
                    number = number/i ;
                    if(z==number)
                    {
                        max = number ;
                    }
                }
                if(max==1)
                {
                    return 2 ;
                }
            }
            if(max== -1)
            {
                max = number ;
            }
            
            return max ;
        }else if(number==2)
        {
            return 2 ;
        }
        else
         return -1 ;
        
    }
}

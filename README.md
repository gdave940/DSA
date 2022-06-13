# DSA

https://practice.geeksforgeeks.org/problems/factorial5739/1
```
class Solution{
    static long factorial(int N){
        if(N==0)
        return 1;
    return N*factorial(N-1);
    }
}
```

https://practice.geeksforgeeks.org/problems/nth-fibonacci-number1335/1?utm_source=inf&utm_medium=inf%2Fcampaign+&utm_campaign=codein10_fibonacci_YT
```
class Solution {
    static long nthFibonacci(long n){
        if(n==0){return 0;}
        if(n==1){return 1;}
        return nthFibonacci(n-1)+nthFibonacci(n-2);            
    }
}
```
https://practice.geeksforgeeks.org/problems/count-ways-to-reach-the-nth-stair-1587115620/1
```
class Solution
{
    //Function to count number of ways to reach the nth stair.
    int countWays(int n)
    {
        if(n==1 || n==2){return n;}
        return countWays(n-1)+countWays(n-2);
    }
}
```

Intialize n

temp=n

sum=0

order= length of n

WHILE n>0

    digit=n%10
    sum=sum+digit**order
    n=n/10
ENDWHILE

IF sum==temp

    PRINT "IT IS AN ARMSTRONG NUMBER"
ELSE

    PRINT "IT IS NOT AN ARMSTRONG NUMBER"
![func](https://lh3.googleusercontent.com/zgxHGbfJZy27iwLIPt_bpIT1wO4YiC64RYZf37P50d1P17XQWUNuJV7ymeJDAICZF5NLZOwzI5b37iXApUEsCzAUzZctPKMpT7jq4Kdxp3Xr7UXFAKrq=w1280)
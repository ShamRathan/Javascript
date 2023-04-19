# Javascript
### Name:  S.Sham Rathan
### Reg.no 212221230093
### 1.Get user input using prompt(“Enter your age:”). If user is 18 or older , give feedback: 'You are old enough to drive' but if not 18 give another feedback stating to wait for the number of years he needs to turn 18.
```
Solution:
var age=prompt("Enter your age:");
if (age>=18)
{
    console.log("You are old enough to drive")
}
else
{
    age=18-age;
    console.log("You are left with",age,"years to drive")
}
```
![image](https://user-images.githubusercontent.com/93587823/232979396-180ecfec-78b6-4851-8b8b-4c904bb9e7d4.png)
### 2.Compare the values of myAge and yourAge using if … else. Based on the comparison and log the result to console stating who is older (me or you). Use prompt(“Enter your age:”) to get the age as input.
```
Solution:
var my=prompt("Enter my age:");
var you=prompt("Enter your age:");
var diff1
if (my>you)
{
    diff1=my-you
    console.log("Iam are",diff1," years older than you")
}20
else
{
    diff1=you-my
    console.log("You are",diff1," years older than me")
}

```
![image](https://user-images.githubusercontent.com/93587823/232979514-b1b7ebf2-d12e-4015-8be3-5da8537496d7.png)
### 3.Even numbers are divisible by 2 and the remainder is zero. How do you check, if a number is even or not using JavaScript?
```
Solution:
var choice=prompt("Enter a number:")
if(choice%2==0)
{
    console.log(choice,"is an even number.")
}
else
{
    console.log(choice,"is an odd number.")
}
```
![image](https://user-images.githubusercontent.com/93587823/232979642-5b33878b-6cc4-4726-8767-dfe7e7e0a2fb.png)

### Github link:
https://github.com/ShamRathan/Javascript.git

## Configuring AWS CLI (Command Line Interface) with IAM User Account

## Terminal Commands

![Screenshot 2022-07-07 at 15.12.43.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657209556395/gdthGl99O.png align="left")
*Terminal screenshot (Green border = user values from IAM credential)*


- ```which aws``` -> Location of AWS folder
- ```aws --version``` or ```aws --v``` -> AWS version installed
- ```aws configure``` Configure AWS with IAM security credentials

## Generating the IAM credentials
![Screenshot 2022-07-07 at 14.59.35.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657210353310/Sc2BxUhe9.png align="left")
- Open AWS console, login and go to IAM Management Console. 
- Click on ```Add Users``` 

![Screenshot 2022-07-07 at 15.00.34.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657210538754/vLuzuw3Oo.png align="left")
- Input ```User name``` and select your ```AWS credential type```

![Screenshot 2022-07-07 at 15.01.33.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657210555329/BHsMoXG7k.png align="left")
- Attach policies

![Screenshot 2022-07-07 at 15.01.59.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657210993290/TFyF1ga2s.png align="left")
- Add tags

![Screenshot 2022-07-07 at 15.02.26.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657211018383/I-aMIqX2Q.png align="left")
- Review your details

![Screenshot 2022-07-07 at 15.03.08.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657211035102/rYJySuP70.png align="left")
- Copy your credentials

![Screenshot 2022-07-07 at 15.19.36.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657212783860/gt39ecZui.png align="left")
- Let the system know that your sensitive information is residing in the ```.aws folder```
- ```aws iam list-users``` -> Display IAM details in Terminal

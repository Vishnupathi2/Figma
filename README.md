# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div style="width: 100%; height: 100%; justify-content: flex-start; align-items: flex-start; gap: 48px; display: inline-flex">
      <div style="width: 343px; height: 640px; position: relative; background: grey">
            <div style="width: 300px; height: 37px; left: 47px; top: 23px; position: absolute; text-align: center; color: rgb(55, 51, 51); font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">Saveetha Engineering College</div>
            <div style="width: 300px; height: 37px; left: 20px; top: 221px; position: absolute; text-align: center; color: black; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">Affilated to  Anna University</div>
            <div style="width: 290px; height: 61px; left: 35px; top: 273px; position: absolute; text-align: center; color: black; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">NIRF Ranked<br/>Autonomous Institution<br/></div>
            <div style="width: 360px; height: 0px; left: 0px; top: 75.05px; position: absolute; border: 4px #9db326 solid"></div>
            <img style="width: 92px; height: 88px; left: 20px; top: 100px; position: absolute" src="S logo 1.png" />
            <div style="width: 99px; height: 44px; left: 221px; top: 122px; position: absolute; background: #29F94A; border-radius: 5px"></div>
            <div style="width: 79px; height: 15px; left: 229px; top: 135px; position: absolute; text-align: center; color: white; font-size: 18px; font-family: Inter; font-weight: 400; word-wrap: break-word">LOGIN</div>
            <div style="width: 261px; height: 267px; left: 47px; top: 349px; position: absolute; background: #29F94A"></div>
            <div style="width: 179px; height: 230px; left: 88px; top: 368px; position: absolute; text-align: center; color: white; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">CSE<br/><br/>AIDS<br/><br/>IT<br/><br/>ECE<br/><br/>EEE</div>
        </div>
        <div style="width: 343px; height: 640px; position: relative; background: grey">
            <div style="width: 300px; height: 37px; left: 22px; top: 26px; position: absolute; text-align: center; color: black; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">Saveetha Engineering College</div>
            <div style="width: 126px; height: 126px; left: 109px; top: 126px; position: absolute"></div>
            <div style="width: 249px; height: 48px; left: 44px; top: 305px; position: absolute; background: white; border-radius: 3px; border: 2px #29F94A solid"></div>
            <div style="width: 249px; height: 48px; left: 44px; top: 390px; position: absolute; background: white; border-radius: 3px; border: 2px #29F94A solid"></div>
            <div style="width: 179px; height: 24px; left: 28px; top: 402px; position: absolute; text-align: center; color: black; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">Password</div>
            <div style="width: 179px; height: 24px; left: 28px; top: 315px; position: absolute; text-align: center; color: black; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">user names</div>
            <img style="width: 92px; height: 88px; left: 20px; top: 100px; position: absolute" src="S logo 4.png" />
            <div style="width: 99px; height: 44px; left: 119px; top: 475px; position: absolute; background: #29F94A; border-radius: 5px"></div>
            <div style="width: 79px; height: 15px; left: 127px; top: 488px; position: absolute; text-align: center; color: white; font-size: 18px; font-family: Inter; font-weight: 400; word-wrap: break-word">LOGIN</div>
            <div style="width: 360px; height: 0px; left: 0px; top: 75.05px; position: absolute; border: 4px #29F94A solid"></div>
            <div style="width: 99px; height: 44px; left: 221px; top: 122px; position: absolute; background: #29F94A; border-radius: 5px"></div> 
            <div style="width: 79px; height: 15px; left: 229px; top: 135px; position: absolute; text-align: center; color: white; font-size: 18px; font-family: Inter; font-weight: 400; word-wrap: break-word">Register</div>
        </div>
        <div style="width: 343px; height: 640px; position: relative; background: grey">
            <div style="width: 300px; height: 37px; left: 22px; top: 26px; position: absolute; text-align: center; color: black; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">Saveetha Engineering College</div>
            <div style="width: 126px; height: 126px; left: 109px; top: 126px; position: absolute"></div>
            <div style="width: 249px; height: 48px; left: 44px; top: 305px; position: absolute; background: white; border-radius: 3px; border: 2px #29F94A solid"></div>
            <div style="width: 249px; height: 48px; left: 44px; top: 390px; position: absolute; background: white; border-radius: 3px; border: 2px #29F94A solid"></div>
            <div style="width: 179px; height: 24px; left: 28px; top: 402px; position: absolute; text-align: center; color: black; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">Password</div>
            <div style="width: 179px; height: 24px; left: 28px; top: 315px; position: absolute; text-align: center; color: black; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">Ref No</div>
            <img style="width: 92px; height: 88px; left: 20px; top: 100px; position: absolute" src="S logo 3.jpeg" />
            <div style="width: 99px; height: 44px; left: 108px; top: 472px; position: absolute; background: #29F94A; border-radius: 5px"></div>
            <div style="width: 79px; height: 15px; left: 118px; top: 481px; position: absolute; text-align: center; color: white; font-size: 18px; font-family: Inter; font-weight: 400; word-wrap: break-word">LOGIN</div>
            <div style="width: 360px; height: 0px; left: 0px; top: 75.05px; position: absolute; border: 4px #29F94A solid"></div>
            <div style="width: 99px; height: 44px; left: 221px; top: 122px; position: absolute; background: #29F94A; border-radius: 5px"></div>
            <div style="width: 79px; height: 15px; left: 229px; top: 135px; position: absolute; text-align: center; color: white; font-size: 18px; font-family: Inter; font-weight: 400; word-wrap: break-word">User</div>
            <div style="width: 215px; height: 31px; left: 28px; top: 241px; position: absolute; text-align: center; color: black; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">Registration Form</div>
        </div>
    </div>
</body>
</html>
```

## OUTPUT:
![Screenshot 2024-05-10 172213](https://github.com/Sabari-2005/Figma/assets/139338709/0707a00b-8906-43fd-8f04-749f83fa5050)



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.

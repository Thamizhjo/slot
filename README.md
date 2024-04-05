
































# Ex03 Time Table
## Date:

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>Saveetha Engineering college</title>
        <style>
            img {
    text-align: center;
    width: 40em;
}
table,th,td {
    border: 2px;
    border-style: solid;
}
.head{
    background-color: #1532ec;  
}
.data{
    text-align: center;
    background-color: #f27908;
}
table,img{
    margin: 20px;
}
.cont{
    background-color: rgb(225, 79, 11);
}
        </style>
    </head>
    <body>
        <center>
            <img src="C:\Users\admin\slot-1\logo.png" alt="Saveetha">
            <h1 style="font-family: cursive; font-size: 15px;"> Thamizhkumaran PS (212223240166)</h1>
            <table>
                <tr>
                    <th class="head">Day&time</th>
                    <th class="head">Monday</th>
                    <th class="head">Tuesday</th>
                    <th class="head">Wednesday</th>
                    <th class="head">Thursday</th>
                    <th class="head">Friday</th>
                    <th class="head">Saturday</th>
                </tr>
                <tr>
                    <th class="head">8-10</th>
                    <td class="data">FWA</td>
                    <td class="data">T&A</td>
                    <td class="data">Beee</td>
                    <td class="data">SE</td>
                    <td class="data">FREE</td>
                    <td class="data">Csfc</td>
                </tr>
                <tr>
                    <th class="head">10-12</th>
                    <td class="data">FREE</td>
                    <td class="data">SE</td>
                    <td class="data">FREE</td>
                    <td class="data">T&A</td>
                    <td class="data">EDM</td>
                    <td class="data">FREE</td>
                </tr>
                <tr>
                    <th class="head">12-1</th>
                    <td class="data" colspan="6">LUNCH BREAK</td>
                </tr>
                <tr>
                    <th class="head">1-3</th>
                    <td class="data">Beee</td>
                    <td class="data">FREE</td>
                    <td class="data">CE</td>
                    <td class="data">FWA</td>
                    <td class="data">FWA</td>
                    <td class="data">FREE</td>
                </tr>
                <tr>
                    <th class="head">3-5</th>
                    <td class="data">FREE</td>
                    <td class="data">FREE</td>
                    <td class="data">FREE</td>
                    <td class="data">EDM</td>
                    <td class="data">CE</td>
                    <td class="data">FREE</td>
                </tr>
            </table>
            <table class="cont">
                <tr>
                    <th>S.No</th>
                    <th>Subject Code</th>
                    <th>Subject Name</th>
                </tr>
                <tr>
                    <tr>
                        <td>1.</td>
                        <td>19AI305</td>
                        <td style="color: rgb(56, 5, 5);border-color: rgb(195, 17, 159);">Advanced C Programming(Adv C)</td>
                    </tr>
                    <tr>
                        <td>2.</td>
                        <td>19AI414</td>
                        <td>Fundamentals of web Application(FWA)</td>
                    </tr>
                    <tr>
                        <td>3.</td>
                        <td>19CS405</td>
                        <td>Operating System(OS)</td>
                    </tr>
                    <tr>
                        <td>4.</td>
                        <td>19EY702</td>
                        <td>Creative Skill(CS)</td>
                    </tr>
                    <tr>
                        <td>5.</td>
                        <td>19MA211</td>
                        <td>Statics and Numerical Methods(S&N)</td>
                    </tr>
                    <tr>
                        <td>6.</td>
                        <td>19MA219</td>
                        <td>Transfroms and its applications(T&A)</td>
                    </tr>
                    <tr>
                        <td>7.</td>
                        <td>19MS155</td>
                        <td>Stock Market and Company Operations(STOCK)</td>
                    </tr>
                    <tr>
                        <td>8.</td>
                        <td>19PH214</td>
                        <td>Physics for Quantum Computing(PHY)</td>
                    </tr>
                </tr>
            </table>
        </center>
    </body>
</html>
```


## OUTPUT
![Screenshot 2024-04-05 190437](https://github.com/Thamizhjo/slot/assets/123891476/f7504982-0225-4365-94f8-2d99587dd55a)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

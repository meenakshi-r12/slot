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
<body>
    <img src="logo.png" height="200px" width="200px"/>
    <h4>SLOT TIMETABLE-MEENAKSHI.R(24003710)</h4>
    <table border="5">
        <tr>
            <td style="background-color: yellow;">Day/Time</td>
              <td style="background-color: yellow;">Monday</td> 
               <td style="background-color: yellow;">TuesDay</td>
               <td style="background-color: yellow;">Wednesday</td>
               <td style="background-color: yellow;">Thursday</td>
               <td style="background-color: yellow;">Friday</td>
            </td>
        </tr>
        <tr>
            <td style="background-color: yellow;">8-10</td>
            <td colspan="3" style="background-color: aqua;"><center>Freeslot</center></td>
            <td style="background-color: aqua;">phy</td>
            <td style="background-color: aqua;">che</td>
        </tr>
        <tr>
            <td style="background-color: yellow;">10-12</td>
            <td style="background-color: aqua;">ger</td>
            <td style="background-color: aqua;">freeslot</td>
            <td style="background-color: aqua;">fwad</td>
            <td style="background-color: aqua;">fwad</td>
            <td style="background-color: aqua;">phy</td>
        </tr>
        <tr>
            <td style="background-color: yellow;">12-1</td>
            <td colspan="5" style="background-color: aqua;"><center>lunch</center></td>

        </tr>
        <tr>
            <td style="background-color: yellow;">1-3</td>
            <td colspan="2" style="background-color: aqua;">freeslot</td>
            <td style="background-color: aqua;">mat</td>
            <td style="background-color: aqua;">mat</td>
            <td style="background-color: aqua;">ss</td>
        </tr>
        <tr>
            <td style="background-color:yellow;">3-5</td>
            <td colspan="2" style="background-color: aqua;">freeslot</td>
            <td style="background-color: aqua;">ger</td>
            <td style="background-color: aqua;">che</td>
            <td style="background-color: aqua;">fwad</td>
        </tr>
        

    </table>



    <table>
        <table border="5">
        <tr>
            <td>S.no</td>
            <td>Subject code</td>
            <td>subject name</td>
        </tr>
        <tr>
            <td>1</td>
            <td>19ai414</td>
            <td>fwad</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19en612</td>
            <td>ger</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19ph206</td>
            <td>phy</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19cy205</td>
            <td>che</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19ma201</td>
            <td>calculas</td>
        </tr>
        <tr>
                <td>6</td>
                <td>19ey701</td>
                <td>ss</td>
        </tr>
    </table>
</body>

## OUTPUT


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

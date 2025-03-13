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
<!DOCTYPE html>
<html lang="en"
<head>
    <title> Slot time table</title>
</head>
<body>
    <br>
    <center><h3>SLOT TIME TABLE- Vedagiri Indu Sree (212223230236)</h3></center>
    <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
    <tr align="center">
        <th bgcolor="Blue">Day time</th>
        <th bgcolor="Blue">Monday</th>
        <th bgcolor="Blue">Tuesday</th>
        <th bgcolor="Blue">Wednesday</th>
        <th bgcolor="Blue">Thursday</th>
        <th bgcolor="Blue">friday</th>
    </tr>
    <tr align="center">
        <th bgcolor="yellow"> 8-10</th>
        <td colspan="3"> Free slot</td>
        <td>Physics</td>
        <td>Chemistry</td>
    </tr>
    <tr align="center">
    <th bgcolor="yellow">10-12 </th>
    <td>Ger</td>
    <td>Free Slot</td>
    <td>Fwad</td>
    <td>Fwad</td>
    <td>Phy</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">12-1</th>
        <td colspan="5">Lunch</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">1-3</th>
        <td colspan="2">Free slot</td>
        <td>Mat</td>
        <td>Mat</td>
        <td>SS</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">3-5</th>
        <td colspan="2">free slot</td>
        <td>Ger</td>
        <td>Che</td>
        <td>Fwad</td>
    </tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="5">
    <tr align="center">
        <th>S.No.</th>
        <th>Subject code</th>
        <th>Subject Name</th>
    </tr>
    <tr align="center">
        <th>1.</th>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr align="center">
    <th>2.</th>
    <td>19EN612</td>
    <td>German Basic (Ger)</td>
    </tr>
    <tr align="center">
        <th>3.</th>
        <td>19PH206</td>
        <td>Physics for Information Technology (PHY)</td>
        </tr>
        <tr align="center">
            <th>4.</th>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering (CHE)</td>
            </tr>
             <tr align="center">
                <th>4.</th>
                <td>19MA201</td>
                <td>Statistics and Numerical Methods (Mat)</td>
                </tr>
                <tr align="center">
                    <th>5.</th>
                    <td>19EY701</td>
                    <td>Soft Skills (SS)</td>
                    </tr>

</table>
</body>
</html>


## OUTPUT
![image](https://github.com/user-attachments/assets/8aebd1cb-6764-4432-9516-2e4699f798a6)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

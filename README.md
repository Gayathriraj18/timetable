# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
~~~<!DOCTYPE html>
<html>

   <head>
      <title>TIME TABLE</title>
   </head>
	
   <body>
      <table border = "1" cellspacing="1" bordercolor="blue" bgcolor="yellow">
         <tr>
            <th colspan="8">TIME TABLE</th>
         </tr>
         
         <tr>
            <th>DAYS</th>
            <th>1</th>
            <th>2</th>
            <th>3</th>
             <th>4</th>
            <th rowspan="6">lunch break</th>
            <th>5</th>
            <th>6</th>
         </tr>
          <tr>
             <td>MONDAY</td>
             <td>19EY701/SnehaPriya</td>
             <td></td>
             <td>19AI301C/JabaJasphin</td>
             <td></td>
             <td align="center">19AI301C/JabaJasphin</td>
             <td align="center"></td>
         </tr>
         <tr>
             <td>TUESDAY</td>
             <td>19AI402/KarthiGovindharaju</td>
             <td></td>
             <td>19AI302C/Ram.G.R</td>
             <td></td>
             <td align="center">19AI301C/Ram.G.R</td>
             <td align="center"></td>
         </tr>
         <tr>
             <td>WEDNESDAY</td>
             <td>19AI402/KartthiGovindharaju</td>
             <td></td>
             <td>19AI301C/JabaJasphin</td>
             <td></td>
             <td align="center">-</td>
             <td align="center">-</td>
         </tr>
         <tr>
             <td>THURSDAY</td>
             <td>19AI302C/Ram.G.R</td>
             <td>-</td>
             <td>19AI301C/JabaJasphin</td>
             <td></td>
             <td align="center">19AI301C/Ram.G.R</td>
             <td align="center"></td>
         </tr>
         <tr>
             <td>FRIDAY</td>
             <td>19AI402C/KarthiGovindharaju</td>
             <td></td>
             <td>19AI302C/JabaJasphin</td>
             <td></td>
             <td align="center">-</td>
             <td align="center">-</td>
         </tr>
      </table>
      
   </body>
</html>


~~~
# OUTPUT
![GitHub Logo](/logo.png)
![GitHub Logo](.//Timetable.png)

# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<title>Javascript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=91)&&(percentage<=100))
{
    alert("O Grade");
}
else if((percentage>=81)&&(percentage<=90))
{
    alert("A+ Grade");
}
else if((percentage>=71)&&(percentage<=80))
{
    alert("A Grade");
}
else if((percentage>=61)&&(percentage<=70))
{
    alert("B+ Grade");
}
else if((percentage>=51)&&(percentage<=60))
{
    alert("B Grade");
}
else
{
    alert("RA Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
```
## OUTPUT

![webassignment62](https://github.com/Soundaryaveeran906/Ex06_Web-Design/assets/127818071/e7c16276-83e2-448d-867c-d3a75e62ea4b)
![webassignment63](https://github.com/Soundaryaveeran906/Ex06_Web-Design/assets/127818071/ab4d95a9-313d-4ed9-b67a-0eaa13a998b0)
![webassignment64](https://github.com/Soundaryaveeran906/Ex06_Web-Design/assets/127818071/78bfa23d-dd4e-4d04-996c-4f0569c3a548)
![webassignment65](https://github.com/Soundaryaveeran906/Ex06_Web-Design/assets/127818071/cb0285e0-415f-4dbc-a43a-9775a20e5edc)
![webassignment66](https://github.com/Soundaryaveeran906/Ex06_Web-Design/assets/127818071/2dfe9d3f-f935-4655-bd1e-c9eda75bfacb)
![webassignment67](https://github.com/Soundaryaveeran906/Ex06_Web-Design/assets/127818071/d226406e-91d5-40c9-b1c3-b2c569b36465)


## RESULT
  Student result using JavaScript is created successfully.

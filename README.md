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
##OUTPUT
![Screenshot (82)](https://github.com/BakkiyalakshmiPavadai/Ex06_Web-Design/assets/127816647/de21a147-e7fc-40de-9dc2-09b850fc9a23)
![Screenshot (83)](https://github.com/BakkiyalakshmiPavadai/Ex06_Web-Design/assets/127816647/8d4affb8-a201-46a4-8da4-685e6ce0a3c8)
![Screenshot (84)](https://github.com/BakkiyalakshmiPavadai/Ex06_Web-Design/assets/127816647/0e1ba8c8-4380-4bdc-9d96-d2464ed9e55d)
![Screenshot (85)](https://github.com/BakkiyalakshmiPavadai/Ex06_Web-Design/assets/127816647/6f8dc89d-35fc-4544-9a5b-07b28acef3eb)
![Screenshot (86)](https://github.com/BakkiyalakshmiPavadai/Ex06_Web-Design/assets/127816647/7ed13f36-a8d1-4d89-a9d1-fd01f14f9fd1)
![Screenshot (87)](https://github.com/BakkiyalakshmiPavadai/Ex06_Web-Design/assets/127816647/b7df591c-2f89-4fc1-89a6-4ba5b9193fd1)
## RESULT!
 Student result using JavaScript is created successfully.

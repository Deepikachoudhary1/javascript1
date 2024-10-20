# javascript1

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JS-Task1</title>
    <style>
        body{
            margin: 20px 600px;
            border: 5px groove blue;
        }
        span{
            color: red;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <script>
        var num=10
if (num>0){
    console.log("Positive")
    if(num%2==0){
        console.log("even")
    }else{
        console.log("odd")
    }
}
else if(num<0){
    console.log("Negative")
}
else{
    console.log("0")
}

//Code2:- add two number only even 

var n1=6
var n2=4
if (n1%2==0 && n2%2==0){
    console.log(n1+n2)
}
else{
    console.log("Not valid")
}

// code3:- num multiples table 

var n=5
var i=1
for (i=1; i<=10;i++){
    console.log(n+"*"+i+"="+n*i)
}
    </script>
    <center>
    <p><span>Code1</span>:-check nuber is +ve,-ve and zero. <br>if +ve then check even or odd
    </p>
    <p><span>o/p</span>:- positive even</p><hr>
    <p><span>Code2</span>:- Add two numbers if only both are numbers.</p>
    <p><span>o/p</span>:- 10</p><hr>
    <p><span>Code3</span>:- multiplication table for that number from 1-10 using loops</p>
    <pre><span>o/p</span>:- 5*1=5 <br>      5*2=10 <br>      5*3=15 <br>      5*4=20 ......
    </pre></center>
    <script src="./js_task1.js"></script>
</body>
</html>

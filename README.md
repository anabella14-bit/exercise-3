
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale-1.0">
    <title>Calculator</title>
    <link rel="stylesheet" href="style.css">
    
    <style>  
    body {
    background:#98AFC7;

}
        *{
            box-sizing:border-box;
            -webkit-box-sizing:border-box;
            -moz-box-sizing:border-box;

        }
    
        input[type=button]{
            background-color: lightskyblue;
            color: white;
            width: 63px;
            padding: 5px;
            font-size: 22px;
            border-radius: 5px;
            border-color: black;
            
        }
        
        .wrap{

            width:300px;
            margin:auto;
            height:400px;
            background:gray;
            border: 3px solid black;
            padding:10px;
            border-radius: 20px;

        }
        
        input[type=text]{

            background-color:lightsteelblue;
            width:100%;
            padding:5px;
            font-size:22px;
            margin-top:20px;
            border-radius:5px;
            border-color: black;

        }
        
        input[type=button]{

            background-color: skyblue;
            color: white;
            width:63px;
            padding:5px;
            font-size:22px;
            border-radius:5px;
            border-color: black;

        }

        .del{
        width: 48%;
        background-color: green;
    
        }

        .input:hover{
        color: darkgreen;
        background-color: aqua;
   
        }

    </style>

</head>
    
<body>
    <div class="wrap">
        <form name ="cal">
            <input type="text" name ="display" readonly>
            <br><br>
            
            <input type="button" value ="AC" onclick ="cal.display.value+=''" id="del">
            <input type="button" value ="DEL" onclick ="cal.display.value=''" id="del">
            <input type="button" value ="%" onclick ="cal.display.value+='%'">
            <input type="button" value=" √ " onclick="sq()">

            <br><br>
            
            <input type="button" value ="7" onclick ="cal.display.value+='7'">
            <input type="button" value ="8" onclick ="cal.display.value+='8'">
            <input type="button" value ="9" onclick ="cal.display.value+='9'">
            <input type="button" value ="*" onclick ="cal.display.value+='*'">
            
            <br><br>
            
            <input type="button" value ="4" onclick ="cal.display.value+='4'">
            <input type="button" value ="5" onclick ="cal.display.value+='5'">
            <input type="button" value ="6" onclick ="cal.display.value+='6'">
            <input type="button" value ="-" onclick ="cal.display.value+='-'">

            <br><br>

            <input type="button" value ="1" onclick ="cal.display.value+='1'">
            <input type="button" value ="2" onclick ="cal.display.value+='2'">
            <input type="button" value ="3" onclick ="cal.display.value+='3'">
            <input type="button" value ="+" onclick ="cal.display.value+='+'">

            <br><br>
            
            <input type="button" value ="00" onclick ="cal.display.value+='00'">
            <input type="button" value ="0" onclick ="cal.display.value+='0'">
            <input type="button" value ="." onclick ="cal.display.value+='.'">
            <input type="button" value ="=" onclick ="cal.display.value =eval(cal.display.value)">

            <br><br>
         
            
      
            

        </form>
  

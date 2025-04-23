<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>calculator</title>
    <style>
       

        .container{
            width: 100%;
            height: 100vh;
            background: #e3f9ff;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .calculator{
            background: black;
            padding: 20px;
            border-radius: 10px;
            height: 400px;
            width: 300px;
            align-content: center;
        }

        .calculator form input{
            border: 50px;
            outline: 50px;
            width: 60px;
            height: 60px;
            border-radius: 10px;
            background: transparent;
            font-size: 40px;
            font-weight: bolder;
            color: black;
            cursor: pointer;
            margin: 1px ;
            background: #e3f9ff;
            align-content: center;
            margin-right: 10px;
            
        }
        
        form .display{
            display: flex;
            justify-content: flex-end;
            margin: 20px 0;
            border-radius: 10px;
            
        }

        form .display input{
        text-align: right;
        flex: 1;
        font-size: 40px;
        }

        .btn :hover{
            color: red;
            transition: 0.5 ease-in-out;  
            }

       

    </style>
</head>
<body>
    <h1><u><center>MY CALCULATOR</center></u></h1>
    <div class="container">
        <div class="calculator">
            <form>
                <div class="display">
                    <input type="text" name="display">
                </div>
                <div class="btn">
                    <div>
                        <input type="button" value="7" onclick="display.value ='7' ">
                        <input type="button" value="8" onclick="display.value ='8' ">
                        <input type="button" value="9" onclick="display.value ='9' ">
                        <input type="button" value="/" onclick="display.value ='/' ">
                    </div>
    
                    <div>
                        <input type="button" value="4" onclick="display.value ='4' ">
                        <input type="button" value="5" onclick="display.value ='5' ">
                        <input type="button" value="6" onclick="display.value ='6' ">
                        <input type="button" value="*" onclick="display.value ='*' ">
                    </div>
    
                    <div>
                        <input type="button" value="1" onclick="display.value ='1' ">
                        <input type="button" value="2" onclick="display.value ='2' ">
                        <input type="button" value="3" onclick="display.value ='3' ">
                        <input type="button" value="-" onclick="display.value ='-' ">
                    </div>
    
                    <div>
                        <input type="button" value="c" onclick="display.value ='c' ">
                        <input type="button" value="." onclick="display.value ='.' ">
                        <input type="button" value="+" onclick="display.value ='+' ">
                        <input type="button" value="=" onclick="display.value ='=' ">
                    </div>
                </div>
               
            </form>
                
        </div>
        
    </div>

    <script>
        
    </script>
</body>
</html>

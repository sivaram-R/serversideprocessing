# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:
### Step 1: 
Clone the repository from GitHub
### Step 2:
Create Django Admin project.
### Step 3:
Create a New App.
### Step 4: 
Create python programs for views and urls.
### Step 5: 
Create a HTML file of forms.
### Step 6:
Publish the website in the given URL


## PROGRAM :
```

<html>
    <head>
        
        <Title>Calculate area of rectangle</Title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style>
        body{background-color:black}
        }
        .edge{
            width:1080px;
            margin-left:auto;
            margin-right: auto;
            padding-top: 500px;
            padding-left: 300px;
        }
        .box{
            display: block;
            border: thick yellow;
            width:500px;
            min-height: 300px;
            font-size: 20px;
            background-color: purple;
            text-align:center;
            margin-left:200px;
            margin-right:100px;
        }
        .formelt{
            color:yellow;
            text-align: center;
            margin-top: 5px;
            margin-bottom: 5px;
        }
        .h1{
            color:red;
            text-align: center;
            padding-top: 20px;
        }

        </style>

    </head>
    <body>
        
        <div class="edge">
            <div class="box">
                <h1>Area of Rectangle</h1>
                <form method="POST">
                {% csrf_token%}
                <div class="formelt">
                    Length: <input type="text" name="length" value="{{l}}"></input>(in m)<br/>
                </div>
                <div class="formelt">
                    Breadth: <input type="text" name="breadth" value="{{b}}"></input>(in m)<br/>
                </div>
                <div class="formelt">
                    <input type="submit" value="Calculate"></input><br/>
                </div>
                <div class="formelt">
                    Area: <input type="text" name="area" value="{{area}}"></input>m<sup>2</sup><br/>
                </div>
                </form>
            </div>

        </div>
        
    </body>
</html>
```
## OUTPUT:
![2023-05-15 (1)](https://github.com/sivaram-R/serversideprocessing/assets/121165794/298d16bc-ca35-4dc1-af2d-356629ff3f90)

## Result:
area calculator for rectangle was got .

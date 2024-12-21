# Ex.05 Design a Website for Server Side Processing
## Date:

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
P = I<sup>2</sup>R
<br> P --> Power (in watts)
<br> I --> Intensity
<br> R --> Resistance

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Area of Surface</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body {
    background-color: rgb(3, 41, 60);
}
.edge {
    width: 100%;
    padding-top: 250px;
    text-align: center;
}
.box {
    display: inline-block;
    border: thick dashed rgb(53, 48, 53);
    width: 500px;
    min-height: 300px;
    font-size: 20px;
    background-color: rgb(100, 193, 221);
}
.formelt {
    color: rgb(22, 20, 20);
    text-align: center;
    margin-top: 7px;
    margin-bottom: 6px;
}
h1 {
    color: rgb(200, 61, 91);
    padding-top: 20px;
}
</style>
</head>
<body>
<div class="edge">
    <div class="box">
        <h1>Area of Surface</h1>
        <h3>Samritha R (24013637)</h3>
        <form method="POST">
            {% csrf_token %}
            <div class="formelt">
                Radius: <input type="text" name="radius" value="{{r}}">m<br/>
            </div>
            <div class="formelt">
                Height: <input type="text" name="height" value="{{h}}">m<br/>
            </div>
            <div class="formelt">
                <input type="submit" value="Calculate"><br/>
            </div>
            <div class="formelt">
                Area: <input type="text" name="area" value="{{area}}">m<sup>2</sup><br/>
            </div>
        </form>
    </div>
</div>
</body>
</html>
```

## SERVER SIDE PROCESSING:
![Screenshot 2024-12-21 155905](https://github.com/user-attachments/assets/0cd888b8-44ef-4bbc-90df-a96807152619)



## HOMEPAGE:
![server-1](https://github.com/user-attachments/assets/27249bc9-8146-4d9c-9b55-0774e4bfbf1f)



## RESULT:
The program for performing server side processing is completed successfully.

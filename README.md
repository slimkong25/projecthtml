<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .main{
            display: grid;
            grid-template-columns: 10cm 19cm 10cm;
            grid-template-rows: 1.5cm 15cm 1.5cm;
            gap: 20px;
            /* border-color: black; */
        }
        .d1{
            background-color: yellow;
            grid: 1/2;
            padding: 20px;
            text-align: center;
        }
        .d2{
            background-color: aqua;
            padding: 20px;
            grid-column: 2/4;
            text-align: center;
        }
        .d3{
            background-color: aquamarine;
            grid-column: 1/3;
            padding: 20px;
            text-align: center;
        }
        .d4{
            background-color: blue;
            padding: 20px;
            text-align: center;
        }
        .d5{
            background-color: blueviolet;
            grid-column: 1/4;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="main">
        <div class="d1">Header</div>
        <div class="d2">Navigation</div>
        <div class="d3">main </div>
        <div class="d4">sidebar</div>
        <div class="d5">footer</div>
    </div>
    
    
    
    
</body>
</html>

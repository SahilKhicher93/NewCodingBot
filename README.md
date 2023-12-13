<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width , initial-scale=1.0">
    <title>CSS grid 2</title>
</head>
<style>

    .grid-container{
        display: grid;
        grid-template-columns: auto auto auto;
        background-color: aqua;
        padding: 10px;
        grid-template-areas: "b a a" "b c c";

    }
    .grid-item{
        background-color: silver;
        padding: 20px;
        border: 1px solid red;
        font-size: 30px;
        text-align: center;
    }
    #item1{
        grid-area: a;
    }
    #item2{
        grid-area: b;
    }
    #item3{
        grid-area: c;
    }
</style>
<body>
    <div class="grid-container"
        <div class="grid-item" id="item1">1</div>
        <div class="grid-item" id="item2">2</div>
        <div class="grid-item" id="item3">3</div>

</body>
</html>

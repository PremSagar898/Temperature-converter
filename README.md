# Temperature-converter
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Temperature Converter</title>
    <link rel="stylesheet" href="temp.css">
</head>
<body>
    <div class="container">
        <div class="title">
            <h1>PREM Temperature Converter</h1>
            <span class="Temperaure-icon"><i class="fa-solid fa-temperature-three-quarters"></i></i></span>
        </div>
    <br>
    <label><h4>Tempurature</h4></label><br>
    <input type="text" name="temp" id="temp" placeholder="Enter only number" value=""><br>
    <br><label><h4>Given Tempurature format</h4></label><br>
    <select name="kind" id="kind">
        <option>Select one of below</option>
        <option value="celsius">Celsius </option>
        <option value="fahrenheit">Fahrenheit </option>
        <option value="kelvin">Kelvin </option>
    </select><br>
    <br><input type="button" value="Convert" id="convert" onclick="TemperatureConverter()">
    <div id="result"></div>
    <script src="temp.js"></script>
</body>
</html>

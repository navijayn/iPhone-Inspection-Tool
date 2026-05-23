<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>iPhone Checker</title>

<style>
body{
    font-family: Arial;
    background:#0f172a;
    color:white;
    padding:20px;
}
.container{max-width:800px;margin:auto;}

.card{
    background:#1e293b;
    padding:20px;
    border-radius:16px;
    margin-bottom:15px;
}

select,input{
    width:100%;
    padding:10px;
    border-radius:10px;
    margin-top:10px;
}

.check{
    margin:8px 0;
}

button{
    width:100%;
    padding:15px;
    border:none;
    border-radius:12px;
    background:#2563eb;
    color:white;
    font-size:18px;
}

.result{
    margin-top:20px;
    padding:20px;
    border-radius:12px;
    text-align:center;
    font-size:22px;
}

.safe{background:#166534;}
.mid{background:#a16207;}
.bad{background:#991b1b;}
</style>
</head>

<body>

<div class="container">

<h1>📱 iPhone Inspection Tool</h1>

<div class="card">
<h2>Device Info</h2>

<select id="model">
<option>iPhone 11</option>
<option>iPhone 12</option>
<option>iPhone 13</option>
<option>iPhone 14</option>
<option>iPhone 15</option>
<option>iPhone 16</option>
</select>

<select id="storage">
<option>64GB</option>
<option>128GB</option>
<option>256GB</option>
<option>512GB</option>
<option>1TB</option>
</select>

<input type="number" id="battery" placeholder="Battery Health % (0-100)">
</div>

<div class="card">
<h2>Basic Checks</h2>
<div class="check"><input type="checkbox" class="good"> iCloud OFF</div>
<div class="check"><input type="checkbox" class="good"> Find My OFF</div>
<div class="check"><input type="checkbox" class="good"> No physical damage</div>
</div>

<div class="card">
<h2>Panic / Restart</h2>
<div class="check"><input type="checkbox" class="good"> No restart issue</div>
<div class="check"><input type="checkbox" class="bad"> Panic logs found</div>
<div class="check"><input type="checkbox" class="bad"> Overheating restart</div>
</div>

<div class="card">
<h2>Camera / Face ID</h2>
<div class="check"><input type="checkbox" class="good"> Face ID OK</div>
<div class="check"><input type="checkbox" class="good"> Cameras OK</div>
<div class="check"><input type="checkbox" class="bad"> Camera issue</div>
</div>

<div class="card">
<h2>Network</h2>
<div class="check"><input type="checkbox" class="good"> Signal OK</div>
<div class="check"><input type="checkbox" class="bad"> No Service issue</div>
</div>

<button onclick="checkPhone()">Analyze</button>

<div id="result"></div>

</div>

<script>
function checkPhone(){

let score = 100;

let battery = document.getElementById("battery").value;
if(battery){
    score -= (100 - battery);
}

// good checks
document.querySelectorAll(".good").forEach(i=>{
    if(!i.checked) score -= 5;
});

// bad checks
document.querySelectorAll(".bad").forEach(i=>{
    if(i.checked) score -= 20;
});

if(score < 0) score = 0;

let cls = "";
let text = "";

if(score >= 85){
    cls = "safe";
    text = "SAFE TO BUY ✅";
}
else if(score >= 60){
    cls = "mid";
    text = "BUY WITH CAUTION ⚠️";
}
else{
    cls = "bad";
    text = "AVOID ❌";
}

document.getElementById("result").innerHTML = `
<div class="result ${cls}">
${score}/100 <br><br>
${text}
</div>
`;

}
</script>

</body>
</html>
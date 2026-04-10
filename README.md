<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
  <title>번호 추첨기</title>
  <style>
    body { text-align:center; font-family:sans-serif; }
    button { font-size:20px; padding:10px 20px; }
    #result { font-size:40px; margin-top:20px; }
  </style>
</head>
<body>

<h1>번호 추첨기 🎲</h1>

<button onclick="draw()">추첨!</button>

<div id="result">?</div>

<script>
function draw() {
  let num = Math.floor(Math.random() * 10) + 1;
  document.getElementById("result").innerText = num;
}
</script>

</body>
</html>

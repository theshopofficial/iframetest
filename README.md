<html>
<head>
</head>
<body>
<button onclick="openGame()">Open iFrame</button>
<script>
function openGame() {
var win = window.open()
var url = "https://sites.google.com/view/games-unblockedd"
var iframe = win.document.createElement('iframe')
iframe.style.width = "100%";
iframe.style.height= "100%";
iframe.style.border = "none";
iframe.src = url
win.document.body.appendChild(iframe)
}
</script>
</body>
</html>

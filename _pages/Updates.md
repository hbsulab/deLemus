---
layout: page
title: Update
nav: true
nav_order: 2
---
<h4>The identified leading mutations in 2023 are listed as follows:<h4>
<hr>

<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script>
$(document).ready(function(){
  $(".flip").click(function(){
    $(this).next(".panel").slideToggle("slow");
  });
});
</script>
<style> 
.panel, .flip {
  padding: 5px;
  text-align: center;
  background-color: #f2e1ef;
  border: solid 1px #f2e1ef;
}

.panel {
  padding: 50px;
  display: none;
}
</style>
</head>
<body>
 
<div class="flip">2023.08</div>
<div class="panel">2023.08</div>
<hr>
<div class="flip">2023.07</div>
<div class="panel">2023.07</div>
<hr>
<div class="flip">2023.06</div>
<div class="panel">2023.06</div>

</body>
</html>
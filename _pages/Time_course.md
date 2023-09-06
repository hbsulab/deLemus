---
layout: page
title: Time Course
permalink: /Time Course/
nav: true
nav_order: 3
---

<style>
    @media (min-width: 576px) {
        .profile {
            width: 30%;
        }
        .profile .address p {
            display: block;
        }
    }
</style>

<html>
<head>
<style> 
h5 {
  line-height: 1.6;
}
</style>
</head>
<body>

<h5>Within the first 2 years of this pandemic, the World Health Organization (WHO) has already announced 4 variants of concern (VOC), which are the previously circulating α (B.1.1.7), β (B.1.351), γ (P.1), and δ (B.1.617.2) strains, and many other variants of interest (VOI).The successive emergence of new SARS-CoV-2 variants has brought along many novel mutations. Between July and October 2022, 3 new members of the omicron (B.1.1.529) lineage have emerged, and subsequently been recognized as variants of interest (VOI) by the World Health Organization (WHO), which are the BA.2.75, XBB, and BQ.1 subvariants.[2] Each of these VOIs has brought along an array of novel mutations in the constantly evolution of SARS-CoV-2. The time course analysis of identified leading mutations are presented here.</h5>

</body>
</html>
<br>


<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script>
$(document).ready(function(){
  $(".panel").hide();
  // Show latest panel
  $("#panel-202307").show();
  $("#dateSelect").change(function(){
    $(".panel").hide();
    var selected = $(this).val();
    $("#panel-"+selected.replace('.', '')).show();
  });
});
</script>
<style> 
.panel {
  padding: 50px;
  text-align: left;
  background-color: #f2e9f0;
  border: solid 1px #f2e9f0;
}
</style>
</head>
<body>
 
<select id="dateSelect">
  <option value="">--Select Month--</option>
  <option value="2023.07">2023.07</option>
  <option value="2023.06">2023.06</option>
  <option value="2023.05">2023.05</option>
  <option value="2023.04">2023.04</option>
  <option value="2023.03">2023.03</option>
  <option value="2023.02">2023.02</option>
  <option value="2023.01">2023.01</option>
  <option value="2022.08">2022.08</option>
  <option value="2022.06">2022.06</option>
  <option value="2021.08">2021.08</option>
  <option value="2021.03">2021.03</option>
  <option value="2021.03">2020.12</option>
  <option value="2021.03">2020.11</option>
  <option value="2021.03">2020.10</option>
</select>

<div id="panel-202307" class="panel">
  <h4><strong>NTD</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC0202307/2023-07a.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <h4><strong>RBD</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC0202307/2023-07b.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <h4><strong>Other Domains</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC0202307/2023-07c.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <div align="right">
    <p><h5>Click<a href="#"> here </a>to top.</h5></p>
  </div>
</div>

<div id="panel-202306" class="panel">
  <h4><strong>NTD</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202306/2023-06a.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <h4><strong>RBD</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202306/2023-06b.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <h4><strong>Other Domains</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202306/2023-06c.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <div align="right">
    <p><h5>Click<a href="#"> here </a>to top.</h5></p>
  </div>
</div>

<div id="panel-202305" class="panel">
  <h4><strong>NTD</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202305/2023-05a.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <h4><strong>RBD</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202305/2023-05b.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <h4><strong>Other Domains</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202305/2023-05c.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <div align="right">
    <p><h5>Click<a href="#"> here </a>to top.</h5></p>
  </div>
</div>

<div id="panel-202304" class="panel">
  <h4><strong>NTD</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202304/2023-04a.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <h4><strong>RBD</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202304/2023-04b.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <h4><strong>Other Domains</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202304/2023-04c.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <div align="right">
    <p><h5>Click<a href="#"> here </a>to top.</h5></p>
  </div>
</div>

<div id="panel-202303" class="panel">
  <h4><strong>NTD</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202303/2023-03a.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <h4><strong>RBD</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202303/2023-03b.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <h4><strong>Other Domains</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202303/2023-03c.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <div align="right">
    <p><h5>Click<a href="#"> here </a>to top.</h5></p>
  </div>
</div>

<div id="panel-202302" class="panel">
  <h4><strong>NTD</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202302/2023-02a.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <h4><strong>RBD</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202302/2023-02b.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <h4><strong>Other Domains</strong></h4>
  <hr>
  {% include figure.html path="assets/img/TC202302/2023-02c.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <div align="right">
    <p><h5>Click<a href="#"> here </a>to top.</h5></p>
  </div>
</div>

<div id="panel-202301" class="panel">
2023.03
</div>

</body>
</html>
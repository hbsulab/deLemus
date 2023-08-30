---
layout: page
title: Time Course
permalink: /Time Course/
nav: true
nav_order: 3
---

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
  $("#panel-202308").show();

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
  <option value="2023.08">2023.08</option>
  <option value="2023.07">2023.07</option>
  <option value="2023.06">2023.06</option>
</select>

<div id="panel-202308" class="panel">
  <h4><strong>Outlined Mutation in 2023.08</strong></h4>
  <hr>
  <img src="{{'assets/img/update_2308/2023-08.png' | relative_url}}" alt="2023-08" style="width: 1100px; height: 200px;">
  <br>
  <br>
  <strong>2023.08.04 - 2023.08.22</strong>
  <hr>
  <img src="{{'assets/img/update_2308/confirmed mutations.png' | relative_url}}" alt="Confirmed mutations" style="width: 600px; height: 300px;">
  <br>
  <br>
  <strong>RBD Mutation Profile of Latest VOIs.</strong>
  <hr>
  <img src="{{'assets/img/update_2308/2023-08_VarRBD.png' | relative_url}}" alt="RBD profile" style="width: 700px; height: 300px;">
  <br>
  <br>
  <strong>3D structure illustration</strong>
  <hr>

    <div class="l-page">
    <style>
        .molstar {
            position: relative;
            padding-bottom: 60%;
        }
    </style>
    <link rel="stylesheet" type="text/css" href="https://molstar.org/viewer/molstar.css" />
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>

    <div id="viewer-1" class="molstar" style="display: block; margin-left:auto; margin-right:auto; padding-bottom: 60%;"></div>
    <script type="text/javascript">
        molstar.Viewer.create('viewer-1', {
            layoutIsExpanded: false,
            layoutShowControls: false,
            layoutShowRemoteState: false,
            layoutShowSequence: true,
            layoutShowLog: false,
            layoutShowLeftPanel: true,

            viewportShowExpand: true,
            viewportShowSelectionMode: false,
            viewportShowAnimation: false,
        }).then(viewer => {
            viewer.loadSnapshotFromUrl("{{ 'assets/img/update_2308/LM_2023_08.molx' | relative_url }}", 'molx');
        });
    </script>
</div>
</div>

<div id="panel-202307" class="panel">
2023.07
</div>

<div id="panel-202306" class="panel">
2023.06
</div>

</body>
</html>
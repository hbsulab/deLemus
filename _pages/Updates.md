---
layout: page
title: Updates
permalink: /Updates/
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
  background-color: #f2e9f0;
  border: solid 1px #f2e9f0;
}

.panel {
  padding: 50px;
  display: none;
  text-align: left;
}
</style>
</head>
<body>
 
<div class="flip"><strong>2023.08</strong></div>
<div class="panel">
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
<hr>

<div class="flip">2023.07</div>
<div class="panel">
  <img src="{{'assets/img/update_2308/2023-08.png' | relative_url}}" alt="2023-08" style="width: 1100px; height: 200px;">
</div>
<hr>

<div class="flip">2023.06</div>
<div class="panel">2023.06</div>

</body>
</html>
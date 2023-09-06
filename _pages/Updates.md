---
layout: page
title: Updates
permalink: /Updates/
nav: true
nav_order: 2
---

<h4>The identified leading mutations in 2023 are listed as follows:<h4>
<hr>
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
  <option value="2023.05">2023.05</option>
  <option value="2023.04">2023.04</option>
  <option value="2023.03">2023.03</option>
  <option value="2023.02">2023.02</option>
  <option value="2023.01">2023.01</option>
</select>

<div id="panel-202308" class="panel">
  <h4><strong>Outlined Mutation in 2023.08</strong></h4>
  <hr>
  {% include figure.html path="assets/img/update_2308/2023-08.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>2023.08.04 - 2023.08.22</strong>
  <hr>
  {% include figure.html path="assets/img/update_2308/confirmed_202308.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>RBD Mutation Profile of Latest VOIs.</strong>
  <hr>
  {% include figure.html path="assets/img/update_2308/2023-08_VarRBD.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>3D structure illustration</strong>
  <hr>
    <div class="l-page">
    <style>
        .molstar {
            position: relative;
            padding-bottom: 50%;
        }
    </style>
    <link rel="stylesheet" type="text/css" href="https://molstar.org/viewer/molstar.css" />
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <div id="viewer-8" class="molstar" style="display: block; margin-left:auto; margin-right:auto; padding-bottom: 50%;"></div>
    <script type="text/javascript">
        molstar.Viewer.create('viewer-8', {
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
  <h4><strong>Outlined Mutation in 2023.07</strong></h4>
  <hr>
  {% include figure.html path="assets/img/update_2307/2023-07.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>2023.06.30 - 2023.07.05</strong>
  <hr>
  {% include figure.html path="assets/img/update_2307/confirmed_202307.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>3D structure illustration</strong>
  <hr>
    <div class="l-page">
    <style>
        .molstar {
            position: relative;
            padding-bottom: 50%;
        }
    </style>
    <link rel="stylesheet" type="text/css" href="https://molstar.org/viewer/molstar.css" />
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <div id="viewer-7" class="molstar" style="display: block; margin-left:auto; margin-right:auto; padding-bottom: 50%;"></div>
    <script type="text/javascript">
        molstar.Viewer.create('viewer-7', {
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
            viewer.loadSnapshotFromUrl("{{ 'assets/img/update_2307/LM_2023_07.molx' | relative_url }}", 'molx');
        });
    </script>
</div>
</div>

<div id="panel-202306" class="panel">
  <h4><strong>Outlined Mutation in 2023.06</strong></h4>
  <hr>
  {% include figure.html path="assets/img/update_2306/2023-06.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>2023.06.01 - 2023.06.13</strong>
  <hr>
  {% include figure.html path="assets/img/update_2306/confirmed_2306.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>3D structure illustration</strong>
  <hr>
    <div class="l-page">
    <style>
        .molstar {
            position: relative;
            padding-bottom: 50%;
        }
    </style>
    <link rel="stylesheet" type="text/css" href="https://molstar.org/viewer/molstar.css" />
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <div id="viewer-6" class="molstar" style="display: block; margin-left:auto; margin-right:auto; padding-bottom: 50%;"></div>
    <script type="text/javascript">
        molstar.Viewer.create('viewer-6', {
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
            viewer.loadSnapshotFromUrl("{{ 'assets/img/update_2306/LM_2023_06.molx' | relative_url }}", 'molx');
        });
    </script>
</div>
</div>

<div id="panel-202305" class="panel">
  <h4><strong>Outlined Mutation in 2023.05</strong></h4>
  <hr>
  {% include figure.html path="assets/img/update_2305/2023-05.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>2023.05.01 - 2023.05.12</strong>
  <hr>
  {% include figure.html path="assets/img/update_2305/confirmed_2305.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>3D structure illustration</strong>
  <hr>
    <div class="l-page">
    <style>
        .molstar {
            position: relative;
            padding-bottom: 50%;
        }
    </style>
    <link rel="stylesheet" type="text/css" href="https://molstar.org/viewer/molstar.css" />
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <div id="viewer-5" class="molstar" style="display: block; margin-left:auto; margin-right:auto; padding-bottom: 50%;"></div>
    <script type="text/javascript">
        molstar.Viewer.create('viewer-5', {
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
            viewer.loadSnapshotFromUrl("{{ 'assets/img/update_2305/LM_2023_05.molx' | relative_url }}", 'molx');
        });
    </script>
</div>
</div>

<div id="panel-202304" class="panel">
  <h4><strong>Outlined Mutation in 2023.04</strong></h4>
  <hr>
  {% include figure.html path="assets/img/update_2304/2023-04.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>2023.04.01 - 2023.04.21</strong>
  <hr>
  {% include figure.html path="assets/img/update_2304/confirmed_2304.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>3D structure illustration</strong>
  <hr>
    <div class="l-page">
    <style>
        .molstar {
            position: relative;
            padding-bottom: 50%;
        }
    </style>
    <link rel="stylesheet" type="text/css" href="https://molstar.org/viewer/molstar.css" />
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <div id="viewer-4" class="molstar" style="display: block; margin-left:auto; margin-right:auto; padding-bottom: 50%;"></div>
    <script type="text/javascript">
        molstar.Viewer.create('viewer-4', {
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
            viewer.loadSnapshotFromUrl("{{ 'assets/img/update_2304/LM_2023_04.molx' | relative_url }}", 'molx');
        });
    </script>
</div>
</div>

<div id="panel-202303" class="panel">
  <h4><strong>Outlined Mutation in 2023.03</strong></h4>
  <hr>
  {% include figure.html path="assets/img/update_2303/2023-03.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <img src="{{'assets/img/update_2303/2023-03.png' | relative_url}}" alt="2023-03" style="width: 1100px; height: 300px;">
  <br>
  <br>
  <strong>2023.03.01 - 2023.03.21</strong>
  <hr>
  {% include figure.html path="assets/img/update_2303/confirmed_2303.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>3D structure illustration</strong>
  <hr>
    <div class="l-page">
    <style>
        .molstar {
            position: relative;
            padding-bottom: 50%;
        }
    </style>
    <link rel="stylesheet" type="text/css" href="https://molstar.org/viewer/molstar.css" />
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <div id="viewer-3" class="molstar" style="display: block; margin-left:auto; margin-right:auto; padding-bottom: 50%;"></div>
    <script type="text/javascript">
        molstar.Viewer.create('viewer-3', {
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
            viewer.loadSnapshotFromUrl("{{ 'assets/img/update_2303/LM_2023_03.molx' | relative_url }}", 'molx');
        });
    </script>
</div>
</div>

<div id="panel-202302" class="panel">
  <h4><strong>Outlined Mutation in 2023.02</strong></h4>
  <hr>
  {% include figure.html path="assets/img/update_2302/2023-02.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>2023.02.03 - 2023.02.20</strong>
  <hr>
  {% include figure.html path="assets/img/update_2302/confirmed_2302.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>3D structure illustration</strong>
  <hr>
    <div class="l-page">
    <style>
        .molstar {
            position: relative;
            padding-bottom: 50%;
        }
    </style>
    <link rel="stylesheet" type="text/css" href="https://molstar.org/viewer/molstar.css" />
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <div id="viewer-2" class="molstar" style="display: block; margin-left:auto; margin-right:auto; padding-bottom: 50%;"></div>
    <script type="text/javascript">
        molstar.Viewer.create('viewer-2', {
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
            viewer.loadSnapshotFromUrl("{{ 'assets/img/update_2302/LM_2023_02.molx' | relative_url }}", 'molx');
        });
    </script>
</div>
</div>

<div id="panel-202301" class="panel">
  <h4><strong>Outlined Mutation in 2023.01</strong></h4>
  <hr>
  {% include figure.html path="assets/img/update_2301/2023-01.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>2023.01.17 - 2023.01.31</strong>
  <hr>
  {% include figure.html path="assets/img/update_2301/confirmed_2301.png" title="example image" class="img-fluid rounded z-depth-1" %}
  <br>
  <br>
  <strong>3D structure illustration</strong>
  <hr>
    <div class="l-page">
    <style>
        .molstar {
            position: relative;
            padding-bottom: 50%;
        }
    </style>
    <link rel="stylesheet" type="text/css" href="https://molstar.org/viewer/molstar.css" />
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <div id="viewer-1" class="molstar" style="display: block; margin-left:auto; margin-right:auto; padding-bottom: 50%;"></div>
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
            viewer.loadSnapshotFromUrl("{{ 'assets/img/update_2301/LM_2023_01.molx' | relative_url }}", 'molx');
        });
    </script>
</div>
</div>

</body>
</html>


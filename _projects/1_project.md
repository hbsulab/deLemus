---
layout: page
title: 2023.08
description: 
importance: 1
category: 2023
---
  <h3><strong>Outlined mutations</strong></h3>
  <hr>
  <img src="{{'assets/img/update_2308/2023-08.png' | relative_url}}" alt="2023-08" style="width: 1150px; height: 220px; margin-left:auto; margin-right:auto;">
  <br>
  <br>
  <h3><strong>2023.08.04 - 2023.08.22</strong></h3>
  <hr>
  <img src="{{'assets/img/update_2308/confirmed mutations.png' | relative_url}}" alt="Confirmed mutations" style="width: 600px; height: 300px;">
  <br>
  <br>
  <h3><strong>RBD Mutation Profile of Latest VOIs.</strong></h3>
  <hr>
  <img src="{{'assets/img/update_2308/2023-08_VarRBD.png' | relative_url}}" alt="RBD profile" style="width: 700px; height: 300px;">
  <br>
  <br>
  <h3><strong>3D structure illustration</strong></h3>
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


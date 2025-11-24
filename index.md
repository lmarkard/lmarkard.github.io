---
title: Home
---

# NeuroPhysio Oerlikon: Your home away from home

<div class="intro-container">
  <div style="width: 100%">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
  </div>

  <div class="thumbnail center">
    <img class="thumbnail" src="{{ '/assets/img/lmarkard.jpeg' | relative_url }}">
  </div>
</div>

# Find me

<div id="demoMap" style="height:250px"></div>
<script src="assets/js/OpenLayers.js"></script>
<script>
  map = new OpenLayers.Map("demoMap");
  map.addLayer(new OpenLayers.Layer.OSM());
  map.zoomToMaxExtent();
</script>

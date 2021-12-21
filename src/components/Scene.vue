<template>
  <v-app>
    <v-content>
        <Scene/>
    </v-content>
  </v-app>
</template>

<script type="module">

  // Find the latest version by visiting https://cdn.skypack.dev/three.

  import * as THREE from 'https://cdn.skypack.dev/pin/three@v0.135.0-pjGUcRG9Xt70OdXl97VF/mode=imports,min/optimized/three.js';

  const scene = new THREE.Scene();

</script>

<style scoped>
.scene {
  width: 100%;
  height: 100%;
}
</style>


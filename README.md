# Shooting Stars Animation

<div class="shooting-star"></div>

<style>
body {
  overflow: hidden;
}

.shooting-star {
  position: absolute;
  width: 5px;
  height: 5px;
  background-color: white;
  animation: shooting 2s infinite linear;
}

@keyframes shooting {
  0% {
    left: 0;
    top: 50%;
    opacity: 0;
  }
  100% {
    left: 100%;
    top: 0;
    opacity: 1;
  }
}
</style>

<!---
ABottleOfSprite/ABottleOfSprite is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

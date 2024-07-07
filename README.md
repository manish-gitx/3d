<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rolling Cube with A-Frame</title>
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
    <style>
        body { margin: 0; }
    </style>
</head>
<body>
    <a-scene>
        <a-box position="0 0.5 -3" rotation="0 0 0" color="#4CC3D9"
               animation="property: rotation; to: 0 360 360; loop: true; dur: 2000">
        </a-box>
        <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
        <a-sky color="#ECECEC"></a-sky>
    </a-scene>
</body>
</html>

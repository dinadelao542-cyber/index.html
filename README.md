# index.html
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Para ti 💙</title>
<style>
html, body {
    height: 100%;
    margin: 0;
    padding: 0;
    background: black;
    overflow: hidden;
}

body {
    width: 100vw;
    height: 100vh;
    color: white;
    font-family: 'Arial', sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    position: relative;
}

.stars, .stars2, .stars3 {
    position: absolute;
    top: 0; left: 0;
    width: 100vw; height: 100vh;
    background: transparent;
    display: block;
    pointer-events: none;
    z-index: 0;
}
.stars {
    background: url('https://raw.githubusercontent.com/VincentGarreau/particles.js/master/demo/img/stars.png') repeat;
    animation: moveStars 100s linear infinite;
    opacity: 0.8;



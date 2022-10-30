<template>
  <div class="gris vw-100 vh-100 d-flex justify-content-center p-3">
    <div class="d-flex flex-column align-items-center rounded-4 my-auto mx-auto justify-content-center blanco p-3">
    <img class="img-fluid rounded-4" src="../images/image-qr-code.png" alt="Imagen QR" />
    <p class="fw-bold mt-3 fs-4 text-center azul">Improve your front-end<br> skills by building projects</p>
    <p class="fw-light text-center">Scan the QR code to visit Frontend <br /> Mentor and take your coding skills to <br>the next level</p>
    </div>
  </div>
  
</template>

<style>

.blanco {
  background-color: white;
  z-index: 1;
}

.gris {
  background-color: hsl(212, 45%, 89%);
}

.azul {
  color:hsl(218, 44%, 22%);
}

img {
  width: 350px;
  height: 350px;
}

.azul_oscuro {
  color:darkblue;
}

p {
  font-size: 15px;
  font-family: 'Outfit', sans-serif;
}

@media screen and (max-width:375px) {
}
</style>

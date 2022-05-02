# Promocion-2022

- Temario a Oct. 2022 de Cap. a Myr. I.C.E.:
  - Tec/Admtvo   231 -> Domingo
  - Mando         85 -> Lunes
  - Tactica      143 -> Martes
  - Normatividad 120 -> Miercoles
  - Tactica      143 -> Jueves
  - Legislacion  159 -> Viernes
  - Operaciones  314 -> Sabado
  - Total:      1052 Paginas


-----------------------------------------------------------------------------------
# Cambiar PDF a fondo negro en Chrome
  - https://www.reddit.com/r/chrome/comments/e3txhi/change_pdfs_to_dark_mode/
  
var cover = document.createElement("div");
let css = `
    position: fixed;
    pointer-events: none;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background-color: white;
    mix-blend-mode: difference;
    z-index: 1;
`
cover.setAttribute("style", css);
document.body.appendChild(cover);

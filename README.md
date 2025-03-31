# surf
style:
.trilho {
    width: 350px;
    height: 150px;
    background-color: rgb(85, 91, 104);
    border-radius: 150px;
    text-align: center;
    margin-left: 38%;margin-right:20%;
    position: relative;
    cursor: pointer;

}

.trilho .indicador {
    width: 150px;
    height: 150px;
    background-color: black;
    border-radius: 200px;
    transform: scale(.9);
    position: absolute;
}
.trilho.dark .indicador{
    left: 200px;

}

SCRIPT.JS
  let trilho = document.getElementById('trilho')

    trilho.addEventListener('click',()=>{
        trilho.classList.toggle ('dark')
    })
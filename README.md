# fquery
Fake jQuery

Ejemplos de uso:

Crear eventos:

$("elemento").on("click", function(){ 
    console.log("Click!")
})

Editar css

$("elemento").css({
    color:"blue",
     background: "green"
})

O para obtener el valor de X elemento

$("elemento").css("background") // Devolverá 'green'

Añadir una nueva clase a un elemento:

$("elemento").addClase("nuevaclase")

remover clase:

$("elemento").removeClass("nuevaclase")

Para inicializar el fQuery:

$().ready(function(){
    //code...
})


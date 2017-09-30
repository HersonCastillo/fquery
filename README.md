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

Establecer u obtener el valor del atributo de un elemento:

$("elemento").attr("name") // 'nombreelemento'

Establecer o cambiar el valor un atributo para un elemento:

$("elemento").attr("disabled", "true")

Para inicializar el fQuery:

$().ready(function(){
    //code...
})


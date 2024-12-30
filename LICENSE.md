var hora = 24
console.log("Agora são exatamente " + hora + " horas")
if (hora < 12 && hora >= 5){
    console.log("Esta de manhã")
}



     else if(hora <= 18 && hora > 12){
     console.log("Esta de tarde")}

     else if(hora < 23 && hora > 18) {
        console.log("Esta de noite")
        }
    


    else if(hora > 23 && hora <= 24 || hora < 5){
        console.log("Boa madrugada")
    }

    else{
        console.log("Hora invalida")
    }


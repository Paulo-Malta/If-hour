var s = new Date();
var c = s.getMinutes();

if(c < 30){
    console.log("Você esta mais perto da ultima hora")
}

else if(c == 30){
    console.log("Você esta na metade entre os dois")
}

else if(c > 30){
    console.log("Vocês esta mais proximo da proxima hora")
}

else{
    console.log("Minutos invalido")
}



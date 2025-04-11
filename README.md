# javascript_prova
questao3
let banco = []
banco.push('pessoa1')
banco.push('pessoa2')
banco.push('pessoa3')
console.log(banco)
for(let i = 0;i<3; i++){
    banco.shift()
    console.log(banco)}

questao5
let idade=45;
let categoria=(0);
if (idade < 12)
   { categoria=('ingresso infantil');}
else if (idade < 18 && idade >= 12)
   { categoria=('ingresso Adolescente');}
else if (idade < 60 && idade >= 18)
   { categoria=('ingresso Adulto');}
else
   { categoria=('ingresso senior');}
   console.log("tipo de ingresso: "+categoria)



    

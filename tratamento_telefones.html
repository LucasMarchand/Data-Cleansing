<!DOCTYPE html>
<html>
<body>

<p>Click the button to extract characters from the string.</p>

<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
function myFunction() {
  
	function validaDDD(str) {
        var d = '';
        str = str.replace(/[^0-9]/g,'');
        str = parseInt(str, 10).toString();
        var res = str.substring(0, 2).replace(/[^1-9]/g,'');
        if(res.length != 2){
            d = '';
        } else {
            d = '(' + res + ')';
        }
        return d;
    }
   
    function validaTelefone(t){
    
        if(t.slice(0,1) == '9' || t.slice(0,1) == '8' ||
            t.slice(0,1) == '7' || t.slice(0,1) == '6') {       // talvez seja um celular
            
            if(t.length == 8){  // celular com 8 dígitos
                p1 = '9'.concat(t.slice(0,4));
                p2 = t.slice(4,8);
                t = p1+'-'+p2;
            } else if(t.length == 9 && t.slice(0,1) == '9'){    // celular com 9 dígitos
                p1 = t.slice(0,5);
                p2 = t.slice(5,9);
                t = p1+'-'+p2;
            } else {
                // se não encontrou nada acima não é um celular
                t = '';
            }
            
        } else if(t.slice(0,1) == '5' || t.slice(0,1) == '4' || t.slice(0,1) == '3' || t.slice(0,1) == '2') { // talvez seja um telefone fixo
            if(t.length == 8){  // telefone fixo
                p1 = t.slice(0,4);
                p2 = t.slice(4,8);
                t = p1+'-'+p2;
            } else {
                // possui um caractere a mais que o desqualifica
                t = '';
            }
            
        } else {
            // não começa com um dígito válido
            t = '';
        }
        
        return t;
    }
    
    function validacaoCompleta(fieldTel, fieldDDD) {
     
        var p1 = '';
        var p2 = '';
        var aux1 = '';
        var aux2 = '';
        
        var ddd = validaDDD(fieldDDD);
        var tel = fieldTel;
        
        tel = tel.replace(/[^0-9]/g,'');        // deixa só números
        tel = parseInt(tel, 10).toString(); // tira os zeros da frente
        
        if(tel.length < 8){         // número inválido
            tel = null;           // menor que 8 caracteres
        } else if(tel.length > 11){ // número inválido
            tel = null;           // maior que 11 caracteres
        } else {
            if(tel.length <= 9) {   // quantidade correta de dígitos
                tel = validaTelefone(tel);
                if(tel != '') {     // se a validação foi OK.
                    tel =  ddd+''+tel;   // montagem do telefone
                } else { tel = null }
            } else {                                            // talvez os dois primeiros dígitos sejam um DDD
                aux1 = validaTelefone(tel.slice(2,tel.length)); // valida o telefone sem o DDD
                if(aux1 != '') {                                // se a validação do telefone está OK.
                    aux2 = validaDDD(tel.slice(0,2));           // pega o DDD e testa
                    if(aux2 != '') {                            // se a validação do DDD estiver OK
                        ddd = aux2;                             // substitui o DDD anterior por este
                    }
                    tel = ddd+''+aux1;  // montagem do telefone
                } else { tel = null }
            }
        }
        
        return tel;
    }
    
    // para testes
    var telefoneFinal = '';
    var ddd = '(0051';
    var tel = ' 0488233 -0140';
    
    telefoneFinal = validacaoCompleta(tel, ddd);
	
    if (telefoneFinal == null) { telefoneFinal = 'erro' }
    document.getElementById('demo').innerHTML = telefoneFinal;
}
</script>

</body>
</html>

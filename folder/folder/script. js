function calculate(){
    
    
    const num1=parseFloat(document.getElementById("num1").value);
const num2=parseFloat (document.getElementById("num2").value);
 const operator=  (document.getElementById("operator").value);   
    
    let result;
 if(isNaN(num1)|| isNaN(num2)){
 result="enter both number";
 }else if( operator==="+"){ 
 result=num1+num2; } 
 else if(operator==="-"){
 result=num1-num2;}
 else if (num2===0){
 result="error:cannot divide by zero";}
 else if(operator==="/"){
 result=num1/num2;}
 else if(operator==="*"){
 result=num1*num2;}
 else{
 result="invalide opearator";
 }
    document.getElementById("result").innerText="Result:" + result;
    }

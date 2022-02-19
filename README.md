# Regex-Recursion
let div = 0;
function division(number, dividedBy){
    if (number % dividedBy == 0 && number >= 1 && dividedBy >= 1) {
        division(number - dividedBy, dividedBy);  
        div++;
    }
    return div;
}


function pow(x,n){
    if (n > 0)
    return (x * pow(x, n-1));
  else
    return 1
}


let f = 0 ;
function fibonacci(n){
    if (n==0) {
        f = 0;
    }else if(n==1) {
        f = 1;
    }else {
        f = fibonacci(n-2) + fibonacci(n-1);
    }
    return f;
}

node(){
def display = true;
def code
    stage('checkout'){
     checkout scm
        code = load 'code.groovy'
    }
stage('input'){
    println("taking input")
}
stage('compile'){

     code.complie()
}
if(!display){
    return ;
}
stage('process'){
    if(!display){
    return ;
}
    println("proccessing code")
}
stage('display'){
    code.dispay()
}

}

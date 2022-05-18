node(){
def display = true;
def code = load 'code.groovy'
    stage('checkout'){
     checkout scm
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

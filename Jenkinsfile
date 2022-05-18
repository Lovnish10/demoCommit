
NAME  ="love Jain"
node(){
def display = true;
def code = load 'code.groovy'
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
    name()
}
stage('display'){
    code.dispay()
}

}


def name(){
    stage('printing name'){
        println("my name is ${NAME}")
    }
}

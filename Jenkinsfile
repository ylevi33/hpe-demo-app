node { 
    //Checkout scm
    checkout scm

    stage 'test'
    sh 'make test'

    
    stage 'publish'
    sh 'make publish'
}

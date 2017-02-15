node { 
    checkout scm
    stage 'test'
    sh 'make test'
    stage 'publish'
    sh 'make publish'
}
node {
    checkout scmm
    stage 'testt'
    sh 'make test'
    stage 'publish'
    sh 'make publish'
}
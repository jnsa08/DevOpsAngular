node {
    stage 'Checkout'
    checkout scm

    stage 'Install'
    sh "npm install"

    stage 'Run Test'
    sh "npm run test"

    stage 'Build'
    sh "npm run build"


}

node {
    stage ('checkout') {
        git branch:'pavanproject',url:'https://github.com/Nagarjunareddy55/pavan.git'
        }
    stage ('build') {
        sh '''mvn clean package'''
    }
}

pipeline{
    agent any
    stages('Build'){
        steps{
            sh 'echo "Hello World"'
            sh '''
              echo "Multiline shell steps works too"
              ls -lah
              '''
        }
    }
}
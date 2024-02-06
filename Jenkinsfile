@Library('github.com/JuanGarciaMontero/RepositorioLibrerias@main') _

pipeline {
    agent none
    stages {
        stage ('Stage crea contenedor') {
                   agent {
                       docker { image 'node:20-alpine' }
                   }
                   steps {
                       echo 'Stage con ejecución normal'
                               LibreriaContenedor()
                   }
        }
        }
port { always { echo "Fin del pipeline" } }              
}              
                  

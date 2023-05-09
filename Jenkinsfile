pipeline {
    agent any

    stages {
        stage('Validacion') {
            steps {
                // Get some code from a GitHub repository
                echo "Validando datos..."
                sh 'python --version'
                sh 'pip list'
                sh 'ls'
                script {
                    currentBuild.displayName = "Nov-2022-BD55"
                    currentBuild.description = "planificacion.quipucamayoc"
                }
            }
        }
        stage('Registro') {
            steps {
                // Get some code from a GitHub repository
                echo "Registrado en redmine..."

                // To run Maven on a Windows agent, use
                // bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }
        }
        stage('Conversion') {
            steps {
                // Get some code from a GitHub repository
                echo "Convirtiendo a select..."

                // To run Maven on a Windows agent, use
                // bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }
        }
        stage('Comparacion') {
            steps {
                // Get some code from a GitHub repository
                echo "Comparacion de registros en incidencias y produccion..."

                // To run Maven on a Windows agent, use
                // bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }
        }
        stage('Backup') {
            steps {
                // Get some code from a GitHub repository
                echo "Guardando registros de produccion..."

                // To run Maven on a Windows agent, use
                // bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }
        }
        stage('Ejecucion') {
         
            steps {
                // Get some code from a GitHub repository
                echo "Guardando registros de produccion..."
                echo 'mvn --version'
            }
        }
    }
}

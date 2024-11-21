pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage("build") {
            steps {
                echo "Building  the application"
            }
        }
      stage("test") {
            steps {
                echo "Testing  the application"
            }
        }
      stage("deploy") {
            steps {
                echo "deploying  the application"
            }
        }
    }
}

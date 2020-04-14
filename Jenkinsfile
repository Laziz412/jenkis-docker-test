pipeline {

    agent {

        docker {

            image 'python'

            label 'any'

        } //docker

    } //agent

    stages {

        stage("Run hello world") {

            steps {

                sh """

                    python hello-world.py

                """

            } //steps

        } //stage

    } //stages

} //pipeline

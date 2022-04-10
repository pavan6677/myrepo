pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hi') {
            steps {
                echo 'How r u'
            }
        }
        stage('git') {
            steps {
                git branch: 'dev', url: 'git \'https://github.com/pavan6677/myrepo.git\''
            }
        }
    }
}
 master

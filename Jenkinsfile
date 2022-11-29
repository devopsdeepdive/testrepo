pipeline {
    agent any
    parameters {
properties([parameters([gitParameter(branch: '', branchFilter: '.*', defaultValue: 'origin/*', name: 'BRANCH_NAME', quickFilterEnabled: false, selectedValue: 'NONE', sortMode: 'NONE', tagFilter: '*', type: 'GitParameterDefinition')])])  }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}

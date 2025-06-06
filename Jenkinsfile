pipeline {
    agent any
    stages {
        stage('Install dependencies') {
            steps {
                bat '"C:\\Users\\Admin\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" -m pip install pandas'
            }
        }
        stage('Run analysis') {
            steps {
                bat '"C:\\Users\\Admin\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" data_analysis.py'
            }
        }
    }
}

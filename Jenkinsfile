pipeline {
    agent any

    stages {
        stage('Vérifier les modifications') {
            when {
                changeset "**/test0.py" // Remplace par ton vrai script (ex: script.py)
            }
            steps {
                echo 'Hello - Le script a été modifié.'
            }
        }
    }
}

//To get the content of Release page
pipeline {
    agent any

    stages {
         stage('build') {
            steps {
                sh 'curl -D- \
   -X GET \
   -H "Authorization: Basic a2xtaXR0YWxAbHV0cm9uLmNvbTpiTklzOGlpT3ZneFhhbURsQ3l5RDdEQkM=" \
   -H "Content-Type: application/json" \
   "https://lutron.atlassian.net/wiki/rest/api/content/149245035?expand=body.storage"'
            }
        }
    }
}


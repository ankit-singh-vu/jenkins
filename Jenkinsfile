// pipeline {
//     agent { docker { image 'node:20.10.0-alpine3.19' } }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'node --version'
//                 sh 'echo "Hello World"'
//             }
//         }
//     }
// }

// pipeline {
//     agent any
//     stages {
//         stage('Build') {
//             steps {
//                 sh 'echo "Ankit is here"'
//                 sh 'echo "Hello World"'
//                 sh '''
//                     echo "Multiline shell steps works too"
//                     ls -lah
//                 '''
//             }
//         }
//     }
// }


pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "starting npm install"'
                sh 'pwd'
                sh 'cd ./node-backend/  && ls -la  && npm i && npm start'
                sh 'ls -la' //its coming back to root dir so using all cmds in one line
                // sh 'npm i'
                // sh 'npm start'
            }
        }
    }
}
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
                // sh 'cd /media/dell/1C2210EF2210D01E/MyDevops/node-backend/'
                sh 'ls -la'
                // sh 'npm i'
                // sh 'npm start'
            }
        }
    }
}
node {
 stage('Clone'){
     git 'https://github.com/rrolet/jenkins.git'
 }   
 stage('Build'){
     sh label: '', script: 'javac Main.java'
 } 
 stage('Run'){
     sh label: '', script: 'java Main'
 } 
}

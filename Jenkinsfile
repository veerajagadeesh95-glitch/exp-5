pipeline {
agent any

stages {
stage ('compile') {
steps {
sh 'javac Hello.java'
}
}
stage ('run') {
steps {
sh 'java Hello'
}
}
}
}

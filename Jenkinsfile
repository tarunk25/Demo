pipeline {

agent any

stages {

stage('Build') {

steps {

bat 'javac helloworld.java'
  bat 'java -version'

}

}

stage('Run') {

steps {
 bat 'java helloworld'
  

}
}
}
}

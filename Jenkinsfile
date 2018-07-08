pipeline {
  agent any
  stages {
    stage('Clean_WorkSpace') {
      steps {
        bat 'echo Empty WorkSpace'
      }
    }
    stage('Run Test') {
      steps {
        bat '"C:\\Program Files\\apache-jmeter-4.0\\bin\\jmeter.bat" -n -t "D:\\SandBox\\JMeter_DashBoards\\Demo.jmx" -l "D:\\SandBox\\JMeter_DashBoards\\Sample.csv" -e -o "D:\\SandBox\\JMeter_DashBoards\\Jenkins"'
      }
    }
  }
}
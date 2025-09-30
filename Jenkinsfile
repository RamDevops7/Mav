pipeline{
    agent any
stages{
stage('SCM'){
steps{
git branch: "main", url:'https://github.com/RamDevops7/Mav.git'
}
}
stage('Build and Unit Test'){
steps{
  sh 'mvn clean package'
}
}
stage('Done'){
steps{
echo 'Pipeline steps completed'
}
}
}
}

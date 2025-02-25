pipeline
{
agent any
stages
{
stage('clone')
{
steps
{
git 'https://github.com/zorouchicha/github-demo.git'
}
}
stage('build')
{
steps{
sh 'javac hello.java'
}
}
stage('run')
{
steps
{
sh 'java helllo'
}
}
}
}

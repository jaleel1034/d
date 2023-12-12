pipeline{
agent any
stages{
stage('check validate'){
steps{
echo 'i am validating the code'
}
}
stage('compilation'){
echo 'i am compiling the code'
}
}
stage('install'){
echo 'i am installing the code'
}
}
stage('deploy'){
echo 'i am deploying the code'
}
}
}
}

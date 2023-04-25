pipeline{
  agent any
  parameters {
    string(name: 'DEPLOY_ENV', defaultValue: 'staging', description: '') 
    text(name: 'DEPLOY_TEXT', defaultValue: 'One\nTwo\nThree\n', description: '')
    booleanParam(name: 'TOGGLE', defaultValue: true, description: 'Toggle this value')
    choice(name: 'CHOICE', choices: ['One', 'Two', 'Three'], description: 'Pick something')
    file(name: 'FILE', description: 'Some file to upload')
    password(name: 'PASSWORD', defaultValue: 'SECRET', description: 'A secret password')
}
  stages{
    stage('testing'){
          steps{
            sh 'touch bharath.txt'      
          }
     }
  
  }

}

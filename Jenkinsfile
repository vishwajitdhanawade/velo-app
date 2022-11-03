pipeline {

  agent {

           label {
                 label 'built-in'
                  customWorkspace '/mnt/vishwa'
                   
                 }
        }
       stages {

                 stage ('make dir') {

                 steps {
                           sh "rm -rf *"
                           sh "mkdir dir1"
                           sh "sh touch file1"                           
                         }


}

}

}

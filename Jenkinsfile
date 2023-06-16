//declerative
pipeline{
    agent any // where to execute node1, linux node, windows node and etc
    stages{
        stage("build"){
            steps {
                echo "building stage "
                script{
                    def test= 2+3 > 3 ? 'cool': 'notcool'
                    echo test
                }
                }
        }
        stage("test_dev_stage"){
            steps {
                 echo "testing stage "
                 echo " adding second commit"
                }
        }
        stage("deploy"){
            steps {
                 echo "deoloying stage "
                }
        }
    }
}


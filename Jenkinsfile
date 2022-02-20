pipeline {
    agent any
    
    stages{
        stage("Build"){
            steps{
                echo "Perform build"
                sh "g++ main.cpp -o ./a.out"
            }
        }
        
        stage("Test"){
            steps{
                echo "Perform test"
                sh "./a.out"
            }
        }
        
        stage("Deploy"){
            steps{
                echo "Perform build"
            }
        }
    }
}

#!groovy

@Library('jenkinslib') _     

def mytools = new org.devops.tools()



pipeline {
    agent any

    stages {
        //下载代码
        stage("GetCode"){ 
            steps{  
                timeout(time:5, unit:"MINUTES"){   
                    script{ 
                        mytools.PrintMes("this is my lib", "green")
                    }
                }
            }
        }
    }
}

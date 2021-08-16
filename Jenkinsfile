properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("Clone"){
        git branch: 'main', url: 'https://github.com/Amitk3293/***'
    }
    stage("Show files"){
        sh 'ls -ltr'
    }
}

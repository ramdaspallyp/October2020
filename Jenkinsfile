node {
    stage('SCM'){
        git 'https://github.com/wakaleo/game-of-life.git'
    }
    stage('Build the Code'){
        sh 'mvn package'
    }
    stage('archive artifact') {
        archive 'gameoflife-web/target/gameoflife.war'
}   
    /*stage('junit'){
        junit 'gameoflife-web/target/surefire-reports/*.xml'
}*/
}


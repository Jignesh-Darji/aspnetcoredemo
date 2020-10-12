node {
    stage('Checkout git repo') {
      git branch: 'master', url: 'https://github.com/Jignesh-Darji/aspnetcoredemo.git'
    }
    stage('build and publish') {
        sh(script: "dotnet publish C:\\Users\\jik\\source\\repos\\aspnetcoredemo\\aspnetcoredemo.sln -c Release ", returnStdout: true)
    }
}

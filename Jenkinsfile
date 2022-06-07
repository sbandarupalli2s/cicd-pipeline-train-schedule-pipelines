pipeline{
    agent any
    
    stages{
        stage(build){
            echo "this is the build stage."
            sh './gradle build --no-daemon'
            archiveArtifacts arifacts: 'dist/trainSchedule.zip'
        }
    }

}

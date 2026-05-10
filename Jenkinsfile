pipeline {
    agent any
    stages{
        stage("build")
        steps{
            echo "We buliding the image"
        }

        stage("Deploy to registry")
        steps{
            echo "Pushing image to registry"
        }

        stages("running the Application")
        steps{
            echo "basically kubectl Apply phase "
        }

        


    }
}
